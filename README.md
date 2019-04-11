# 🎰 Markdown Playgrounds for Swift

This app reads and writes Markdown documents that contain Swift code. This code can be executed as well: you can run individual code blocks, or all the blocks in a file.

We're using this app to update our book [Advanced Swift](https://www.objc.io/books/advanced-swift/), and while blogging — it's very useful!

### How the app works

The app works by sending Swift code to a REPL instance, and reading back the results. Compared to Swift Playgrounds or Xcode's playgrounds, this is quite limiting, but it also means we can keep things simple.

<img width="912" alt="Screen Shot 2019-04-02 at 12 51 40" src="https://user-images.githubusercontent.com/5382/55397985-bdfca180-5547-11e9-8820-7cf3012c6e53.png">

### Learn more

We're documenting the building of this app on [Swift Talk](https://talk.objc.io/collections/markdown-playgrounds), a weekly video series of conversational live-coding hosted by [Chris Eidhof](https://twitter.com/chriseidhof) and [Florian Kugler](https://twitter.com/floriankugler).

The [first episode](https://talk.objc.io/episodes/S01E145-setting-up-a-document-based-app) previews the app, and is free to watch.


## Building

- You need to have [cmark](https://github.com/commonmark/cmark) installed from master (not via homebrew). If you use the version from homebrew, you won't get proper syntax highlighting (especially for inline elements).
- This project uses Swift Package Manager. You can either run "swift build" or do "swift package generate-xcodeproj"

## Future Direction

This project could head in a number of directions, and there are many useful features we could add. Our main goal is to keep using this for authoring Swift-heavy Markdown, when deciding features that will guide our decisions.

To keep things simple, we have collected a list of todos in [todo.txt](todo.txt).

## License

This library is released under the MIT license. See LICENSE for details.

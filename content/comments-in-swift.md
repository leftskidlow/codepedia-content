<!--
---
Subjects: # Please first look to use Subjects that are already listed at author.codecademy.com/browse/categories
  - "Learn Swift"
  - "iOS and Swift Fundamentals"
Tags: # Please first look to use tags that are already listed at author.codecademy.com/browse/tags
  - "#Comment"
  - "#Swift"
  - "#Style"
Catalog Content: # Please use course/path landing pages, rather than linking to individual content items. If listing multiple URLs, please put the most relevant one first 
  - "https://www.codecademy.com/learn/learn-swift"
  - "https://www.codecademy.com/learn/paths/build-ios-apps-with-swiftui"
---
-->

# Comments in Swift

[Introduction] Comments in Swift represent text that is useful to the programmer or developement team. Think of them as notes or reminders to yourself of important concepts or ideas that need a little explaining above the syntax of the raw code. In Swift there are two kinds of comments: single-line comments and multi-line comments. These comments will be completely ignored by the compiler at compile-time. Famous software engineer Martin Fowler once wrote, "Any fool can write code that a computer can understand. Good programmers write code that humans can understand."

## Single-Line Comments
In Swift, as in many other languages, single line comments are prefaced with two consecutive forward slashes (//). They don't have to be their own line, single line comments can be appended at the end of a line to give more context.

```swift
// I represent a comment in Swift
print("Hello World)

let name = "Johnny Appleseed" // I am also a comment! <- So Cool!
```

## Multi-Line Comments
Multi-line comments allow for greater context and readability of a concept or idea that your program is doing. It is also commonly used for metadata information like authorship and copyright information.

```swift
/* Here we can write all sorts of stuff about the program we are writing AND
   if we want to carry it down onto the next line so that it looks professional
   and doesn't scroll across the whole page, we can do that.
*/

/* This space can be used to write notes to ourself about ideas that we want 
   to implement and just haven't or if our algorithm isn't easily legible through
   the code, we can explain it here. This is especially important if we are part
   of a team separated by time and space and communication occurs here instead of an office.
*/
```
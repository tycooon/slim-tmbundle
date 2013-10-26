# A Sublime Text / TextMate Bundle for Slim

## Description

This is a [Sublime Text](http://www.sublimetext.com/) / [TextMate](http://macromates.com/) bundle for [Slim](http://slim-lang.com/) template language. The puprose of this bundle is to improve the [original bundle](https://github.com/slim-template/ruby-slim.tmbundle) by Fred Wu. Since Slim doesn't really need any snippets, this package includes only syntax highlighting and comment hotkey support.

## Features

- Support for unwrapped tag attributes and their values.
- Support for wrapped with `[]{}()` tag attributes (including multiline) and their values.
- Embedded ruby is highlighted using Ruby on Rails syntax (includes all embedded ruby including parameter values).
- Support for multiline comments.
- Support for multiline blocks escaped with `|` and `'`.
- Illegal syntax is highlighted (makes it super easy to migrate from haml).

## Screenshots

##### Original bundle
![Original](https://dl.dropboxusercontent.com/spa/q16ef54fcja6qje/6akya9ff.png)

##### This bundle
![This](https://dl.dropboxusercontent.com/spa/q16ef54fcja6qje/3t1k2rxi.png)

## Installation

#### TextMate 1

    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone https://github.com/tycooon/slim-sublime.git Slim.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

#### TextMate 2

    cd ~/Library/Application\ Support/TextMate/Managed/Bundles/
    git clone https://github.com/tycooon/slim-sublime.git Slim.tmbundle

#### Sublime Text 2

    cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    git clone https://github.com/tycooon/slim-sublime.git Slim.tmbundle

#### Sublime Text 3

    cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
    git clone https://github.com/tycooon/slim-sublime.git Slim.tmbundle

### Notes

This syntax highlighting file was developed using a nice tool called [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev) which allows to edit a JSON file and then convert it to tmLanguage XML. This really helped me a lot since editing Property List format file is a huge pain. Sublime Text provides split view and custom build systems, so I can just press one button and instantly see all the changes I've made taking place in a sample slim file that I have open in a split view. I've actually left the JSON-tmLanguage file in the sources so you are free to compare how much more readable it is. Maybe this info might help someone who is looking into creating tmLanguage files.

If you have any questions or suggestions, you are welcome to post an issue or message me directly.

### Author

Yuri Smirnov (tycoooon@gmail.com)

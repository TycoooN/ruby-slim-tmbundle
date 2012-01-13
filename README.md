# Slim TextMate Bundle

## Description

This is the [TextMate](http://macromates.com/) bundle for [Slim](http://slim-lang.com/), based on the [Fred Wu's Slim bundle](http://github.com/fredwu/ruby-slim-tmbundle).

I left all the snippets &amp; stuff from the original bundle, the only thing I changed was the tmLanguage "syntax coloring" file. Actually I've rewrote it completely from scratch.

This bundle is still in very early stage of development and is not fully tested, so feel free to post an issue if you find any bugs.

## Scnreenshots

- [Before](http://dl.dropbox.com/u/8231702/Screenshots/qhc8gy6j%7E2i%7E.png)
- [After](http://dl.dropbox.com/u/8231702/Screenshots/a5_r-_6_4jom.png)

## Installation

    cd ~/Library/Application\ Support/TextMate/Bundles/
    git clone git://github.com/TycoooN/ruby-slim-tmbundle.git Slim.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Development process

I switched from TextMate to [Sublime Text 2](http://www.sublimetext.com/2) lately so I am using [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev) which allows to edit tmLanguage as JSON file. This really helped me a lot since editing Property List format file is a huge pain. Sublime Text 2 provides split view and custom build systems, so I can just press one button and instantly see all the changes I've made taking place in a sample slim file that I have open in a split view. I've actually left the JSON-tmLanguage file in the sources so you are free to compare how much more readable it is.

If you have any questions or suggestions, you are welcome to post an issue or message me directly.

## Author

Smirnov Yuri aka TycoooN

# InnoSetup for Sublime Text [![Build Status](https://secure.travis-ci.org/idleberg/InnoSetup-Sublime-Text.png)](http://travis-ci.org/idleberg/InnoSetup-Sublime-Text)

[InnoSetup](http://www.jrsoftware.org/isinfo.php) syntax definitions, completions and build system for [Sublime Text](http://www.sublimetext.com/).

![Screenshot](https://raw.github.com/idleberg/InnoSetup-Sublime-Text/master/images/screenshot.gif)

*Screenshot of InnoSetup script in Sublime Text with [Harper theme](https://github.com/idleberg/Harper.tmTheme)*

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `⇧⌘P` on OS X)
3. Select *InnoSetup* and press `Enter`

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/InnoSetup-Sublime-Text.git`

### Manual installation

1. Download the files using the GitHub .zip download option
2. Unzip the files to your Sublime Text `Packages` directory

## Usage

### Completions

Auto-completion will always list all available flags for a command, the first flag displayed is always the default.

### Building

Building requires a properly installed InnoSetup. You can build your script using the default shortcut or from the Tools menu. Output files will be placed in the same folder as your input.

Should the build system be unable to locate the compiler, you should probably re-install InnoSetup to make sure required registry keys are created. Alternatively, you can specify the install location in the environment variable `%INNO_HOME%`.

## License

The MIT License (MIT)

Copyright (c) 2013 Jan T. Sott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/InnoSetup-Sublime-Text) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
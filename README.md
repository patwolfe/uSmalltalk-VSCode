# uSmalltalk-VSCode

Syntax highlighting for the uSmalltalk language.

## Installation

If you haven't already, install the all dependencies by running `npm i`

Build the extension by running `npm run package`

In vscode, use `Install from vsix` to install the extension

## Changes vs wolfep15/uSmalltalk-VSCode

* Enhanced "function" definitions
  * Names of  `class-method`s, `method`s and `define`s are highlighted
  * Parameters are highlighted
* `set` and `val` highlight the variable
* instance variables are highlighted in `[ivars ...]`
* symbol literals now stop once their reach a delimiter (i.e a bracket or a space)
* added support for array literals
* Messages passed to objects are highlighted
* ... probably more

## Needs work

* There's still a few places where comments won't show up when they should


## Methodology

* The grammar was re-written essentially as a transcription of the grammar
  presented in Prof. Ramsey's "Build, Prove, Compare"

* Written using [Iro](https://eeyo.io/iro/documentation/) which can compile 
the file down to textmate format.
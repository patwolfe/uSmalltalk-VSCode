# uSmalltalk-VSCode

Syntax highlighting for the uSmalltalk language.

## Installation

If you haven't already, install the all dependencies by running `npm i`

Build the extension by running `npm run package`

In vscode, use `Install from vsix` to install the extension


## Needs work

* There's still a few places where comments won't show up when they should


## Methodology

* The grammar was re-written essentially as a transcription of the grammar
  presented in Prof. Ramsey's "Build, Prove, Compare"

* Written using [Iro](https://eeyo.io/iro/documentation/), ([web editor](https://eeyo.io/iro/)) which can compile 
the file down to textmate format.

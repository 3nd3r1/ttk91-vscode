# ttk91-vscode README

A [Visual Studio Code](https://code.visualstudio.com/) language support extension for the machine language TTK-91.
TTK-91 is used by [Titokone](https://github.com/titokone/titokone) machine language simulator.

## Installation

-   Search ttk91-vscode in VSCode's marketplace and the extension should be there!
-   Or download the latest vsix file from releases and open it!

## Errors

-   Variables aren't tokenized
-   Jump destinations aren't tokenized
-   Register tokenization is sloppy. For example, pc will be read as register even if it's meant to be a symbol.

## Todo

-   Auto indent after jump destination.
-   Revamp grammar to properly tokenize everything in one machine instruction.

## Credits

-   Grammar from [@jiikai](https://github.com/jiikai/language-ttk91)

**Enjoy!**

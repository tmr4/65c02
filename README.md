# 65c02 Assembler Extension for VS Code

65c02 Assembler is a lightweight version of the [cc65 cross development package](https://cc65.github.io/) designed to work with the WDC 65C02 processor.
<br />

## 65c02 Assembler User Guides

[65c02 Assembler Documentation](C:\\cc65\User_Guides\\ca65 Users Guide.html) which explains everything and contains information about file extension support regarding this extension, too.

## Features

### Supported Syntax

The 65c02 Assembler only supports the WDC 65C02 processor including all new instructions.  The ca65 assembler has been expanded to include additional formats for the bit branch/reset/set instructions, bbr/bbs/rmb/smb, in the form:

        bbr(bbs) bit#, zero page address, branch destination address
        rmb(smb) bit#, zero page address

### Supported File Extensions

- .asm
- .s
- .inc

### Code Snippets

The Directives like _.macro_ can insert Code Snippets with the typically used parameters.
After typing "." you can either press Ctrl+Space to bring up a list of the available directives,
or start typing the directive you need. It will show a short description and examples for each. You can activate the auto-completion by hitting Tab.
<br />

## Build, Start and Debug Integration

- The command _Build_ is assigned to the keys Ctrl+Shift+B
<br />

## Extension Settings

This extension contributes the following settings that you can set up in your User Settings:

* `65c02.path`: set the execution path or command for the cc65 installation, for example "C:\\cc65\\cl65.exe"
* `65c02.args`: set command line arguments for the build, for example "-x"
* `65c02.mainfile`: set the project's main file that should be compiled instead of the currently edited file, for example "[path]\\main.6502.asm"
<br />

## Release Notes for the Extension

### 0.0.1

- Initial commit for WDC 65C02 processor.

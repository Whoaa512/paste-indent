# paste-indent README

This Visual Studio Code [Extension](https://marketplace.visualstudio.com/items?itemName=LesGrieve.paste-indent) is meant to recreate the paste_and_indent feature in Sublime Text 3. That causes pasted content to follow the indentation of the current line.
This began as a fork of https://github.com/partkyle/paste-and-indent but function diverged enough to create a new project.
I tried all of the paste_and_indent VS Code extensions, all have some flaw.
```
Paste and Indent by g3rry
    Some characters are always selected leading to loss of pasted content
Indent on Paste by gazugafan
    No hotkey
    Reformats
paste-and-indent by partkyle
    Pasted contents cannot begin with blank line
Paste with Indent by anhnhoktvn
    Reformats
```
paste-and-indent was the superior extension, so I decided to solve the small problem I had with it. The content I wish to paste often begins with one or more blank lines. The result with paste-and-indent was that nothing would be pasted. With paste-indent, content beginning with blank lines is pasted and content is left justified. Huge thanks to partkyle for preparing this valuable extension.

## Features

Provides a command palette item named paste-indent that will paste text following the indentation of the current line. The pasted block is left justified within the indentation.

There are no keybindings set, but you can set them yourself. I suggest mapping "cmd+shift+v" to the paste-indent command.

## Requirements

None

## Extension Settings

None

## Known Issues

This extension has not been tested with combinations of tab characters and spaces, there may be pitfalls.

## Release Notes

### 0.0.2

Issues-2 Fix remote execution.

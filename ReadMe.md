![Menu](https://i.imgur.com/RcKd96h.png)

Features
=====
* No plugins, just one file
* Fast
* Auto-Completion
* Automatically detect indentation
* 256-color Monokai theme (16-color Monokai-like theme if you're using Windows)
* Sans-serif mono font automatic detection (GUI)
* Extra menu items under Edit option (GUI)
* Paste to vim on ssh-server out-of-box
* Works even without any syntax/color files (e.g. only vim executable)
* For vim beginners only

This vimrc is based on [MiniVim](https://github.com/sd65/MiniVim). It runs on Vim/Gvim >= 7.3 and Neovim >= 0.2

The code is under Public-domain licence.

| Keys      | Action                                                | Description |
| --------- | ----------------------------------------------------- | ----------- |
| Ctrl A    | Move cursor to the beginning of the line              | Just like macOS and terminals |
| Ctrl E    | Move cursor to the end of the line                    | Just like macOS and terminals |
| Ctrl C    | Copy current line / Copy Selection                    | Also copy to a file `clipboard.txt` if you are using terminals |
| Ctrl X    | Cut current line / Cut Selection                      | Also cut to a file `clipboard.txt` if you are using terminals |
| Ctrl V    | Paste                                                 | |
| Ctrl D    | Duplicate current line                                | |
| Ctrl K    | Kill current line / Kill selected lines               | Just like nano |
| Ctrl F    | Search                                                | Case insensitive  |
| /         | Search                                                | Case sensitive    |
| Ctrl R    | Replace                                               | Case sensitive    |
| Ctrl G    | Select all                                            | |
| Ctrl \\   | Comment/Uncomment                                     | Depends on file type |
| Ctrl T    | New tab                                               | |
| Ctrl Z    | Undo                                                  | |
| Ctrl Y    | Redo                                                  | |
| Ctrl S    | Save                                                  | |
| Ctrl W    | Close                                                 | |
| Ctrl Q    | Visual-Block mode                                     | |
| \| (bar)  | Enter multiple-line editing from Visual-Block mode    | |
| Ctrl N    | Next word                                             | |
| Ctrl P    | Previous word                                         | |
| Ctrl U    | Move current line / Selection up                      | Depends on window size |
| Ctrl J    | Move current line / Selection down                    | Depends on window size |
| Ctrl →    | Next word                                             | |
| Ctrl ←    | Previous word                                         | |
| Ctrl ↑    | Jump up multiple lines                                | Depends on window size |
| Ctrl ↓    | Jump down multiple lines                              | Depends on window size |
| Alt →     | Next word                                             | In case Ctrl key is not working in terminal emulators |
| Alt ←     | Previous word                                         | |
| Alt ↑     | Jump up multiple lines                                | Depends on window size |
| Alt ↓     | Jump down multiple lines                              | Depends on window size |
| Shift →   | Select next word                                      | In case Ctrl key is not working in terminal emulators |
| Shift ←   | Select previous word                                  | |
| Shift ↑   | Select multiple lines up                              | Depends on window size |
| Shift ↓   | Select multiple lines down                            | Depends on window size |
| Ctrl B    | Delete a word backward                                | |
| q         | Quit                                                  | Normal mode only |
| Q         | Quit                                                  | Normal mode only |
| Tab       | Indent                                                | |
| Shift Tab | Unindent                                              | |
| Insert    | Paste from `clipboard.txt`                            | Only available in terminals, in case vim clipboard is broken |
| F2        | New tab                                               | Like Byobu |
| F3        | Move to next tab                                      | Like Byobu |
| F4        | Move to previous tab                                  | Like Byobu |
| F10       | Enable/Disable Auto-Completion                        | |
| PageUp    | Jump up multiple lines                                | Depends on window size |
| PageDown  | Jump down multiple lines                              | Depends on window size |
| Home      | Increase font size                                    | GUI only |
| End       | Decrease font size                                    | GUI only |
| - (minus) | Fold/Unfold                                           | Normal mode only |
| Ctrl Backspace    |  Delete a word backward                       | |
| Alt  Backspace    |  Delete a word backward                       | In case Ctrl key is not working in terminal emulators |
| Ctrl Delete       |  Delete a word forward                        | |

## Extra menu items (GUI)

![Menu](https://i.imgur.com/5HfHMOK.png)

## Extra commands (Most of them were added to the GUI Edit menu already)

| Command   | Action                                                    | Description |
| --------- | --------------------------------------------------------- | ----------- |
| OpenDroppedFiles      | Open dropped files to each tab at one time    | |
| JsonBeautify          | Json file beautify                            | Require Python 2/3 |
| JsonMinify            | Json file minify                              | |
| XmlBeautify           | XML file beautify                             | |
| XmlMinify             |                                               | |
| Base64Decode          | Decode base64 file                            | Require Perl |
| Base64Encode          | Encode base64 file                            | Require Perl |
| URLDecode             | Decode URL in current file                    | Require Perl |
| URLEncode             | Encode URL in current file                    | Require Perl |
| MergeToOneLine        | Merge selection to one single line            | |
| RemoveLeadingSpace    |                                               | |
| RemoveTrailingSpace   |                                               | |
| RemoveEmptyLines      |                                               | |
| ToggleCaseToUpper     | Toggle case from selection                    | |
| ToggleCaseToLower     | Toggle case from selection                    | |
| ReverseString         | Reverse selected string                       | |
| FastRender            | Disable everything slowing vim down           | |
| Split2Vertical        | Split window                                  | |
| Split3Vertical        |                                               | |
| Split2Horizontal      |                                               | |
| Split3Horizontal      |                                               | |
| Split4                |                                               | |
| SplitMoveRight        | Move window                                   | |
| SplitMoveLeft         |                                               | |
| SplitMoveUp           |                                               | |
| SplitMoveDown         |                                               | |
| SplitResizeRight      | Resize window                                 | |
| SplitResizeLeft       |                                               | |
| SplitResizeUp         |                                               | |
| SplitResizeDown       |                                               | |
| IndentSpace2          | 2 space indention                             | |
| IndentSpace4          | 4 space indention                             | |
| IndentSpace8          | 8 space indention                             | |
| IndentTab2            | 2 tab indention                               | |
| IndentTab4            | 4 tab indention                               | |
| IndentTab8            | 8 tab indention                               | |
| LineEndingUnix        | \\n line ending                               | |
| LineEndingDos         | \\r\\n line ending                            | |
| LineEndingMac         | \\r line ending                               | |
| EncodingUTF8          |                                               | |
| EncodingBig5          |                                               | |
| EncodingGBK           |                                               | |
| EncodingJapan         |                                               | |
| EncodingKorea         |                                               | |
| EncodingUTF16LE       |                                               | |
| EncodingUTF16BE       |                                               | |
| EncodingAnsi          |                                               | |
| Opencc2T              |                                               | Require Opencc |
| Opencc2S              |                                               | |
| AutoCompleteEnable    |                                               | |
| AutoCompleteDisable   |                                               | |
| SshPasteEnable        |                                               | |
| SshPasteDisable       |                                               | |
| Download              | Download a file from a given URL              | |

## Install

* Use curl

```sh
curl https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc -o ~/.vimrc
```

* Use wget

```sh
wget https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc -O ~/.vimrc
```

<!-- * Use Python2 -->
<!-- ```sh -->
<!-- python2 -c "import urllib;from os.path import expanduser; urllib.urlretrieve('https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc', expanduser('~') + '/.vimrc')" -->
<!-- # python2 -c "import urllib; print urllib.urlopen('https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc'.encode('UTF-8')).read()" > ~/.vimrc -->
<!-- ``` -->

<!-- * Use Python3 -->
<!-- ```sh -->
<!-- python3 -c "import urllib.request;from os.path import expanduser; urllib.request.urlretrieve('https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc', expanduser('~') + '/.vimrc')" -->
<!-- ``` -->

## Install on Windows

* Use Powershell
* Copy all and press Enter

```sh
$url = "https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc"
$path = "$env:USERPROFILE\\.vimrc"
(New-Object System.Net.WebClient).DownloadFile($url, $path)
```

* Use cmd.exe

```sh
C:\windows\explorer.exe https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc
```

## Install for Neovim

```sh
mkdir -p ~/.config/nvim/
curl https://raw.githubusercontent.com/joeky888/vimrc/master/.vimrc -o ~/.config/nvim/init.vim
```

### Extra notes

* Don't use `sudo vim`, use `sudoedit` instead
* Auto-complete is disabled inside ssh sessions and docker containers
* Vim built-in clipboard will be used when system clipboard is not available
* When Fbterm and gpm is detected, ttymouse will be set to `xterm` (to use gpm mouse)
* There are some keys one should never map them
    * Ctrl-I = Space in terminal
    * Ctrl-M = Enter in terminal
    * Ctrl-H = Backspace in terminal
    * Ctrl-[ = ESC in terminal
    * Ctrl-/ Vim doesn't support it
    * Ctrl-AnyNumberkey Vim doesn't support it
    * More than three combination keys like Ctrl-Shift-S, terminals don't accept this
* An example setup should like this in terminals
```sh
# Add this to bash_profile, bashrc or zshrc
if [[ "$TERM" == "xterm"* ]]; then
  export TERM=xterm-256color
fi
stty -ixon -ixoff # In order to use Ctrl Q and ctrl S
stty lnext '^-' stop undef start undef -ixon # In order to use Ctrl V
export VISUAL="vim" # For sudoedit command
export EDITOR="$VISUAL" # For sudoedit command
```

### Cheat sheet for Vim regex pattern matching

```conf
^   Begin of line
$   End of line

\s  whitespace character        \S  non-whitespace character
\d  number digit                \D  non-number digit
\x  hex digit	                \X  non-hex digit
\o  octal digit	                \O  non-octal digit
\a  alphabetic character        \A  non-alphabetic character
\w  A word                      \W  Not a word
\l  lowercase character         \L  non-lowercase character
\u  uppercase character         \U  non-uppercase character
\t  Tab character

.   any character
*   matches 0 or more
\+  matches 1 or more
\=  matches 0 or 1

\{n,m}      matches from n to m times
\{n}        matches exactly n times
\{,m}       matches at most m times
\{n,}       matches at least n times

[A-Za-z0-9_]    alphanumeric
[^A-Za-z0-9_]   non-alphanumeric

[\u0000-\u007F]     range of ASCII
[^\u0000-\u007F]    range of non-ASCII (e.g. Full-width characters)

:g/pattern/d        Remove all lines contains a pattern
```

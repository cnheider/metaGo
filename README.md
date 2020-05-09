[![Version](https://vsmarketplacebadge.apphb.com/version/metaseed.metago.svg)](https://marketplace.visualstudio.com/items?itemName=metaseed.metago)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/metaseed.metago.svg)](https://marketplace.visualstudio.com/items?itemName=metaseed.metago)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/metaseed.metago.svg)](https://marketplace.visualstudio.com/items?itemName=metaseed.metago)


[![](https://img.shields.io/badge/TWITTER-%40metaseed-blue.svg?logo=twitter&style=for-the-badge)](https://twitter.com/metaseed)
[![](https://img.shields.io/badge/gitter-join_chat-1dce73.svg?style=for-the-badge&logo=gitter-white)](https://gitter.im/vscode-metago/community)
---
 
 > **Attention: In V3 we changed MetaJump command names and the command default trigger keys**

First of all, Metago is a tool made for myself, it comes from the voice in my heart💖as a programmer.    
Metago tries its best to be the coolest😎 keyboard(mouseless) focused navigation tool in vscode.    
Metago tries to make your keyboard⌨ to you as meaningful as a kitchen knife to a master chef👩‍🍳.    

<br>
Metago as an free tool, currently is maintained and developed by me in my spare time🌙⏳, if you think it's useful to you or even indispensable like some of our users, please support me, just buy me a drink☕ would be a great inspiration for me, which means there is someone really like it. 😊

Give me a  [github⭐](https://github.com/metaseed/metago)
<table align="center" width="68%" border="0">
  <tr>
    <td>
      <a href="https://github.com/sponsors/metasong">
          <img src="https://github.com/metaseed/metaGo/blob/master/donate/githubSponsors.png?raw=true" style="height: 66px;" />
      </a>
    </td>
    <td>
      <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=P9GXHBAAHPBMN&item_name=metago+dev&currency_code=USD&source=url">
          <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif"/>
      </a>
      <br>
    </td>
    <td>
      <a href="https://github.com/metaseed/metaGo/blob/master/donate/index.md">
          <img src="./donate/scan.png" style="height: 66px;"/>
      </a>
    </td>
  </tr>
</table>
<br>
<br>

**quotes from users:**
> [Wicked fast cursor movement/selection for a focus on keyboard usage. This changed how I use VS Code forever. Seriously.](https://spectrum.chat/frontend/general/favourite-vs-code-extensions~9ad33139-aa3a-4f8e-a640-d08ba08736b0)

> [This boosts my performance so much since It’s a trouble for me to use VIM (I’m leftie :( )](https://medium.com/@ColCh/i-found-also-these-plugins-very-helpful-in-my-work-df795a9e929f)

> [probably the best tool for keyboard driven navigation bar none (better than vim), includes bookmarks](https://dev.to/fbnlsr/10-essential-extensions-for-vscode-174i#comment-node-140785)

> [MetaGo is a way to move your cursor to a position quickly and without using your mouse/trackpad.](https://scotch.io/starters/visual-studio-code/metago)

> [Oh, man.. I have a feeling that after that I'm going to feel crippled without it. This is fantastic.](https://www.reddit.com/r/vscode/comments/6wcucw/mouseless_setup/#t1_dm8ka1b)

> and MORE from you... 

**With this new V3 released, we are going to add more features, peek features in dev:**
* hold <kbd>/</kbd> to hide jumper decorators on screen.(Done😉)
* jumper commands for all opened editors, not just the active editor.(Done!)
* support having fold regions.(V3.2 Done!)
* ripple jump support to show less decorators on screen. one target-char for current section(seperated by empty lines), two target-chars for current document editor, three or more for all open editors.(V3.5 Done!)
* improved line-selection extend/shrink command. (V3.6 Done!)
* command to add multiple cursors, and multiple cursor/selection support for all command in metaGo (V3.6 Done!)
* command to change active selection in multiple selections (V3.6 Done!)
* command to select within separator pairs. i.e. '(', ')'; '[',']', '"',''',... (V3.6 Done!)
* and more... at [changelog](https://github.com/metaseed/metaGo/blob/master/CHANGELOG.md)

if you have andy suggestion just open an [issue on github](https://github.com/metaseed/metago/issues) or discuss with us on [Gitter☕](https://gitter.im/vscode-metago/community)

## Features Summary
MetaGo provides fast cursor movement/selection for keyboard focused users:
* [MetaJump](https://github.com/metaseed/metaGo/blob/master/README.md#metajump)
    * [features highlight](https://github.com/metaseed/metaGo/blob/master/README.md#features-highlight)
    * [go to any character on screen with 3(most cases) or 4 times key press](https://github.com/metaseed/metaGo/blob/master/README.md#go-to-any-character-on-screen)
    * [select to any character in the active editor](https://github.com/metaseed/metaGo/blob/master/README.md#select-to-any-character-in-the-active-editor)
    * [add multiple cursors to the active editor](https://github.com/metaseed/metaGo/blob/master/README.md#select-to-any-character-in-the-active-editor)
    * [change active selection in multiple selections](https://github.com/metaseed/metaGo/blob/master/README.md#change-active-selection-in-multiple-selections)

* [MetaSelection](https://github.com/metaseed/metaGo/blob/master/README.md#metaselection)
    * [alternate Selection's active with anchor](https://github.com/metaseed/metaGo/blob/master/README.md#alternate-selections-active-with-anchor)
    * [lines selection](https://github.com/metaseed/metaGo/blob/master/README.md#lines-selection)
    * [surrounding-pair selection](https://github.com/metaseed/metaGo/blob/master/README.md#surrounding-pair-selection)
      * [surrounding-pair selection of common tag](https://github.com/metaseed/metaGo#surrounding-pair-selection-demo)
      * [surrounding-pair selection of html tag](https://github.com/metaseed/metaGo#surrounding-pair-selection-demo-html-tag-pairs)
      * [surrounding-pair changing demo](https://github.com/metaseed/metaGo#surrounding-pair-changing-demo)


* [Navigate between files using bookmarks](https://github.com/metaseed/metaGo/blob/master/README.md#navigate-between-files-using-bookmarks)
* [MetaWord](https://github.com/metaseed/metaGo/blob/master/README.md#metaword)
* [Other features](https://github.com/metaseed/metaGo/blob/master/README.md#other-features)
    * [scroll the active line to the screen top, middle and bottom](https://github.com/metaseed/metaGo/blob/master/README.md#scroll-the-active-line-to-the-screen-top-middle-and-bottom)
    * [moving/select up/down between blank lines](https://github.com/metaseed/metaGo/blob/master/README.md#moveselect-updown-between-blank-lines)
    * [jump to bracket](https://github.com/metaseed/metaGo/blob/master/README.md#jump-to-bracket)

> MetaGo compatible with the vim plugins.

> if you like this tool, and using Windows, you may also be interested in my other tool: [**metaTool**](https://github.com/metatool/metatool). (release soon) 😉    
> with metaTool running with it's metaKeyboard plugin, you just using the 61 keys main keyboard area to type any key you want.
>
> i.e. to jump next blank line in the document, currently the default trigger is <kbd>Alt</kbd>+<kbd>End</kbd>, now you could use<kbd>LAlt</kbd>+<kbd>;</kbd>, because <kbd>LAlt</kbd>+<kbd>;</kbd> is expanded to <kbd>Alt</kbd>+<kbd>end</kbd>

## MetaJump

### features highlight
* code characters are based on priority, the character easier to type has higher priority. i.e. 'k','j', and code characters are configurable.
* code character decorator is encoded with 1 or 2 characters, the code characters around cursor are easier to type.
* only encode characters on viewable screen area, so metaGo is faster.
* support having fold regions
* support jumping to all opened editors
* work with vim plugin

### go to any character on screen
1. type <kbd>Alt</kbd>+<kbd>/</kbd> to tell I want to *go* somewhere. (Trigger)
2. type the characters(stands for the target location) on screen, metaGo will show you some decorator codes(candidate target locations) encoded with characters. (you could hold the <kbd>/</kbd>(configurable) to hide the location decorators, release to show again)
3. you could continue type characters following the target location to narrow down the possible targets range, or type the code decoration characters of one location to *go* to that target location.

> at any time press <kbd>ESC</kbd> to cancel the command; <kbd>Backspace</kbd> to cancel last typed char in target-char-sequence. (<kbd>Backspace</kbd> triggers 'step-cancel')    

> Ripple Support, Less Decorators On Screen: type location-chars to encode locations far from center(cursor location): 
> 1. one target-char for current section(separated by empty lines);
> 1. two target-chars for current doc;
> 1. three or more target-chars for all opened editors;
> 1. for one or two target-chars, one-char-decorators will pass through boundaries(section or document) if possible. (i.e. for one-target-char, one-char-decorators has encoded all possible target locations in the section, then it will continue encodes until all one-char-decorators are used up).

* the <kbd>Alt</kbd>+<kbd>.</kbd> shortcut will trigger the metaGo.gotoAfter command, the cursor will be placed after the target character;    
* the <kbd>Alt</kbd>+<kbd>,</kbd> shortcut will trigger the metaGo.gotoBefore command, the cursor will be placed before the target character;
* the <kbd>Alt</kbd>+<kbd>/</kbd> shortcut will trigger the metaGo.gotoSmart command which intelligently set cursor position after navigation:
    * if the target is at the begin of the word, the cursor will be set before target character, otherwise after it;
    * The 'word' is defined as a group of all alphanumeric or punctuation characters.

> Note: <kbd>Enter</kbd> is also usable as location character, it means the end of line. You could press <kbd>Enter</kbd> any times to trigger the decorator-encoding for the line-end out side of current section(2 times) or document(3 times). (like a ripple)    
> commands that only navigate in the active editor are also provided: metaGo.gotoAfterActive, metaGo.gotoBeforeActive, metaGo.gotoSmartActive, you could assign shortcuts by yourself.


[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

### select to any character in the active editor
1. type <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>/</kbd> to tell I want to *select* to somewhere.
2. type the character(stands for location) on screen, metaGo will show you some codes encoded with character.
3. type the code characters, you will *select* to that location.
4. repeat 1-3 to adjust your current selection.
> at any time press <kbd>ESC</kbd> to cancel, or press <kdb>Backspace</kbd> to do step cancel to re-input last typed character

> support to do multiple selections, 

![MetaGo.MetaJump](images/metago.jump.gif)

### add multiple cursors to the active editor
1. <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>,</kbd> to add another cursor before the target-character
1. <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>.</kbd> to add another cursor after the target-character
1. <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>/</kbd> to add another cursor smartly to the target-character

> <kbd>Ctrl</kbd>+<kbd>u</kbd> to cancel last cursor action.

#### add-multi-cursors demo
we want to modify the three wrongly spelled words, `alt+/` to goto the end of one of them, and `ctrl+alt+/` two times to add two additional cursors to the end of the other two words, `ctrl+backspace` to delete them together, `esc` to escape multi-cursor mode:

![MetaGo.MultiCursor](images/metago.multiCursor.gif)


[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

### change active selection in multiple selections
> the three add-cursor commands would become change-active-selection commands if the target location is inside a selection. It is useful to modify multiple selection ranges, just select one selection as the active one and do extending or shrinking there.
#### change-active-selection demo
we use `alt+shift+/` do selection, then `alt+a` to alternate selection's active with anchor, then `alt+shift+/` to extend selection from another end; then we use `ctrl+alt+/` to add another cursor to code above, `alt+shift+/` to do selection, then `ctrl+alt+/` to make the first selection active, `alt+shift+/` to shrink selection there:
![MetaGo.change-active-selection](images/metago.change-active-selection.gif)

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

## metaSelection

### alternate Selection's active with anchor
* <kbd>Alt</kbd>+<kbd>a</kbd> to alternate the selection's active(cursor flashing) with the anchor.

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

### lines selection
vsCode's default select current line command(`Ctrl+l`) selects current line and puts the cursor at the next line's start position.
we create our own to extend/shrink the selection of the current line:
* <kbd>Ctrl</kbd>+<kbd>l</kbd> to select current line if no selection at cursor, or extend/shrink selections by one line below if there is selection before/after the cursor.
* <kbd>Ctrl</kbd>+<kbd>o</kbd> to extend/shrink selection by one line above if there is selection after/before the cursor.

> extend/shrink selections work at the selection's active end(where cursor flashing), if you want to extend/shrink at the selection's anchor end, use <kbd>Alt</kbd>+<kbd>a</kdb> to alternate selection's anchor with active at first. 

> note: <kbd>Ctrl</kbd>+<kbd>o</kbd> triggers open file by default, and it triggers extend line selection above only when there is selection in active editor.

> if you want to select line up, you should press <kbd>Ctrl</kbd>+<kbd>l</kbd> to select current line and then press <kbd>Ctrl</kbd>+<kbd>o</kbd> to extend line selection above.

by default selectLineUp command is configured as:
```json
{
    "command": "metaGo.selectLineUp",
    "key": "ctrl+o",
    "when": "editorTextFocus && editorHasSelection"
}
```
you could assign a shortcut key not collision with default vscode ones, just remove the `editorHasSelection` condition, so it works even with no selection in editor.

#### lineSelection demo
we use `ctrl+l` to select current line, then `ctrl+l` again to extend current selection below, then `ctrl+o` to shrink current selection above, then `alt+a` to alternate the current selection's active end with anchor end, then `ctrl+o` to extend current selection above, then `ctrl+alt+/` to add another cursor, and `ctrl+l` to select current line, `ctrl+l` again to extend selection below, then `alt+a` to alternate selection's active with anchor, then `ctrl+o` to extend selection above. 


With the two selections, you could then delete or copy...
![MetaGo.LineSelection](images/line-selection.gif)

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

### surrounding-pair selection
commands to select content inside a pair of separators: '(',')'; '[',']'; '{','}';'<','>'; '>', '<'; or any char pair: '''; '"'...
html tag pair is supported via regexp. (i.ed to select content between two html tag pairs: `alt+shift+p t`, `t` means tag).

* `Alt+p` to chang surrounding pairs.
* `Alt+Shift+p` to select content between surrounding pairs.
* `Alt+Ctrl+p` to select both the content and the pairs.

1. <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>: I want to select content between a pair of chars.
2. type the start character of the pair. i.e. '(', '[', '{', '"'... or the specific regex key(i.e. 't' for html/xml tag)

> Note: <kbd>Alt</kbd>+<kbd>Ctrl</kbd>+<kbd>p</kbd> to selection both the content and the pair of separators.

> it supports multiple cursors/selections

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

#### surroundPairs config
below is the default surrounding-pairs config, it support regex: 
```json
"metaGo.surroundPairs": {
    "type": "object",
    "default":[["{","}"],["(",")"],["[","]"],["<",">"],["/<(?!/)(?!!)(?!br[\\s>])(?!area[\\s>])(?!base[\\s>])(?!col[\\s>])(?!command[\\s>])(?!embed[\\s>])(?!hr[\\s>])(?!img[\\s>])(?!input[\\s>])(?!keygen[\\s>])(?!link[\\s>])(?!meta[\\s>])(?!param[\\s>])(?!source[\\s>])(?!track[\\s>])(?!wbr[\\s>])((?:.(?!/>))+?)(?<!/)>/ms", "/<\/(.+?)>/", "t"]]
},

```
> the last one is and regex, it is used for html tag: this array has 3 items: start html tag regex, end html tag regex, trigger key.    
> the default trigger key is the start pair, if start pair is only one char.    
> regex is the content inside '/' and '/', is defined by javascript regex grammar    
> you could config your own regex pairs
> the regex pairs support all regex flags, which means it support multiline tag.
  
> html elements is defined in https://www.w3.org/TR/2011/WD-html-markup-20110405/syntax.html#syntax-elements

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

#### surrounding-pair-selection demo
we use `alt+shift+p (` to select content inside the '(' and ')', then `alt+shift+p {` to extend selection, then `alt+shift+p {` to extend further, then `alt+ctrl+p {` to include then pair('{'and '}') in the selection, then `alt+ctrl+p` to extend the selection further with the pair('{' and '}') included.

![metago.surrounding-pair-selection](images/metago.surrounding-pair-selection.gif)

> note: the hotkey in gif has been changed

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

#### surrounding-pair-selection demo: html tag pairs

we use `alt+shift+p t` to select content inside html tag, `alt+ctrl+p` to select both the content and the tag pairs.
if the cursor is in the start or end tag, `alt+shift+p t` would select both the tag and the content.

![metago.surrounding-pair-selection-html-tag](images/metago.in-selection-html-tag.gif)
> note: hotkeys in gif have been changed

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

#### surrounding-pair changing demo

in this demo, we `alt+p ' "` to change a pair of ' to ", and then goto another place use `alt+p [ (` to change a pair to '[]' to '()'. Then we switch to another html file, where we `alt+p t` to change a surrounding pair of 'h1' to 'h2`, and go to another place, to use `alt+p t` to change another pair of tag from 'h3' to 'h1', note: here is a multi-line start-tag, we use `alt+shift+//` to shrink the selection first and then modify the pair of tag.

![](images/metago.changing-surrounding-pair.gif)

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

## navigate between files using bookmarks

* <kbd>Alt</kbd>+ <kbd>\'</kbd> to toggle a bookmark at the cursor location.
* <kbd>Alt</kbd>+ <kbd>[</kbd> goto previous bookmark.
* <kbd>Alt</kbd>+ <kbd>]</kbd> goto next bookmark.
* <kbd>Alt</kbd>+<kbd>\\</kbd> to list the bookmarks with management menu:
    1. press <kdb>cc</kbd> then <kbd>enter</kbd> to clear all the bookmarks
    2. press <kdb>c</kbd> then <kbd>enter</kbd> to clear all the bookmarks in current document.
    3. press <kdb>n</kbd> then <kbd>enter</kbd> to go to the next bookmark.
    4. press <kdb>p</kbd> then <kbd>enter</kbd> to go to the previous bookmark.

![MetaGo.Center](images/metago.bookmark.gif)

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

## MetaWord
space is very common separator, it would be convenient to use it as cursor anchor when reading/editing document.

### commands to moveCursor/select/delete word seperated by space:
* <kbd>win/cmd</kbd>+<kbd>alt</kbd>+<kbd>left/right</kbd>: to move cursor left/right by one space-word and set cursor at the begin/end of the word.
* <kbd>win/cmd</kbd>+<kbd>alt</kbd>+<kbd>shift</kbd>+<kbd>left/right</kbd>: to select to left/right by one space-word.
* <kbd>win/cmd</kbd>+<kbd>alt</kbd>+<kbd>backspace</kbd>: to delete one space-word left.
* <kbd>win/cmd</kbd>+<kbd>alt</kbd>+<kbd>del</kbd> or <kbd>win/cmd</kbd>+<kbd>alt</kbd>+<kbd>shift</kbd>+<kbd>backspace</kbd>: to delete one space-word right.


[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)
## Other features
### scroll the active line to the screen top, middle and bottom
* <kbd>Alt</kbd>+<kbd>t</kbd> is the default shortcut to scroll current line to screen top.
* <kbd>Alt</kbd>+<kbd>m</kbd> is the default shortcut to scroll current line to screen middle.
* <kbd>Alt</kbd>+<kbd>b</kbd> is the default shortcut to scroll current line to screen bottom.

![MetaGo.Center](images/metago.center.gif)

### move/select up/down between blank lines
* <kbd>Alt</kbd>+<kbd>Home</kbd> to move cursor to the blank line above.
* <kbd>Alt</kbd>+<kbd>End</kbd> to move cursor to the blank line below.
* <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>Home</kbd> to select from the cursor to the blank line above.
* <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>End</kbd> to select from the cursor to the blank line below.
![MetaGo.blankLine](images/metago.blankLine.gif)

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

### jump to bracket
default command always put cursor before the bracket, we want it after start bracket and before end bracket.

default command always search down for the end bracket if the cursor is not at bracket, we want it search up.

* <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>\\</kbd>: jump to the begin bracket that contains the cursor. Press the shortcut *again* jump to the end bracket.

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

### to invoke command from command panel
it's very easy to trigger metago command: type <kbd>F1</kbd>, xx...`. `xx` is a prefix for search metago commands

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

### Other resources that help you understand MetaGo

[Use MetaGo to Quickly Move Around Your Code in VS Code](https://scotch.io/starters/visual-studio-code/metago#toc-conclusion)


[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

## Default Shortcut Settings
To configure the keybinding, press <kbd>ctrl</kbd>+<kbd>k</kbd> <kbd>ctrl</kbd>+<kbd>s</kbd>, or via menu: File -> Preferences -> Keyboard Shortcuts:

> default shortcuts refer: [keybindings section in package.json](https://github.com/metaseed/metaGo/blob/master/package.json#L159)

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

## Extension Settings
To modify the settings, press <kbd>ctrl</kbd>+<kbd>,</kbd>, and search metago...

> default setting refer: [configuration section in package.json](https://github.com/metaseed/metaGo/blob/master/package.json#L321)

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

## Credits

### Contributors:

<a href="https://github.com/metaseed/metago/graphs/contributors">Thank you to all the people who have already contributed to MetaGo!🤞</a>

[*➭Feature Summary⮵*](https://github.com/metaseed/metaGo/blob/master/README.md#features-summary)

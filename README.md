# Linux-command-line (CheatSheet)
command line shortcuts and shell symbol tools cheatsheet


### Linux Information and News Sites

| Url | Site Description |
| ----- | -------- |
| tldp.org | Linux Documentation Project |
| lwn.net | Linux weekly News |
| linuxtoday.com | Linux Today |
| linuxplanet.com | Linuxplanet |
| linux.com | linux.com |


### Movement Commands

| Movement Commands | Operation | 
| ----------------- | --------- |
| CTRL-F, RIGHT-ARROW | Move forward a character. |
CTRL-B, LEFT-ARROW | Move backward a character.
CTRL-A or HOME |  Move to beginning of line.
CTRL-E or END | Move to end of line.
ALT-F | Move forward a word.
ALT-B | Move backward a word.
CTRL-L | Clear screen and place line at top.

### Editing Commands

| Editing | Commands Operation |
| ------- | --------- |
CTRL-D or DEL | Delete character cursor is on.
CTRL-H or BACKSPACE |Delete character before the cursor.
CTRL-K | Cut remainder of line from cursor position.
CTRL-U | Cut from cursor position to beginning of line.
CTRL-W | Cut previous word.
CTRL-C | Cut entire line.
ALT-D | Cut the remainder of a word.
ALT-DEL | Cut from the cursor to the beginning of a word.
CTRL-Y |  Paste previous cut text.
ALT-Y | Paste from set of previously cut text.
CTRL-Y | Paste previous cut text.
CTRL-V | Insert quoted text, used for inserting control or meta (ALT) keys as text, such as CTRL-B for backspace or CTRL-T for tabs.
ALT-T | Transpose current and previous word.
ALT-L | Lowercase current word.
ALT-U | Uppercase current word.
ALT-C | Capitalize current word.
CTRL-SHIFT-_ | Undo previous change.

### Listing Possible auto Completions

Command (CTRL-R for ListingPossible Completions)| Description
| - | - |
TAB | Automatic completion
TAB TAB or ESC |  List possible completions
ALT-/, CTRL-R-/ | Filename completion, normal text for automatic
ALT-$, CTRL-R-$ | Shell variable completion, $ for automatic
ALT-~, CTRL-R-~ | Username completion, ~ for automatic
ALT-@, CTRL-R-@ | Host name completion, @ for automatic
ALT-!, CTRL-R-! | Command name completion, normal text for automatic

### History Commands

History Commands | Description
| - | - |
CTRL-N or DOWN ARROW | Move down to the next event in the history list.
CTRL-P or UP ARROW | Move up to the previous event in the history list.
ALT-< |  Move to the beginning of the history event list.
ALT-> | Move to the end of the history event list.
ALT-N | Forward search, next matching item.
ALT-P | Backward search, previous matching item.
CTRL-S | Forward search history, forward incremental search.
CTRL-R | Reverse search history, reverse incremental search.
fc event-reference | Edits an event with the standard editor and then executes it Options -l List recent history events; same as history command -e editor eventc reference; invokes a specified editor to edit a specific event

|History Event References| Description |
| ------- | ---- |
 !event | num References an event by its event number.
!! | References the previous command.
!characters | References an event beginning with the specified characters.
!?pattern? | References an event containing the specified pattern.
!-event num | References an event with an offset from the first event.
!num-num | References a range of events.



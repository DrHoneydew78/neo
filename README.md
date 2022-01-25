# neo
A pure\* bash script to generate the digital rain from The Matrix in your terminal.

*\*tput is used to get terminal control codes*

# Features
- Different colors, including 256 color support!
- Different glyph sets!
- Control the number and speed of the sparks!
- Control the length of spark tails!
- Sane defaults based on terminal size!

# Usage
Clone the repo, then just run the `neo` script.

For basic usage, run `neo -h`.\
For extended documentation, run `neo -H`.

Press the INT key (typically Ctrl-C) to break out of the program.

## Examples
- `neo cyan`\
Use cyan instead to default green
- `neo -b -D 3 yellow 5`\
5 very fast yellow sparks on the alternate screen buffer
- `neo -y upper -y digits magenta`\
Purple sparks using only upper case and digits
- `neo -s 520 -t 4`\
256-color orange sparks with 256-color gray tails.  (Spoopy!:ghost:)
- `neo -y kata -y symbol -y digits`\
Very Matrix-y glyph selection

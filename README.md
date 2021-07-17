# A simple google translate tui

A simple script that lets you do a quick translator using [google-translate-cli](https://www.npmjs.com/package/google-translate-cli).  The tui comes with a slightly modified version of [with](https://github.com/mchav/with) REPL.

## Usage
`ttui.config` contains the default source and target languages. This file needs to go in `~/.config/` directory.

 - `ttui` : Opens translatore with default languages (`ttui.config)`
 - `ttui -t`: Toggles default source and target languages
 - `ttui -c`: Translate from any language to any language. It will ask for source and target language after the command is executed.

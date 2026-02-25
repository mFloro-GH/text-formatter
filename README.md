# Text Formatter

A lightweight, zero-dependency browser app for quickly formatting lists of text.

**No server. No npm. No build step.** Just open `index.html`.

## Features

- **Two-pane layout** — input on the left, formatted output on the right
- **⇄ Swap button** — move output back to input to chain multiple transforms
- **Copy button** — copies output to clipboard with a "Copied!" confirmation
- **Clear button** — wipes both panes

## Format Options

| Option | Example |
|--------|---------|
| Add comma to each line | `value` → `value,` |
| Single quotes + comma | `value` → `'value',` |
| Double quotes + comma | `value` → `"value",` |
| Convert to UPPERCASE | `hello` → `HELLO` |
| Convert to lowercase | `HELLO` → `hello` |
| Trim & replace spaces with underscores | `  hello world  ` → `hello_world` |

## Usage

1. Open `index.html` in any modern browser
2. Paste your list into the left pane (one item per line)
3. Pick a format from the dropdown
4. Click **Convert**
5. Copy the output or swap it back to the input to chain another transform

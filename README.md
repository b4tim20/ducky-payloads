# DuckyScript samples

A seven-file teaching set for USB HID payload scripting, each file commented to explain *why* a construct
behaves the way it does rather than just *what* it types.

| File | Teaches |
|---|---|
| `01-hello.dd` | `STRING` / `ENTER` / `DELAY` / `DEFAULT_DELAY` |
| `02-launching.dd` | Run dialog vs Start-menu search; `GUI` chords |
| `03-keys-and-modifiers.dd` | modifier chords, arrows, `REPEAT`, `ALTCODE`, save dialogs |
| `04-timing.dd` | why payloads silently truncate, and delay rules of thumb |
| `05-strings.dd` | literal quotes and backslashes; when a word stops being a command |
| `06-ds3-variables.dd` | `DEFINE`, `VAR`, `IF/ELSE` — DuckyScript 3.0 only |
| `07-ds3-functions-loops.dd` | `FUNCTION`, `WHILE` — DuckyScript 3.0 only |

Nothing here is destructive: the demos type into Notepad, Calculator and cmd, and close what they open.
The README documents which constructs are DS 1.0 vs DS 3.0, because the two are not interchangeable —
a DS 3.0 file on a first-generation Ducky fails silently rather than erroring.

## License

MIT — see `LICENSE`.

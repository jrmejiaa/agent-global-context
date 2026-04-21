# File Editing Steering

When the user asks to "open a file", "edit a file", or "make a file editable", you must open it using the `vi` via the terminal. Do not use `open`, `xdg-open`, or any other shell command. Always use:

```sh
vi <file-path>
```

This applies to any file type and any context where the user wants to review or edit a file interactively.

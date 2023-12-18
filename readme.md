

# Important Notes

1. Ensure your project folder is directly located in `C:/`. The project template must be in `FOS_CODES`. Currently, FOS with VSCode is supported only on Windows.

2. If you are using the "FOS with VSCode Changes" version (check `FOS_Readme_2.txt` for confirmation), you do not need to apply these modifications; they are already integrated.

If you want to use the full FOS with QEMU without Eclipse, download it from [fos_cygwin](https://github.com/ahmedhsin/fos_cygwin).

After extracting the contents of `fos_vscode.rar` into the `fos_cygwin` folder:

- For cohorts starting from 2024, make the following modifications:
  - Update the `build.bat` and `tasks.json` files in the `.vscode` folder, replacing any occurrences of "2023" with your current year.
  - Open `fos_cygwin` as a project folder in VS Code.


To run the project:

- Press `Ctrl+Shift+P`, select "Run Tasks," and choose either "Run FOS" or "Run FOS-qemu."

Alternatively, define shortcuts by going to "File" -> "Preferences" -> "Keyboard Shortcuts." Open "Keyboard Shortcuts (json)" and add the following:

For running FOS with Bochs:
```json
{
    "key": "ctrl+f9",
    "command": "workbench.action.tasks.runTask",
    "args": "Run FOS"
}
```

For running FOS with QEMU:
```json
{
    "key": "ctrl+f9",
    "command": "workbench.action.tasks.runTask",
    "args": "Run FOS-qemu"
}
```

Now, you can run the project by pressing `Ctrl+F9`. Customize shortcuts as needed.

Ahmed Mubarak :)
[ahmedhsin@github](https://github.com/ahmedhsin)

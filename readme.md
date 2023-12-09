Important notes your project folder must be directly in `c:/` also project template must be in `FOS_Codes`.
currently only support windows.

After extracting `fos_vscode.rar` inside the `fos_cygwin` folder:

If your cohort is 2024 or later, modify the `build.bat` and `tasks.json` file in the `.vscode` folder to replace any occurrences of "2023" with your current year. Open `fos_cygwin` as a project folder in VS Code.

You can run it by pressing `Ctrl+Shift+P`, then select "Run Tasks" and choose "Run FOS."

Alternatively, define a shortcut by going to "File" -> "Preferences" -> "Keyboard Shortcuts." In the top right corner, click on "Open Keyboard Shortcuts (json)" and add the following:

```json
{
    "key": "ctrl+f9",
    "command": "workbench.action.tasks.runTask",
    "args": "Run FOS"
}
```

Now, you can run the project by pressing `Ctrl+F9`.

Ahmed Mubarak :)
ahmedhsin@github

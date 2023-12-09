after extract fos_vscode.rar inside fos_cygwin folder
open fos_cygwin as a project folder in vscode
#####################################################
you can run by ctrl+shift+p -> run tasks -> run fos
#####################################################
or you can define a shortcut from
File -> Preferences -> Keyboard shortcuts
in top right corner you will find "Open Keyboard shortcuts (json)" click on it 
then add 
{
        "key": "ctrl+f9",
        "command": "workbench.action.tasks.runTask",
        "args": "Run FOS"
}
inside the brackets "[]"

now you can run the project by click on ctrl-f9
#####################################################

Ahmed Mubarak :)
ahmedhsin@github
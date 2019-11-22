# CPSC-386-Taco-Cat-Crossy-Roads
CPSC-386 Crossy Roads Game in Unreal

Group members:

Ryan Chen - ryan.chen@csu.fullerton.edu

Jeffery Lo - jeffylo94@csu.fullerton.edu

Rey Vergara - reyvergara@csu.fullerton.edu


## Dev Notes:
### Setting up Git Plugin in Editor
```The Git Plugin 1.0 (beta) is installed and enabled by default since UE4.7!
On the Toolbar, "Source Control" menu, select "Connect to Source Control"
Select Git from the drop-down.
If you've installed Git the Git Executable should've been auto-detected, otherwise you need to specify the full location of the Git executable on the Field "Git Path" (Git.exe on Windows, may be just Git elsewhere, for example: D:\Progs\Git\bin\git.exe).
If your project is already a Git repository, is should be auto-detected. Else, since UE4.8 you have the option to "Initialize project with Git". By default, this will also create a proper ".gitignore" file. Since UE4.13 you now also have the option to make the initial commit (with the uproject file, and the content of Config/Content/Sources folders)
Note: In UE4.7 you had to intialize yourself your project with 'git init' and create a proper .gitignore file by yourself.
Note: Before UE4.13 you had to make the initial commit with all appropriate files.
Press the Accept Settings button to enable the Git source control provider.
Congratulations! You're ready to start using Git Source Control in editor :)
You now have direct access for submitting & receiving work directly in editor. If you need further information on what each Asset Status Icon means, than to read this step-by-step guide.```

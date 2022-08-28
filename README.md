# Include-header-files-in-vscode-on-macOS
Include &lt;bits/stdc++.h> header files in vscode on macOS
## 1. Create folder
Go to `/usr/local/include/`, and create a new folder named `bits`, then move this file (stdc++.h) into the folder.
<br>
<br>
<img width="684" alt="截圖 2022-08-28 下午10 38 42" src="https://user-images.githubusercontent.com/107752584/187079665-71618a4c-e779-42dc-a9b2-d0c52b5edfeb.png">
<br>
## 2. Add the include path on vscode.
Go to `Setting/Command Palette` on vscode (or press `shift + command + P`), find `C/C++: Edit Configurations (UI)` .
<br>
Add a new include path under the `${workspaceFolder}/**`: `/usr/local/include/`
<br><img width="838" alt="截圖 2022-08-28 下午10 45 09" src="https://user-images.githubusercontent.com/107752584/187079929-1a3dfa11-4c96-4bbe-bcda-9d266fdb0306.png">

# custom_catppuccin
Custom Oh-My-Posh theme from catppuccin, showing Python environment.

1. Download flie `custom_catppuccin.omp.json` to `C:\Users\USER_NAME\AppData\Local\Programs\oh-my-posh\themes`
2. Open powershell
3. Input following commands
```
# Open profile with vscode
code .$profile

# Set theme in profile
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/custom_catppuccin.omp.json" | Invoke-Expression

# Refresh terminal window
. $profile
```

![image](https://github.com/user-attachments/assets/1071f6ef-c27f-469b-abad-53e5ca36fca6)

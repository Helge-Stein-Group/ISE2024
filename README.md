# Industrial Software Engineering 2024

Welcome to the Industrial Software Engineering 2024 course! 
🎉 🥳 🎈 🎊 🍾 🎂

This guide will help you set up GitHub in Visual Studio Code (VS Code) and check off the necessary steps for successful installation and configuration. Additionally, it includes checklists for other essential software installations.

## Setup GitHub in VS Code

### 1. Install Visual Studio Code
Download and install VS Code from [here](https://code.visualstudio.com/).

### 2. Install Git
Download and install Git from [here](https://git-scm.com/downloads).

### 3. Setup GitHub in VS Code

#### Step-by-Step Instructions:

1. **Open VS Code** and go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
2. **Search for "GitHub"** and install the "GitHub Pull Requests and Issues" extension.
3. **Clone a Repository**:
    - Open the Command Palette (`Ctrl+Shift+P`) and type `Git: Clone`.
    - Enter the repository URL and select the local folder where you want to clone the repository.

4. **Create a New Branch**:
    - Open the Command Palette (`Ctrl+Shift+P`) and type `Git: Create Branch`.
    - Enter the branch name and press `Enter`.

5. **Open the Project**:
    - Open the folder containing your cloned repository in VS Code.

6. **Edit and Push Changes**:
    - Make your changes in the files.
    - Save the changes (`Ctrl+S`).
    - Open the Source Control view by clicking on the Source Control icon or by pressing `Ctrl+Shift+G`.
    - Stage the changes by clicking the `+` icon next to the changed files.
    - Enter a commit message and click on the checkmark icon to commit the changes.
    - Click on the ellipsis (`...`) and select `Push`.

### 4. Verification Checklist
- [ ] Installed VS Code
- [ ] Cloned the repository via Git in VS Code
- [ ] Created a new branch
- [ ] Made changes and pushed to the new branch

## Alternative: Git Commands

### Clone a Repository
```bash
git clone https://github.com/Helge-Stein-Group/ISE2024/
```

### Create a New Branch
```bash
git checkout -b <new-branch-name>
```

### Stage Changes
```bash
git add .
```

### Commit Changes
```bash
git commit -m "Your commit message"
```

### Push to Branch
```bash
git push origin <new-branch-name>
```

## Example VS Code Commands

### Open Command Palette
Press `Ctrl+Shift+P` and type the command you need, such as `Git: Clone`.

### Source Control View
Press `Ctrl+Shift+G` to open the Source Control view where you can stage, commit, and push changes.

## Verification Checklist for Software Installations
- [ ] Installed MATLAB
- [ ] Installed Fusion 360
- [ ] Installed DWSIM
- [ ] Installed Microsoft Excel

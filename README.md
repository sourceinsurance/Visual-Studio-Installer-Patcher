# Visual Studio Installer Patcher

## Tasks Included

Visual Studio Installer Patcher - Patches the version for Visual Studio Installer projects (vdproj) and updates all necessary guids.

1. Locates all .vdproj files in a given **Source folder**
2. Updates the **Version** ('##.##.####' as the required format)
3. Updates the product Code and package code to a new GUID

## Install and Run

After installing the [Visual Studio Installer Patcher](https://marketplace.visualstudio.com/items?itemName=RedAppleGroup.VisualStudioInstallerPatcher) extension, open a build and add the 'Visual Studio Installer Patcher' task.

![Task](https://github.com/sourceinsurance/Visual-Studio-Installer-Patcher/blob/master/Images/Task.png?raw=true "Task")

## Task Options

![Task Options](https://github.com/sourceinsurance/Visual-Studio-Installer-Patcher/blob/master/Images/TaskOptions.png?raw=true "Task Options")

1. **Source folder** - The source folder in which to recursivly locate the .vdproj files
2. **Version** - The version to set on the .vdproj files ('##.##.####' as the required format)
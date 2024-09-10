# Git Ignore Templates

This folder contains `.gitignore` templates for these game engines: **Unreal Engine 5 (UE5)**, **Unity**, and **Godot**. These templates will help you prevent unnecessary files from being tracked by Git when working on projects in these engines.

## Instructions

1. **Choose the appropriate template:**
   - For Unreal Engine 5 (UE5): `ue5.gitignore`
   - For Unity: `unity.gitignore`
   - For Godot: `godot.gitignore`

2. **Copy the template to your repository:**
   - Copy the chosen `.gitignore` template file to the base directory of your GitHub repository (the root folder where your project files are located).

3. **Rename the file:**
   - After copying the template file, remove the engine-specific prefix from the filename.
   - For example:
     - Rename `ue5.gitignore` to `.gitignore`
     - Rename `unity.gitignore` to `.gitignore`
     - Rename `godot.gitignore` to `.gitignore`

4. **Commit the changes:**
   - After adding the `.gitignore` file to the base of your repository, commit and push the changes to GitHub. This ensures that unnecessary files and folders specific to your game engine are ignored by Git.

## Additional Information

- The `.gitignore` file is crucial for preventing large or unnecessary files, such as temporary files, build artifacts, and engine-specific cache files, from being added to your version control system.
- If you are using other tools or plugins in your project, you may want to manually update the `.gitignore` file with additional exclusions based on those tools.

Feel free to modify the `.gitignore` templates to better suit the needs of your project!

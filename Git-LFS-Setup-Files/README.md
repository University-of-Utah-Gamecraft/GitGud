# Git Attributes Templates for Git LFS

This folder contains `.gitattributes` templates specifically for **Git Large File Storage (LFS)** for use with popular game engines: **Unreal Engine 5 (UE5)** and **Unity**. These templates ensure that large binary files are properly tracked with Git LFS, avoiding common issues when working with game assets.

## Instructions

1. **Choose the appropriate template:**
   - For Unreal Engine 5 (UE5): `ue5.gitattributes`
   - For Unity: `unity.gitattributes`
   - For Godot: `godot.gitattributes`

2. **Copy the template to your repository:**
   - Copy the `.gitattributes` file to the base directory of your GitHub repository.

3. **Rename the file:**
   - After copying the template, remove the engine-specific prefix from the filename.
   - For example:
     - Rename `ue5.gitattributes` to `.gitattributes`
     - Rename `unity.gitattributes` to `.gitattributes`
     - Rename `godot.gitattributes` to `.gitattributes`

4. **Commit the changes:**
   - After adding the `.gitattributes` file to your repository, commit and push the changes to GitHub. This ensures Git LFS properly handles large binary files used in your game engine.

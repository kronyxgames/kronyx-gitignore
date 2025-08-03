# Kronyx Engines .gitignore

This repository provides the official `.gitignore` template for **Kronyx Engines**, our in-house game engine based on the [Bevy](https://bevyengine.org/) game engine and built primarily with Rust.  

## Purpose

The purpose of this `.gitignore` file is to ensure consistent exclusion of unnecessary files across all Kronyx Engines projects, keeping repositories clean and focused on source files and essential assets.

## What does it cover?

- **Rust-specific build outputs:** such as `/target/` directory and `Cargo.lock` files.  
- **Bevy assets and cache files:** common temporary files related to game assets.  
- **Blender temp and backup files:** to ignore backup files and autosaves generated during asset creation.  
- **IDE and Editor files:** for VSCode, JetBrains IDEs, and other editors to avoid committing user-specific settings.  
- **Operating system files:** like `.DS_Store` on macOS and `Thumbs.db` on Windows.  
- **Common temporary and backup files:** editor swap files, logs, build intermediates, etc.

## How to use

1. **Copy** the `.gitignore` file from this repository into the root directory of your Kronyx Engine project.  
2. **Customize** it if necessary to fit your project's specific requirements.  
3. **Commit** the `.gitignore` file as part of your project's source control.

## Why use this template?

Using a shared `.gitignore` template across all Kronyx Engine projects ensures:

- Cleaner git history and smaller repositories.  
- Reduced risk of accidentally committing build artifacts or sensitive user files.  
- Improved onboarding experience for developers by having a standard setup.

## Contribution

Contributions to improve this `.gitignore` template are welcome! Feel free to submit a pull request if you notice missing patterns or want to optimize it further.

*This `.gitignore` is maintained by Kronyx Games Studios and tailored for the Kronyx Engines ecosystem.*

---  

## Licence 
This Github repo use the MIT licence. See the ´./licence´ file for more information..

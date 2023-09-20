[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/lVQT1YD0)
# UnityTemplate
A Test Template for Unity when using 

GitHub Copilot: Sure, here are the steps to download Git LFS and use an existing GitHub repository with Unity:

**Downloading Git LFS:**

1. Go to the Git LFS website: https://git-lfs.github.com/
2. Click on the "Download" button to download the Git LFS installer for your operating system.
3. Run the installer and follow the instructions to install Git LFS on your computer.

**Using an existing GitHub repository with Unity:**

1. Open Unity and create a new project.
2. Go to the project folder, and open the folder in your native system and open a command prompt (Git Bash, terminal, etc)
3. Download a zip of this template Extract, and copy it into your existing project. 
4. We are going to create and clone the repository using the following command:

   ```
    git init
    git add *
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin <repo url>
    git push -f origin main
  ```

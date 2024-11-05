Alexander Piraino
Demonstration of deploying website to github pages

# My Profile Website

## Purpose of the Repository
This repository hosts the source code for my personal profile website. The goal of this project is to showcase my skills, projects, and professional background in a professional and visually appealing manner.

## Steps to Set Up Git and Push Code

1. **Create a New Repository on GitHub:**
   - Logged in to GitHub.
   - Clicked on the "+" icon and selected "New repository".
   - Named the repository `my-profile-website` and added a brief description.
   - Set the repository to public and clicked "Create repository".

2. **Initialize a Git Repository Locally:**
   - Opened the terminal and navigated to the folder containing my website files.
   - Ran `git init` to initialize a new Git repository.
   - Added all files using `git add .`.
   - Committed the files with `git commit -m "Initial commit"`.

3. **Link to Remote Repository and Push:**
   - Added the remote repository with `git remote add origin https://github.com/Pirainocis233/my-profile-website.git`.
   - Pushed the files using `git push -u origin master`.

## Challenges and Resolutions

1. **Accidental Incorrect Remote URL:**
   - Initially, I accidentally added the wrong remote URL.
   - Resolved it by running `git remote remove origin` followed by `git remote add origin https://github.com/Pirainocis233/my-profile-website.git`.

2. **Understanding Git Commands:**
   - Faced difficulty remembering the sequence of Git commands.
   - Kept a quick reference guide open and practiced commands frequently to build muscle memory.

3. **Dealing with Merge Conflicts:**
   - Encountered merge conflicts when trying to merge branches.
   - Resolved by carefully following Git's merge conflict resolution prompts and editing files to integrate changes.

This repository will be continuously updated as the website evolves and new features are added. Feel free to fork, contribute, or raise issues!

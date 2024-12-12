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


**Challenges and Resolutions**
Configuring the Correct Node.jsVersion:

Initially, I faced difficulties with selecting the right Node.jsversion for my project.

Resolved it by specifying the version explicitly in the deploy.yml file using actions/setup-node@v2.

**Ensuring Build Commands Work in CI Environment:**

Some build commands worked locally but failed in the CI environment.

Fixed this by ensuring all dependencies were correctly specified and the build commands were adjusted for the CI environment.

**Managing Secret Tokens for Deployment:**

Initially, struggled with securely managing GitHub tokens for deployment.

Learned to use GitHub Secrets to securely store and access tokens in the deploy.yml file.

**Dealing with YAML Syntax Errors:**

Encountered syntax errors in the deploy.yml file which caused the workflow to fail.

Resolved by carefully checking indentation and structure, as YAML is sensitive to formatting.

**Triggering the Deployment**
Push to the Master Branch:

Any time you push changes to the master branch, the deployment workflow will automatically trigger.

To do this, make your changes locally, commit them, and push to the master branch:

sh
git add .
git commit -m "Your commit message"
git push origin master
Manual Trigger via GitHub Actions Tab:

**You can also manually trigger the deployment from the GitHub Actions tab on your repository.**

Navigate to the "Actions" tab of your repository.

Find your workflow in the list and click on it.

Click the "Run workflow" button. You might need to specify the branch (in this case, master) and any other required inputs, if applicable.

**Additional Notes**
Ensure that you have all necessary permissions and tokens set up in your repository settings. For example, you need the GITHUB_TOKEN to have the correct permissions for deploying to GitHub Pages.

You can check the status of your workflow runs in the "Actions" tab, where you’ll find detailed logs for debugging if something goes wrong.
This repository will be continuously updated as the website evolves and new features are added. Feel free to fork, contribute, or raise issues!

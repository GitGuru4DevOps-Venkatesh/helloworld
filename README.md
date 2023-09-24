Welcome to DevOps Central Hub!!!(WAR-style) ###
==============================================

This is the simplest possible Java webapp for testing servlet container deployments.  It should work on any container and requires no other dependencies or configuration.

docker-tomcat-satylearning
A basic tutorial on running a web app on Tomcat using Docker - SATYLearning - Subscribe my youtube channel

     https://github.com/efsavage/hello-world-war

########### Steps ###################
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/GitGuru4DevOps-Venkatesh/helloworld-project-1/
* cd helloworld # from your root directory
* mvn clean install # Build using maven command
* $docker build -t helloworld .
* $docker run -p 8082:8080 helloworld
* http://localhost:8082/hello-world-war-1.0.0
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Here's the information formatted as a README file that you can upload to your GitHub repository:

# Repository Cloning and Setup Guide

This guide outlines the step-by-step process for cloning a repository from GitHub to your local machine, creating a new repository on GitHub, copying code from the original repository to your new repository, and pushing the changes to GitHub. This workflow is useful when you want to start with an existing codebase and make modifications in your own repository.

## Cloning the Original Repository from GitHub

### 1. Clone the Original Repository

Start by cloning an existing repository from GitHub to your local machine using the following command:

```bash
git clone https://github.com/original-username/original-repo.git
```

This command creates a local copy of the repository that you can work with.

## Creating a New Repository on GitHub

### 2. Create a New Repository on GitHub

Follow these steps to create a new repository on GitHub:

- Go to [GitHub](https://github.com/) and log in to your account.
- Click on the "+" sign in the top right corner and select "New repository."
- Fill in the repository name, description, and other settings as needed.
- Click the "Create repository" button.

This new repository will be the destination where you want to copy the code from the original repository.

## Cloning the Newly Created Repository

### 3. Clone the Newly Created Repository

After creating the new repository on GitHub, clone it to your local machine just like you did with the original repository. Use the following command:

```bash
git clone https://github.com/your-username/new-repo.git
```

This sets up an empty repository locally.

## Copying Files from the Original Repository

### 4. Open the Newly Created Repository in Git Bash

Navigate to the directory of the newly created repository in Git Bash using the `cd` command.

### 5. Copy Files from the Original Repository

To bring the code from the original repository into the new one, use the `cp` command with the `-r` flag to recursively copy all files and directories from the original repository to the new repository's directory.

## Committing and Pushing Changes

### 6. Return to the Newly Created Repository

Navigate back to the newly created repository's directory in Git Bash.

### 7. Stage, Commit, and Push Changes

Use Git commands to manage changes:

- `git add .` to stage all the changes.
- `git commit -m "message what we changed"` to commit the changes with a descriptive message.
- `git push origin main` (or `git push`) to push the committed changes to the new repository on GitHub. This makes the code available on GitHub.

## Viewing Changes on GitHub

### 8. Check GitHub Repository

After pushing the changes, check your GitHub repository. You will see that all the files you copied from the original repository are now present in your new GitHub repository.

By following these steps, you have successfully cloned code from one repository to another, creating a new repository on GitHub with the copied code. This workflow allows you to maintain your own version of the code while preserving the history and structure of the original repository.

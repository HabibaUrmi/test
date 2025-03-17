# Testing Git Repository

## Steps to Set Up and Test a Git Repository:

1. Create a New Repository

# Create a new directory and navigate into it

$ mkdir my-test-repo
$ cd my-test-repo

# Initialize a new Git repository

$ git init

2. Create a New Repository

# Create a README file

$ echo "# My Test Repository" > README.md

# Stage the file for commit

$ git add README.md

# Commit the file

$ git commit -m "Initial commit"

3. Create a File and Make a Commit

# Create a README file

$ echo "# My Test Repository" > README.md

# Stage the file for commit

$ git add README.md

# Commit the file

$ git commit -m "Initial commit"

4. Create a Remote Repository (GitHub/GitLab)

5. Connect Local Repository to Remote

# Add remote repository (replace URL with your repo's URL)

$ git remote add origin https://github.com/your-username/my-test-repo.git

# Verify remote

$ git remote -v

6. Push Changes to Remote Repository
   $ git push -u origin main

7. Clone an Existing Repository

# Clone a repository

$ git clone https://github.com/your-username/my-test-repo.git

8. Create and Merge a Branch

# Create and switch to a new branch

$ git checkout -b feature-branch

# Make changes, stage, and commit

$ echo "New feature added" >> feature.txt
$ git add feature.txt
$ git commit -m "Added feature file"

# Switch back to main branch

$ git checkout main

# Merge the feature branch

$ git merge feature-branch

# Push the updated main branch

$ git push origin main

# 10. Handling Pull Requests (For Collaboration)

Fork a repository on GitHub/GitLab.

Clone the forked repository.

Create a feature branch and make changes.

Push the feature branch to the forked repository.

Open a Pull Request on GitHub/GitLab.

Wait for approval and merge the changes.

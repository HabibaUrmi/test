Testing Git Repository

Steps to Set Up and Test a Git Repository:

1. Create a New Repository

# Create a new directory and navigate into it

$ mkdir my-test-repo
$ cd my-test-repo

# Initialize a new Git repository

$ git init

2.

# Create a README file

$ echo "# My Test Repository" > README.md

# Stage the file for commit

$ git add README.md

# Commit the file

$ git commit -m "Initial commit"

3. Create a Remote Repository (GitHub/GitLab)

4. Connect Local Repository to Remote

5. Push Changes to Remote Repository

6. Clone an Existing Repository

7. Make Changes and Push Updates

# Edit README.md

$ echo "This is a test repository." >> README.md

# Add and commit changes

$ git add README.md
$ git commit -m "Updated README"

# Push changes

$ git push origin main

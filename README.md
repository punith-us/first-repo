Git & GitHub CLI Commands Documentation
1. git init
Initializes a new Git repository in your current directory.
Use: Start version control for your project.

2. git add .
Stages all changes (new, modified, deleted files) in the current directory for the next commit.
Use: Prepare your changes to be committed.

3. git commit -m "your message"
Records the staged changes to the repository with a descriptive message.
Use: Save a snapshot of your project history.

4. git config --global user.name "your-username"
Sets your Git username globally (for all repositories on your system).
Use: Identify yourself in your commits.

5. git config --global user.email "your-email@example.com"
Sets your Git email globally.
Use: Identify your email in your commits.

6. gh auth login
Starts the GitHub CLI authentication process.
Use: Log in to your GitHub account from the command line.

7. gh repo create
Creates a new repository on GitHub using the GitHub CLI.
Use: Publish your local project to GitHub.

8. git remote add origin https://github.com/your-username/your-repo.git
Adds a remote repository named origin pointing to your GitHub repo.
Use: Link your local repo to the remote GitHub repo.

9. git checkout -b v0.1
Creates and switches to a new branch named v0.1.
Use: Work on a separate line of development.

10. git push -u origin v0.1
Pushes your local v0.1 branch to the remote origin and sets it to track the remote branch.
Use: Upload your branch to GitHub and set up tracking for future pushes/pulls.

# github-repo-instructions
Next time, when you forget the commands, you don't have to spend more than 5 minutes looking for a video on YouTube. You're welcome.

Instructions:

To add your code files from the "codes" folder on your desktop to your GitHub repository named "github-repo-instructions" using Git Bash, you can follow these steps:

1. Open Git Bash: Go to the Start menu, search for "Git Bash," and click on it to open the Git Bash terminal.

2. Change directory: Use the `cd` command to navigate to your "codes" folder on the desktop. For example, if your username is "YourUsername," you can use the following command:
   ```
   cd /c/Users/YourUsername/Desktop/codes
   ```

3. Initialize a Git repository: If the "codes" folder is not already a Git repository, you need to initialize it by running the following command:
   ```
   git init
   ```

4. Add files to the repository: Use the `git add` command to add all the files in the "codes" folder to the repository:
   ```
   git add .
   ```

5. Commit the changes: Create a commit to save the changes you made. Use the `git commit` command with a descriptive message to commit the files. For example:
   ```
   git commit -m "Add my code files"
   ```

6. Connect to your GitHub repository: You need to set up a remote connection to your GitHub repository. If you haven't done so already, create a new repository on GitHub named "github-repo-instructions."

   In the Git Bash terminal, run the following command, replacing `<username>` with your GitHub username and `<repository>` with the repository name:
   ```
   git remote add origin https://github.com/<username>/github-repo-instructions.git
   ```

7. Push the changes to GitHub: Finally, use the `git push` command to upload your code files to the GitHub repository:
   ```
   git push -u origin main
   ```

   Note: If you already have files in the repository and you are pushing for the first time, you might need to use `git push -u origin master` instead of `main`.

After executing these steps, your code files from the "codes" folder on your desktop will be added to your GitHub repository named "github-repo-instructions."

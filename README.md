# deploying-the-server
Great! If the message you want to change is located in the `server.js` file, here's how you can commit and push the change:

1. **Make the Code Change**: Open the `server.js` file in your code editor and find the line where the message is displayed. Change `"Hello Render!"` to `"Hello Johan!"` or your desired text.

2. **Save the File**: After making the change, save the `server.js` file in your code editor.

3. **Terminal or Command Prompt**:
   - Open a terminal or command prompt.
   - Navigate to your project directory using the `cd` command.

4. **Check Status**: Use the command `git status` to see which files have been modified. Make sure `server.js` is listed as a modified file.

5. **Stage Changes**: Stage the modified `server.js` file for commit using the command `git add server.js`.

6. **Commit Changes**: Commit the staged changes with a meaningful message using the command `git commit -m "Updated the message in server.js"`.

7. **Push Changes to GitHub**: If you haven't linked your local repository to a remote repository on GitHub, follow steps 4-6 under "Create GitHub Repository" and "Link Local and Remote Repositories" from my previous response.

8. **Push to GitHub**: After linking your repository, use the command `git push origin master` (or your branch name instead of "master") to push the changes to GitHub.


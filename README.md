# PLPBasicGitAssignment

Task 1: Repository Setup
GitHub Repository Creation:
Log in to your GitHub account.
Create a new repository on GitHub (name it as desired).
Initialize it with a README file.
Task 2: Local Setup
Local Folder Setup:

Create a new folder on your local machine.
Open a terminal or command prompt and navigate to the created folder.
Git Initialization:

Initialize a new Git repository in your local folder.
Connecting to GitHub:

Link your local repository to the GitHub repository created in Task 1.
csharp
Copy code
git remote add origin <repository-url>
Replace <repository-url> with the actual URL of your GitHub repository.
Task 3: Making Changes
Create a File:

Inside your local folder, create a new text file.
Add a simple text message to the file.
Committing Changes:

Stage the changes.
csharp
Copy code
git add <file-name>
Commit the changes.
sql
Copy code
git commit -m "Commit message"
Task 4: Pushing to GitHub
Pushing to GitHub:
Push the committed changes to your GitHub repository.
css
Copy code
git push -u origin main
Task 5: Verification
Verify on GitHub:
Visit your GitHub repository in a web browser and confirm that the file and commit message are visible.
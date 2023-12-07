Do you know some of the commonly used bash commands?
* ls — List directory contents
* echo — Prints text to the terminal window
* touch — Creates a file
* mkdir — Create a directory
* pwd — Print working directory
* cd — Change directory
* mv — Move or rename directory
* rmdir — Remove directory
* chmod — Sets the file permissions flag on a file or folder
* clear — clears out your screen
* exit — closes the terminal
** Git is a type of version control system (VCS) that makes it easier to track changes to files. For example, when you edit a file, git can help you determine exactly what changed, who changed it, etc..
=>Do you know the difference between Git and Github?
* Git is a version control system that lets you manage and keep track of your source code history.
* git used to keep tracking of the history of work.
* git used collabration of the team about their work at the same server.
* GitHub is a hosting service that lets you manage Git repositories. If you have open-source projects that use Git, then * GitHub is designed to store your source code and better manage them.
***************************First time when you create new repositories******************************
echo "# FullStack-Development" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git branch -M main
  git remote add origin https://github.com/bele-adane/FullStack-Development.git
  git push -u origin main

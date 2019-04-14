## Workshop "A Hitchhiker's Guide to Git/ GitHub" by FDU Vancouver's Code4Fun 
### Content

1. Quick intro about what Git and GitHub are
  1. What is Git?
- Git is Version Control System (VCS). What it really means is, Git helps us manage our project files.
- Keep tracks of changes to code
- Synchronizes code between different people => team collaboration
- Test changes to code without losing the original
- Revert back to old versions of code
	(Transcript: This is extremely helpful for software developers or testers etc, basically anyone working with softwares, because when we build a program or a software from scratch, we would want to come back to the original version of the code in order to add more features, improve it, to make it better. Like when we build the foundation of a house, we need to continue bringing more stuffs in order to develop the house that we want. Or just simply experiment, play with code. You can always revert back to your original code whenever you want. That’s what Version Control do, tracking every minute of the changes you made and allowing us to revert back to previous version no matter how many times we make changes.

  2. What is GitHub?
GitHub is a web-based service for version control using Git. A hosting service of Git repositories. (“Repo”) Basically a social networking site for software developers.
Needed for better chance of getting noticed by your future recruiters and employers. (Show off projects, contribute to open source projects, etc)
  (Transcript: Also very helpful for software developers, as with Github we can upload our code in what are called Repositories, and have others look at our project and we can look at theirs as well. We can help each other by identifying errors and even propose changes. 


2. Operations and commands:
- Note: slides in this part should illustrate the process, so that audience can better understand what the command does.
- Option: audience code along
  1. Necessary operations/commands
    1. Setup
      -Fork: Create a copy repository to your Github
      -Clone: Create a local repository in your computer from the online repository
      -Command: git clone
      -Init: initialize a local repository.
          Git init
      -Add remote server:
          Git remote add <name> <server>
      -Note: Use the project to show how to initialize it, and add to a repository in github. Then maybe fork the said project from a different account and clone it to a different folder.

  2. When working on the project
  
      -Stage: choose the file(s) to track the changes for newer version??
          Git add <fileName>
          Git add . (staging all changed filed)
      -Commit: make a new version from staged changes
          Git commit -m “message”
      -Push: update the changes to online repository
          Git push
      -Pull: get the latest code from online repository to local version
      -Branch: different copies of the original project that can be modified separately and then merged the changes to the original project.
          Create new branch: git checkout -b <branchName>
          Go to branch: git checkout <branchName>
      -Conflicts: Happens when several people try to change 1 same line of code -> cannot know which one to choose.
          How git shows a conflict.
          How to fix a conflict.
      -Note: need to create a conflicted file to show how to fix.
      -Pull request: let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.
      `Note: show how to create a PR, how a collaborator can view and accept/decline the PR.
  3. Other helpful commands
      -Git status: see the current status of the branch (how up-to-date it is to master branch, unstaged/staged changed files)
      -Git log: see the commits and their messages.
      -Git remote -v : see all the remote servers.
      -Git diff <sourceBranch> <targetBranch>: see the different between 2 branches

3. Other helpful sources:
(Git cheat sheet for beginners: Print 10 copies)
https://education.github.com/git-cheat-sheet-education.pdf

https://www.khanacademy.org/computing/computer-programming/html-css/web-development-tools/a/hosting-your-website-on-github

https://scitronboy.github.io/code/2018/simple-git-github-tutorial

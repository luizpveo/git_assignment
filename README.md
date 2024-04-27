# Git Assignment - <luizpveo>

a. What is an issue?
GitHub Issues are items you can create in a repository to plan, discuss and track work.
Issues are simple to create and flexible to suit a variety of scenarios. You can use issues to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.

b. What is a pull request?
Pull requests(PR) let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

c. How do I open up a pull request?
To open a pull request:
1 - Push your changes to a branch in your repository.
2 - Go to your repository on GitHub.
3 - Click on the "Pull requests" tab.
4 - Click on the "New pull request" button.
5 - Select the branch with your changes from the "base" dropdown menu.
6 - Select the branch you want to merge your changes into from the "compare" dropdown menu.
7 - Review the changes, add a title and description for your pull request, and then click on the "Create pull request" button.

d. Give me a step by step guide on how to add someone to your repository.
To add someone to your repository:
1 - Ask for the username of the person you're inviting as a collaborator.
2 - On GitHub.com, navigate to the main page of the repository.
3 - Under your repository name, click Settings. If you cannot see the "Settings" tab, select the  dropdown menu, then click Settings.
4 - In the "Access" section of the sidebar, click  Collaborators.
5 - Click Add people.
6 - In the search field, start typing the name of person you want to invite, then click a name in the list of matches.
7 - Click Add NAME to REPOSITORY.
8 - The user will receive an email inviting them to the repository. Once they accept your invitation, they will have collaborator access to your repository.

e. What is the difference between git and GitHub?
Git is a distributed version control system (VCS) that allows users to track changes to files and collaborate with others on projects. GitHub, on the other hand, is a platform built around Git that provides hosting for repositories, collaboration tools (such as issues and pull requests), and other features to facilitate software development and version control.

f. What does git diff do?
The git diff command is used to show the differences between various states of a Git repository.It can be used to see what changes have been made to files before committing them.

g. What is the main branch?
The default branch name in Git is master .It typically represents the latest stable version of the project and serves as the baseline for development. It is commonly used for production-ready code.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, it's generally not recommended to push changes directly to the main branch, especially in collaborative environments or when working on larger projects. To avoid that, it's a good practice to:
1 -  Create a new branch for each feature or bug fix.
2 - Make changes in that branch
3 - Open a pull request (PR) to merge those changes into the main branch after review. 
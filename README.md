# GH_Actions
This Repo is made to lear about GH Actions and Ansible Integration from Pluralsight course

What is Github Actions?

A tool that lets you automate your software development workflows
It allows you to react to some events that can happen in your repository or outside of your repository. And run a workflow in response to that event

What is a Workflow?

Workflow are configurable automated processes that you can set up in your repository in order to perform a certain task.
    - Testing your code
    - Publishing a package
    - Deploying an application
    - Sending a Slack message
    - Opening an issue
A workflow can contain one or more jobs and each job can have multiple steps.


GH_Commands:
`git init` - Initialize a Git Repository (only requires once per project)
`git add <files(s)>` - Stage code changes (for next commit)
`git commit -m "..."` - Create a commit for the staged chnages (with a message)
`git status` - Get the cuurent repository status
`git log` - Output a chronologically ordered list of commits
`git checkout <id>` - Temporarily move back to the commit <id>
`git revert <id>` - Revert the changes of commit <id> (this creates a new commit)
`git reset --hard <id>` - Undo commit(s) up to the commit <id> by deleting the commits


.gitignore file ignores the folders and files mentioned in it during the commit and staging
`git branch <name>` - Creates a new branch
`git branch` - Shows the list of branches and the current active branch
`git branch -D <name>` - Deletes the branch
`git checkout <name>` - Shifts to that branch
`git checkout -b <name>` - Creates and shifts to that branchs
## Initializing a new git repository
- git init

## Staging for commit
- git add

    - staging with file name:

        `git add <file_name> <file_name_2>`

    - staging with folder name:

        `git add <folder_name> <folder_name_2>`

    - staging all changes:

        `git add .`

## Comitting your changes

- git commit

    `git commit -m "<commit_message>"`

## Linking our remote repository to our local repository

- git remote add

    `git remote add <remote_name> <remote_url>`

## Pushing changes to remote repository
- git push
    
    - when there's no corresponding upstream branch

        `git push --set-upstream <remote_name> <branch_name>`

    - for an existing upstream branch

        `git push`
## Working with branches

 - git branch

    - listing all branches

        `git branch`

    - creating a new branch

        `git branch <branch_name>`

    - deleting a branch

        `git branch -D <branch_name>`

    - renaming a branch

        `git branch -M <old_branch_name> <new_branch_name>`
    
    - switching between branches

        `git checkout <branch_name>`

## Git `checkout` command

- git checkout

    - switching between branches

        `git checkout <branch_name>`

    - creating a new branch and switching to it

        `git checkout -b <new_branch_name>`

    - Undoing changes

        `git checkout <file_name>`

        `git checkout <folder_name>`

        `git checkout .`
# Git Lesson

This lesson covers the basics of git for version control.

This lesson is for the first day of the MSSE bootcamp.

To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project you would like to keep.
2. When you have your changes, tell git you are ready to make a checkpoint of the files using `git add filename`
3. Create a checkpoint using `git commit -m "message about what you did"`

## Adding Features
 
Features should be developed on branches. To create and switch to a branch, use the command:

`git switch -c new_branch_name`

To switch to an existing branch, use

`git switch branch_name`
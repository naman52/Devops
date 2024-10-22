
# Command Descriptions

## File System and Shell Commands
- `ls`: Lists the files and directories in the current directory.
- `ls -a`: Lists all files, including hidden ones.
- `ls -apm`: Lists files with their type information and separated by commas.
- `pwd`: Prints the current working directory path.
- `mkdir github_class`: Creates a new directory called `github_class`.
- `cd github_class/`: Changes the directory to `github_class`.
- `vim hello-dosto.txt`: Opens or creates a file called `hello-dosto.txt` for editing using the Vim text editor.
- `cat hello-dosto.txt`: Displays the contents of the file `hello-dosto.txt`.
- `ls -l`: Lists files in long format, showing permissions, ownership, size, and modification time.
- `chmod 774 hello-dosto.txt`: Changes the permissions of `hello-dosto.txt` so that the owner has full access, the group has read/write, and others have read permissions.
- `chmod +x hello-dosto.txt`: Makes the file `hello-dosto.txt` executable.
- `rm hello-dosto.txt`: Removes the file `hello-dosto.txt`.

## Git Commands
- `git --version`: Checks the installed version of Git.
- `git init`: Initializes a new Git repository in the current directory.
- `git branch`: Lists all branches in the repository.
- `git status`: Displays the current status of the working directory and staging area.
- `git add .`: Stages all changes for the next commit.
- `git rm --cached nibba.txt`: Removes `nibba.txt` from the staging area without deleting the file.
- `git commit hello-dosto.txt -m "first commit"`: Commits changes in `hello-dosto.txt` with the message "first commit".
- `git restore hello-dosto.txt`: Restores the file `hello-dosto.txt` to its last committed state.
- `git log --oneline`: Displays the commit history in a condensed, one-line-per-commit format.
- `git checkout -b dev`: Creates and switches to a new branch called `dev`.
- `git checkout master`: Switches to the `master` branch.

## Other Commands
- `history`: Displays the list of commands recently executed.
- `git --help`: Shows the help documentation for Git commands.

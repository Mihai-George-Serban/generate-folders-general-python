# Generate folders

## Story

The company has decided to move to the cloud and you've been tasked to
create the home directories for everyone.  You are given a shell
account for the server.  You need to create the file structure for
everyone using the shell.

## What are you going to learn?

- Using a unix shell
- How to interact with file contents
- How to create files and directories
- How to set permissions
- How to do loops in the shell

## Tasks

1. Create a directory for yourself inside the `home` directory.  Use the shell to navigate the directory structure.  Use the `mkdir` command to create a directory.
    - There is a directory called `home/<your name>`

2. Create a few directories that will be added to everyone's home folder.
    - There is a directory named `home/<your name>/src`
    - There is a directory named `home/<your name>/config`

3. Create the files that will be present in everyone's folder structure.
    - Create a file called `home/<your name/config/profile`.
    - The profile file should set up some variables with the contents:
```
export NAME='<your name>'
export PS1='<your name> \w $ '
```
    - Create a file called `home/<your name>/src/README.md`
    - The source readme file at `home/<your name>/src/README.md` should read:
```markdown
# Source folder

This is the folder where you can keep your projects.
```

4. Now you need to create the home folder for everyone else.  You will find the name of your co-workers in the `names.lst` file.
    - Create the same directory structure for everyone like the one that you created for yourself.
    - Make sure that wherever you used your own name, use your given co-worker's name instead.

## General requirements

None

## Hints

- You can use a combination of `while` and `read` to read your input
  into **variables** line-by-line and do something with it.
- You can assamble files in multiple steps with appending.

## Starting your project

To start your project click [this link](https://journey.code.cool/v2/project/solo/blueprint/generate-folders/general).

## Background materials

- :exclamation: [How to get help for commands](https://learn.code.cool/full-stack/#/../pages/unix/help)
- :exclamation: [Interacting with the system from the shell](https://learn.code.cool/full-stack/#/../pages/unix/interacting-with-the-system)
- :exclamation: [Control structures in the shell](https://www.gnu.org/software/bash/manual/html_node/Compound-Commands.html)

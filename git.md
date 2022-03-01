# Git
[Git](https://git-scm.com/) is "a free and open source distributed version control system".

This means that it is:
1. *free*: does not cost money to use
2. *open source*: source code accessible & developed by the public
3. *distributed*: hosted by mulitple machines
4. *version control system*: a system to manage different versions of a single repositories

Therefore, `git` keeps a record of all changes made to a project such that you can always refer back to a specific version when needed. The *distributed* aspect of `git` allows for multiple contributors to work at the same time.

## Using Git
### Initializing A Repository
1. Download [git](https://git-scm.com/downloads)
    - macOS: might be already downloaded
    - windows: be sure to check the "include GitBash" box as you click thru the installer

2. Open terminal/gitbash
    - masOS: press cmd+space then enter `terminal`

3. `cd` into your project directory
    - Ex. `cd ~/Desktop/projectulterior/new-project`

4. Run `git init`
    - This initializes the git *repository* (project)

5. Run `git status`
    - This outputs the current status of the git repository.

### Adding A New Commit
1. Make changes to the repository
    - Ex. Create a new file by running `echo "Hello World" >> README.md`

2. Run `git status`
    - Notice that `README.md` is now tagged as `modified`

        ```bash
        $ git status
        On branch master

        Changes not staged for commit:
        (use "git add <file>..." to update what will be committed)
        (use "git restore <file>..." to discard changes in working directory)
                modified:   README.md

        no changes added to commit (use "git add" and/or "git commit -a")
        ```

3. Run `git add READMD.md`
    - Notice that `README.md` is now `staged` to be committed (not yet committed)
    
        ```bash
        $ git status
        On branch master

        Changes to be committed:
        (use "git restore --staged <file>..." to unstage)
                modified:   README.md
        ```

4. Run `git commit -m "my first commit"`
    - "my first commit" can be replaced with any message
    - This should return a summary of changes made

5. Run `git log`
    


### Checking Out A Past Commit

### Adding A New Branch

### Merging Branches

### Cloning A Repository

### Pushing/Pulling

### Typical Workflow

### Resources
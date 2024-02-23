# Why is it recommended to use a .gitignore file in a Git repository?

> It's easy for developers to overlook files included in a commit. Sometimes, these overlooked files are benign, such as intermediate build files. However, there's always the risk that someone might inadvertently commit sensitive data.
> 
> For example, someone could commit an API key or private configuration data that a malicious actor could use. One technique to help avoid this risk is to build and maintain `.gitignore` files. These files instruct client tools, such as the command line `git` utility, to ignore paths and patterns when aggregating files for a commit.
> 
> While `.gitignore` files can be useful in helping contributors avoid committing sensitive data, it's just a strong suggestion. Developers can still work around it to add files if they're motivated enough, and sometimes files might slip through because they don't meet the `.gitignore` file configuration.
> 
> Project participants should always be on the lookout for commits that contain data that should be excluded from the repository or its history.
> 
> [GitHub Docs - Ignoring files](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files)

1. [x] to exclude specific files and directories from being committed to version control.
1. [ ] to encrypt sensitive files in the repository.
1. [ ] to hide the repository from public visibility.
1. [ ] to speed up the Git commit process.
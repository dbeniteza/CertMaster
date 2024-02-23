# What can be determined based on the following CODEOWNERS file?

> Changes to files in the folder `docs` need to be reviewed by the user `dani`. A CODEOWNERS file uses a pattern that follows most of the same rules used in gitignore files. The pattern is followed by one or more GitHub usernames or team names using the standard `@username` or `org/team-name` format
> 
> [GitHub Docs - CODEOWNERS syntax](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#codeowners-syntax)

```
*.tf @acme/infrastructure
/docs/ @dani
```

1. [ ] the GitHub user `dani` has code ownership for all individual commits made in the folder
1. [x] docs changesto files in the `docs` folder need to be reviewed by the GitHub user `dani` for a pull request
1. [ ] review assignments are assigned by placing this CODEOWNERS file in the folder within the `owners` repository
1. [ ] changes to files with the extension need to be `tf` reviewed by the `infrastructure` user
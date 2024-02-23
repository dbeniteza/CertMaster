# When using GitHub Actions, what is the proper order of operations when a pull request is opened?

> You can configure a GitHub Actions workf/owto be triggered when an event occurs in your repository, such as a pull request being opened or an issue being created. Your workflow contains one or more jobs which can run in sequential order or in parallel. Each job Will run inside its own virtual machine runner, or inside a container, and has one or more steps that either run a script that you define or run an action, which is a reusable extension that can simplify your workflow.
> 
> [GitHub Docs - Understanding GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)

1. [ ] `Action` &#8594; `Steps` &#8594; `Workflow` &#8594; `Event` &#8594; `Job`
1. [ ] `Workflow` &#8594; `Event` &#8594; `Steps` &#8594; `Job` &#8594; `Action`
1. [x] `Event` &#8594; `Workflow` &#8594; `Job` &#8594; `Steps` &#8594; `Action`
1. [ ] `Action` &#8594; `Steps` &#8594; `Job` &#8594; `Workflow` &#8594; `Event`
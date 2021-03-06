---
date: 2018-07-26T09:25:15Z
title: "jx edit branchpattern"
slug: jx_edit_branchpattern
url: /commands/jx_edit_branchpattern/
---
## jx edit branchpattern

Create a git branch pattern for your team

### Synopsis

Create a git branch pattern for your team. 

The pattern should match all the branches you wish to automate CI/CD on when creating or importing projects. 

For more documentation see: https://jenkins-x.io/developing/import/#branch-patterns

```
jx edit branchpattern [flags]
```

### Examples

```
  # Create a branch pattern for your team
  jx create branch pattern "master|develop|PR-.*"
```

### Options

```
  -b, --batch-mode             In batch mode the command never prompts for user input
      --headless               Enable headless operation if using browser automation
  -h, --help                   help for branchpattern
      --install-dependencies   Should any required dependencies be installed automatically
      --no-brew                Disables the use of brew on MacOS to install or upgrade command line dependencies
      --verbose                Enable verbose logging
```

### SEE ALSO

* [jx edit](/commands/jx_edit/)	 - Edit a resource

###### Auto generated by spf13/cobra on 26-Jul-2018

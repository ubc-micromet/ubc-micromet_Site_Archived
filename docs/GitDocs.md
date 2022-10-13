---
layout: default
title: Git Information
parent: Documentation
# has_children: True
nav_order: 1
---


# Git vs Github ... whats the difference?

Git and Github are incredibly powerful and useful tools.  Unfortunately, they're also pretty confusing and there is a steep learning curve.

**Git** is a version control system.  It lets you manage and track of code, keeping a history of changes each time you make a "commit".

**GitHub** is a cloud-based service that hosts Git repositories.  It makes it easier for to share code and work with collaborators.  


## Whats a Repository?

A repository (or repo) is just a collection of code, files, data, etc. that are being tracked by Git.

## Common Git Commands

**init**: Creates an empty repository

**commit**: Tells git to "save" a repository in its current state.

**clone:**: Tells git to "copy" a repository from a remote location (i.e. a github URL) to a local directory on you computer

**pull:**: Tells git to "download" any changes from a remote repository (i.e. a github URL you previously cloned) to your local copy

**push**: Tells git to "upload" any changes from a local (your computer) copy of a repository to a remote repository (i.e. a github URL you previously cloned)

<p align = 'center'>
	<img src="images/Git_workflow.png" width = 600>
</p>

## Helpful Resources

Nice video tutorial

<iframe width="560" height="315" src="https://www.youtube.com/embed/3fUbBnN_H2c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[These guidelines](https://medium.com/@jonathanmines/the-ultimate-github-collaboration-guide-df816e98fb67) will inform how we approach collaborating on a project.

Add Git Branch Name to Terminal Prompt [(Linux/Mac)](https://gist.github.com/joseluisq/1e96c54fa4e1e5647940)

<p align = 'center'>
	<img src="images/AddBranch_Bash.png" width = 600>
</p>

### I broke something :(

Sometimes you break something and need to know how to fix it.  Pardon the profanity ... but [Oh Shit, Git](https://ohshitgit.com/) is a really helpful resource.


<!-- For next time

- Branch & Merging
- Resotring
- Conflic Resolution 
 -->
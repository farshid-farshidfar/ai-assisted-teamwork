# Work with your team

[Back to the guide](../README.md) · [First project](FIRST-PROJECT.md)

This is a suggested small-team workflow. Try it on a fictional project before deciding whether it improves your team's work.

## A five-person design and advertising example

Imagine a project lead, a copywriter, two designers, and an account manager preparing a bookshop campaign. Keep the brief, copy, review notes, and decision log together in one private repository. Keep artwork in the team's existing design tools and store links to the agreed versions in the repository.

| Person | Example contribution |
| --- | --- |
| Project lead | Sets the brief and assigns work. |
| Copywriter | Proposes headlines and campaign text. |
| Designers | Link to design versions and describe what needs review. |
| Account manager | Records feedback and confirms approval status. |

These are example responsibilities, not required job titles. Agree who can approve each kind of change.

## Set up once

1. The project owner creates a private repository in the intended personal or company account. For company work, use the ownership and access arrangements the company approves.
2. The owner invites colleagues through repository access settings. Each person uses their own GitHub account and accepts the invitation.
3. Each colleague uses VS Code's **Git: Clone** command with the repository address, chooses a local folder, then opens the downloaded project. Cloning gives them a working copy connected to the shared repository; downloading a ZIP does not set up the same Git connection.
4. Each person opens their own copy with their AI assistant. They share files through GitHub; they do not edit the same local folder together.

Official references: [repository access and visibility](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories), [inviting collaborators](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/repository-access-and-collaboration/inviting-collaborators-to-a-personal-repository), and [cloning in VS Code](https://code.visualstudio.com/docs/sourcecontrol/repos-remotes).

Copy and adapt the files in [templates](../templates/) as useful. Use [the example campaign](../examples/bookshop-campaign/README.md) to see a small complete layout.

## Propose one change

A **branch** is a separate line of work. A **pull request** is a proposal to bring that work into the team's agreed version, usually a branch named `main`.

Ask your assistant:

```text
Help me propose a change to the headline in copy.md.
Check for existing local edits and incoming team changes first.
Preserve any unfinished work, then update from the shared main branch.
Create a branch named warmer-headline. Change only the headline I select.
Show me the difference, save a commit, and upload this branch.
Help me open a pull request for a colleague to review, without merging it.
If that branch name already exists, choose a new descriptive name.
```

The assistant can use the available tools or walk you through VS Code and GitHub. You do not need another extension just to review a pull request in the browser. See [GitHub's beginner workflow](https://docs.github.com/en/get-started/using-github/hello-world) and [VS Code branches](https://code.visualstudio.com/docs/sourcecontrol/branches-worktrees).

**Check:** the browser pull request shows the intended source branch, destination branch, and changed files. A colleague reads the difference and comments or approves. The authorised person merges it, meaning the proposal becomes part of the agreed branch. Other team members then pull the updated branch into their copies.

A team agreement to request review does not automatically enforce it in GitHub. If enforcement matters, have the repository owner check the protection features available for that account and repository.

## Avoid overwriting each other's work

Give each task a clear owner. Prefer small changes with meaningful checkpoint messages. Before starting, ask the assistant to check local work and bring in the latest shared version when safe.

If two people change overlapping text, Git may ask for a **conflict** to be resolved. Give both intended versions to the people responsible for the content. The assistant can explain the difference, but should not decide whose meaning to keep. See [troubleshooting](TROUBLESHOOTING.md).

## Decide what belongs here

Use readable text for briefs, notes, copy, and decisions when it suits the team. Git can store other file types, but reviewing and combining text changes is a different experience from reviewing a Photoshop file or a Word document. VS Code is not a replacement for those native editing applications.

For large artwork and video, start with links to the authoritative version in your existing storage. GitHub has file-size limits; Git LFS is a separate large-file workflow with its own limits and costs. Check [GitHub's large-file guidance](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github) before importing media.

Record an approval as a decision with a date, reviewer, and exact version. Merging copy in GitHub does not publish an advertisement or prove that a client approved the design. Keep campaign release steps explicit.

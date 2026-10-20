# Your first project

[Back to the guide](../README.md) · [Setup](../START-HERE.md) · [Next: teamwork](TEAMWORK.md)

Use your `teamwork-practice` folder. The only prerequisite for the first task is an AI extension that can edit a file there.

## Make something useful first

Send this in the extension chat:

```text
Create campaign-brief.md for a fictional local bookshop's weekend event.
Include its goal, audience, three sample headlines, and a short checklist.
Use invented information and label it as a practice example.
Tell me how to open and read the file in VS Code.
Do not install software or upload anything.
```

Open the file. A `.md` file is text with simple formatting, called Markdown. VS Code can show a formatted version: open the Command Palette from the **View** menu and search **Markdown: Open Preview to the Side**.

Then ask: “Make the second headline warmer and less formal. Change only that headline.” Read the result and decide whether you like it. You have now completed a useful task without writing code.

## Install Git when you need checkpoints

Ask your assistant to check whether Git is installed. If it cannot run commands, it can guide you to **Terminal → New Terminal**, where `git --version` should print a version number.

If Git is missing, use the [official Git downloads](https://git-scm.com/downloads/). Choose Windows, macOS, or Linux and have the assistant explain that platform's installation. Restart VS Code afterward if it still cannot find Git. GitHub Desktop is optional; it is not a replacement for Git in VS Code's built-in integration. See [VS Code's Git requirements](https://code.visualstudio.com/docs/sourcecontrol/faq).

Ask the assistant to check the name and email that will appear in your commits. These are authorship details, separate from your GitHub password. For public work, you can use the private commit email supplied in your GitHub email settings; do not invent its format. See [GitHub's email instructions](https://docs.github.com/en/account-and-profile/how-tos/email-preferences/setting-your-commit-email-address).

## Record your first checkpoint

In VS Code's **Source Control** view, initialise a repository for this practice folder. Select only the practice files, review them, stage them, and commit with a message such as `Add practice campaign brief`. Your assistant can perform these steps if it has the right tools.

Here, **stage** means select changes for a checkpoint; **commit** means record the checkpoint locally. **Save** only writes a file to your computer. None of these actions uploads it. See [VS Code's first-commit walkthrough](https://code.visualstudio.com/docs/sourcecontrol/quickstart).

**Check:** inspect the commit in Source Control Graph, or ask the assistant to show the last commit and its file list. Your file should still open normally.

Now ask the assistant to improve the checklist. Inspect the changed lines in Source Control and record a second checkpoint after reviewing the result. You can see what changed between the two versions.

## Put the practice project on GitHub

Create a GitHub account at [GitHub](https://github.com/) if needed, using the official browser flow. Signing into GitHub and signing into your AI provider are separate steps.

Tell your assistant:

```text
Help me publish only this fictional practice project to a NEW PRIVATE
GitHub repository called teamwork-practice. Confirm the folder, account,
file list, and private visibility before uploading. Reuse my existing
authorisation for routine steps. Then help me verify the files on GitHub.
```

The VS Code Command Palette offers **Publish to GitHub**. Sign in, choose the intended account, name the project, and select private visibility. If the destination already exists, ask the assistant to connect to it instead. See [publishing and remotes](https://code.visualstudio.com/docs/sourcecontrol/repos-remotes).

**Check:** open the repository in your browser. Confirm its Private label, the file contents, and the latest commit. A local commit alone is not proof of an upload.

For later updates, **push** uploads your local commits. **Pull** brings other people's changes into your local branch. VS Code's **Sync Changes** combines pulling and pushing; ask the assistant to explain what is incoming and outgoing before using it.

Copy [the progress template](../templates/SETUP-PROGRESS.md) into the practice folder if you want to resume later. Continue to [teamwork](TEAMWORK.md) when you are ready to involve a colleague.

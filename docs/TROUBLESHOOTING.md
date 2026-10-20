# When something does not work

[Back to the guide](../README.md)

Tell your assistant what you expected, what actually happened, and the exact error if there is one. Describe the screen if you do not know its name. Share a screenshot only after checking that it contains no confidential information.

| What happened | Next action |
| --- | --- |
| The assistant cannot open the guide link | Paste [AI-GUIDE.md](../AI-GUIDE.md). Then paste the next guide page it requests. |
| I cannot install software on my work computer | Ask your company's IT contact for the approved route. Continue with planning in an approved chat meanwhile. |
| VS Code asks whether I trust a folder | Check that it is the folder you intended to open. Ask what trust enables before trusting an unfamiliar downloaded project. |
| The extension is installed but I cannot see its chat | Use its official instructions to open the panel. If needed, restart VS Code. Confirm which extension you installed. |
| The extension asks me to pay or add billing | Stop and check the current official account requirements. The guide does not require choosing an API billing route. |
| The assistant writes text in chat but no file appears | Ask which folder it can access and whether file editing is enabled. Confirm the practice folder is open. |
| Git is not found | Check the Git installation, then restart VS Code. Installing an AI extension does not necessarily install Git. |
| Git asks for my name and email | Configure commit authorship with the assistant. Use your GitHub-provided private commit email if desired. This is separate from signing in. |
| GitHub says I do not have permission | Check the signed-in account, repository address, and accepted invitation. Signing in alone does not give access to every repository. |
| My colleague cannot see my new work | Check whether it was committed and pushed, then whether they are viewing or pulling the same branch. |
| Push is rejected | Ask the assistant to inspect the error and local state. Do not repeatedly sync or force-push. |
| I see conflict markers such as `<<<<<<<` | Pause the edit. Ask the assistant to explain both versions, then have the content owners agree the result. |
| A file is too large to upload | Keep it in the team's approved media storage and link to it. Ask about large-file options before changing the repository setup. |
| I want to undo something | Say whether the change was saved, committed, or uploaded. Ask the assistant for the least disruptive recovery and review its effect before erasing work. |

If private information was uploaded, stop sharing the repository and ask the owner for help. Deleting the visible file alone may leave it in earlier history. If a credential was exposed, revoke or rotate it through its provider; changing the file is insufficient.

Official help: [VS Code source-control troubleshooting](https://code.visualstudio.com/docs/sourcecontrol/troubleshooting), [Codex extension](https://learn.chatgpt.com/docs/codex/ide), and [Claude Code extension](https://code.claude.com/docs/en/vs-code).

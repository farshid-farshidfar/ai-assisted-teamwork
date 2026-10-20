# Start here

You need a computer, an internet connection, and permission to install software on it. On a managed work computer, use your company's approved installation and AI account arrangements.

**Shortest route:** your current AI chat → VS Code → one AI extension → a useful document → Git and GitHub.

Each numbered step below is a separate stop. An assistant should walk you through one action at a time, rather than ask you to complete this whole page at once.

## 1. Tell your current assistant what you have

Say which computer you use: Windows, Mac, or Linux. Tell it which AI account you already have and what you want to make. If you do not know your computer type, ask it to help you find out.

You can continue in your browser chat until the VS Code assistant works. No technical vocabulary is required.

## 2. Install VS Code

Use the [official VS Code download page](https://code.visualstudio.com/download). Download **Visual Studio Code** for your computer and open the installer or downloaded application.

- **Windows:** follow the [Windows installation guide](https://code.visualstudio.com/docs/setup/windows). The user installer is a straightforward starting option when permitted by your organisation.
- **Mac:** follow the [Mac installation guide](https://code.visualstudio.com/docs/setup/mac), move the application into Applications, then open it.
- **Linux:** ask your assistant to identify your distribution and follow the matching [official Linux instructions](https://code.visualstudio.com/docs/setup/linux).

**Check:** you can open a window titled Visual Studio Code. You can skip optional customisation for now.

## 3. Open an empty practice folder

Create a new folder called `teamwork-practice` using your computer's usual file browser. In VS Code, choose **File → Open Folder** and select that folder. If asked about trust, this should be the empty folder you just created.

**Check:** its name appears in VS Code's file panel. Ask your assistant if the screen differs.

## 4. Install ONE AI assistant

Use the account you already have access to. You do not need both extensions. An account for a provider's ordinary chat does not by itself guarantee access to its coding assistant.

### Option A: Codex

1. Open [OpenAI's official Codex extension page](https://learn.chatgpt.com/docs/codex/ide) and use its installation link for VS Code. This avoids choosing a similarly named extension.
2. Follow the installation prompts, then open the Codex panel. If needed, search the Command Palette for **Codex: Open Codex Sidebar**.
3. Follow the account sign-in prompts. Ask your assistant to check current access and usage terms before enabling anything that costs money.

Official starting point: [Codex in your editor](https://learn.chatgpt.com/docs/codex/ide). On Windows, use current [Windows guidance](https://learn.chatgpt.com/docs/windows/windows-sandbox) if additional setup is requested; ask for help with that screen rather than installing extra tools in advance.

### Option B: Claude Code

1. Follow [Anthropic's official VS Code extension instructions](https://code.claude.com/docs/en/vs-code). In Extensions, find **Claude Code**, published by **Anthropic**, and install it.
2. Open the Claude Code panel and follow its sign-in prompts.
3. Check account access first: the documentation currently lists paid Claude subscriptions or a Console account. Console usage has different billing from a subscription.

The extension includes the command-line component for its chat panel; a separate command-line installation is unnecessary for this route. See the official page if requirements change.

### Check that the assistant works

In the extension's chat, send:

```text
I am new to VS Code. Tell me which folder you can access. If you can
edit it, create welcome.md with a friendly two-sentence welcome.
If you cannot edit files, explain the next step to enable that here.
Do not install anything or upload anything for this check.
```

**Success:** `welcome.md` appears in your practice folder, and you can open it and read the text. A chat response without a file is not yet a successful file-editing check.

## 5. Hand over the guide

In your new extension chat, paste the starter message from the [README](README.md) with this guide's GitHub address. If it cannot read links, paste [AI-GUIDE.md](AI-GUIDE.md), then the next guide page it requests.

Continue with [your first project](docs/FIRST-PROJECT.md). Git and GitHub come after your first useful AI task. If you get stuck, use [troubleshooting](docs/TROUBLESHOOTING.md).

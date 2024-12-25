# Codee

Meet Codee, an AI assistant.

1. Enter your task and add images to convert mockups into functional apps or fix bugs with screenshots.
2. Codee starts by analyzing your file structure & source code ASTs, running regex searches, and reading relevant files to get up to speed in existing projects. By carefully managing what information is added to context, Codee can provide valuable assistance even for large, complex projects without overwhelming the context window.
3. Once Codee has the information he needs, he can:
    - Create and edit files + monitor linter/compiler errors along the way, letting him proactively fix issues like missing imports and syntax errors on his own.
    - Execute commands directly in your terminal and monitor their output as he works, letting him e.g., react to dev server issues after editing a file.
    - For web development tasks, Codee can launch the site in a headless browser, click, type, scroll, and capture screenshots + console logs, allowing him to fix runtime errors and visual bugs.
4. When a task is completed, Codee will present the result to you with a terminal command like `open -a "Google Chrome" index.html`, which you run with a click of a button.

> [!TIP]
> Use the `CMD/CTRL + Shift + P` shortcut to open the command palette and type "Codee: Open In New Tab" to open the extension as a tab in your editor. This lets you use Codee side-by-side with your file explorer, and see how he changes your workspace more clearly.

### Run Commands in Terminal
Codee can execute commands directly in your terminal and receive the output. This allows him to perform a wide range of tasks, from installing packages and running build scripts to deploying applications, managing databases, and executing tests, all while adapting to your dev environment & toolchain to get the job done right.

For long running processes like dev servers, use the "Proceed While Running" button to let Codee continue in the task while the command runs in the background. As Codee works he’ll be notified of any new terminal output along the way, letting him react to issues that may come up, such as compile-time errors when editing files.

### Create and Edit Files

Codee can create and edit files directly in your editor, presenting you a diff view of the changes. You can edit or revert Codee's changes directly in the diff view editor, or provide feedback in chat until you're satisfied with the result. Codee also monitors linter/compiler errors (missing imports, syntax errors, etc.) so he can fix issues that come up along the way on his own.

All changes made by Codee are recorded in your file's Timeline, providing an easy way to track and revert modifications if needed.

### Tabcomplete
Waiting for a moment.

### Add Context

**`@url`:** Paste in a URL for the extension to fetch and convert to markdown, useful when you want to give Codee the latest docs

**`@problems`:** Add workspace errors and warnings ('Problems' panel) for Codee to fix

**`@file`:** Adds a file's contents so you don't have to waste API requests approving read file (+ type to search files)

**`@folder`:** Adds folder's files all at once to speed up your workflow even more

## License

[Apache 2.0 © 2024](./LICENSE)

# Development Local Machine

## <img src="https://code.visualstudio.com/assets/images/code-stable.png" width="20"/> Visual Studio Code
Visual Studio Code is a source-code editor that can be used with a variety of programming languages, including C, C#, C++, Fortran, Go, Java, JavaScript, Node.js, Python, Rust, and Julia. It is based on the Electron framework, which is used to develop Node.js web applications that run on the Blink layout engine. Visual Studio Code employs the same editor component (codenamed "Monaco") used in Azure DevOps (formerly called "Visual Studio Online" and "Visual Studio Team Services").

Out of the box, Visual Studio Code includes basic support for most common programming languages. This basic support includes syntax highlighting, bracket matching, code folding, and configurable snippets. Visual Studio Code also ships with IntelliSense for JavaScript, TypeScript, JSON, CSS, and HTML, as well as debugging support for Node.js. Support for additional languages can be provided by freely available extensions on the VS Code Marketplace.
### Installation
- Download from here: https://code.visualstudio.com/Download
- Download from here: https://git-scm.com/download/win

### Config
**Configure Git access first:**
On Windows systems, Git looks for the .gitconfig file in the $HOME directory `C:\Users\$USER for most people`. It also still looks for `[path]/etc/gitconfig`, although it’s relative to the MSys root, which is wherever you decide to install Git on your Windows system when you run the installer.
```
cd $HOME
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

[Details here.](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

### Plug-ins

---
#### <img src="https://ms-azuretools.gallerycdn.vsassets.io/extensions/ms-azuretools/vscode-docker/1.28.0/1699886233608/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Docker**](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

Makes it easy to create, manage, and debug containerized applications.

Docker for Visual Studio Code Version Installs Build Status
The Docker extension makes it easy to build, manage, and deploy containerized applications from Visual Studio Code. It also provides one-click debugging of Node.js, Python, and .NET inside a container.

---
#### <img src="https://github.gallerycdn.vsassets.io/extensions/github/vscode-pull-request-github/0.79.2023122012/1703074879007/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**GitHub Pull Requests and Issues**](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

Pull Request and Issue Provider for GitHub

Review and manage your GitHub pull requests and issues directly in VS Code

This extension allows you to review and manage GitHub pull requests and issues in Visual Studio Code. The support includes:

- Authenticating and connecting VS Code to GitHub and GitHub Enterprise.
- Listing and browsing PRs from within VS Code.
- Reviewing PRs from within VS Code with in-editor commenting.
- Validating PRs from within VS Code with easy checkouts.
- Terminal integration that enables UI and CLIs to co-exist.
- Listing and browsing issues from within VS Code.
- Hover cards for "@" mentioned users and for issues.
- Completion suggestions for users and issues.
- A "Start working on issue" action which can create a branch for you.
- Code actions to create issues from "todo" comments.


---
#### <img src="https://yzhang.gallerycdn.vsassets.io/extensions/yzhang/markdown-all-in-one/3.5.1/1679819344347/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Markdown All in One**](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)

*Note:* VS Code has basic Markdown support out-of-the-box (e.g, Markdown preview), please see the official documentation for more information.

---
#### <img src="https://wayou.gallerycdn.vsassets.io/extensions/wayou/vscode-todo-highlight/1.0.5/1635478170130/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**TODO Highlight**](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
Highlight `TODO`, `FIXME` and other annotations within your code.

Sometimes you forget to review the TODOs you've added while coding before you publish the code to production. So I've been wanting an extension for a long time that highlights them and reminds me that there are notes or things not done yet.

---

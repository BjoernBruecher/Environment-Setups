# Development Local Machine

## <img src="https://code.visualstudio.com/assets/images/code-stable.png" width="20"/> Visual Studio Code
Visual Studio Code is a source-code editor that can be used with a variety of programming languages, including C, C#, C++, Fortran, Go, Java, JavaScript, Node.js, Python, Rust, and Julia. It is based on the Electron framework, which is used to develop Node.js web applications that run on the Blink layout engine. Visual Studio Code employs the same editor component (codenamed "Monaco") used in Azure DevOps (formerly called "Visual Studio Online" and "Visual Studio Team Services").

Out of the box, Visual Studio Code includes basic support for most common programming languages. This basic support includes syntax highlighting, bracket matching, code folding, and configurable snippets. Visual Studio Code also ships with IntelliSense for JavaScript, TypeScript, JSON, CSS, and HTML, as well as debugging support for Node.js. Support for additional languages can be provided by freely available extensions on the VS Code Marketplace.
### Installation
- Download location: [Microsoft Visual Studio Code](https://code.visualstudio.com/Download)
- Download location: [git](https://git-scm.com/download/win)

### Config
**Configure Git access first:**
On Windows systems, Git looks for the .gitconfig file in the $HOME directory `C:\Users\$USER for most people`. It also still looks for `[path]/etc/gitconfig`, although it’s relative to the MSys root, which is wherever you decide to install Git on your Windows system when you run the installer.
```
cd $HOME
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

[Details here.](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

### Plug-ins (recommended)

---
#### <img src="https://formulahendry.gallerycdn.vsassets.io/extensions/formulahendry/auto-rename-tag/0.1.10/1644319230173/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Auto Rename Tag**](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
Auto rename paired HTML/XML tag

Automatically rename paired HTML/XML tag, same as Visual Studio IDE does.

---
#### <img src="https://ms-vscode.gallerycdn.vsassets.io/extensions/ms-vscode/cpptools-extension-pack/1.3.0/1662069439952/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**C/C++ Extension Pack**](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)
Popular extensions for C++ development in Visual Studio Code.

This extension pack includes a set of popular extensions for C++ development in Visual Studio Code:
- C/C++
- C/C++ Themes
- CMake
- CMake Tools

---
#### <img src="https://marlon407.gallerycdn.vsassets.io/extensions/marlon407/code-groovy/0.1.2/1544188541182/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**code-groovy**](https://marketplace.visualstudio.com/items?itemName=marlon407.code-groovy)
Groovy support for VSCode

---
#### <img src="https://nicolasvuillamy.gallerycdn.vsassets.io/extensions/nicolasvuillamy/vscode-groovy-lint/3.1.0/1702839340911/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Groovy Lint, Format and Fix**](https://marketplace.visualstudio.com/items?itemName=NicolasVuillamy.vscode-groovy-lint)
Lint, format and auto-fix groovy and Jenkinsfile

Lint (code quality), Format and Auto-fix your groovy files and Jenkinsfile

Visual Studio Code extension embedding npm-groovy-lint, itself embedding CodeNarc

- You can configure the rules by defining a .groovylintrc.json file
- If you use CI, you can integrate Mega-Linter in your workflow, to make sure all your sources (groovy and other) are clean

---
#### <img src="https://streetsidesoftware.gallerycdn.vsassets.io/extensions/streetsidesoftware/code-spell-checker/3.0.1/1694424431035/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Code Spell Checker**](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
Spelling checker for source code

A basic spell checker that works well with code and documents.

The goal of this spell checker is to help catch common spelling errors while keeping the number of false positives low.

---
#### <img src="https://ms-azuretools.gallerycdn.vsassets.io/extensions/ms-azuretools/vscode-docker/1.28.0/1699886233608/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Docker**](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

Makes it easy to create, manage, and debug containerized applications.

Docker for Visual Studio Code Version Installs Build Status
The Docker extension makes it easy to build, manage, and deploy containerized applications from Visual Studio Code. It also provides one-click debugging of Node.js, Python, and .NET inside a container.

---
#### <img src="https://usernamehw.gallerycdn.vsassets.io/extensions/usernamehw/errorlens/3.16.0/1702717792759/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Error Lens**](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
Improve highlighting of errors, warnings and other language diagnostics.

ErrorLens turbo-charges language diagnostic features by making diagnostics stand out more prominently, highlighting the entire line wherever a diagnostic is generated by the language and also prints the message inline.

---
#### <img src="https://dbaeumer.gallerycdn.vsassets.io/extensions/dbaeumer/vscode-eslint/2.4.2/1687441427519/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**ESLint**](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
Integrates ESLint into VS Code. If you are new to ESLint check the documentation.

The extension uses the ESLint library installed in the opened workspace folder. If the folder doesn't provide one the extension looks for a global install version. If you haven't installed ESLint either locally or globally do so by running `npm install eslint` in the workspace folder for a local install or `npm install -g eslint` for a global install.

On new folders you might also need to create an `.eslintrc` configuration file. You can do this by either using the VS Code command `Create ESLint configuration` or by running the `eslint` command in a terminal with `npx eslint --init`.

---
#### <img src="https://mhutchie.gallerycdn.vsassets.io/extensions/mhutchie/git-graph/1.30.0/1617594001998/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Git Graph**](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
View a Git Graph of your repository, and perform Git actions from the graph.

View a Git Graph of your repository, and easily perform Git actions from the graph. Configurable to look the way you want!

---
#### <img src="https://donjayamanne.gallerycdn.vsassets.io/extensions/donjayamanne/githistory/0.6.20/1678008598739/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Git History**](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
View git log, file history, compare branches or commits

Git History, Search and More (including git log):
- View and search git log along with the graph and details.
- View a previous copy of the file.
- View and search the history
  - View the history of one or all branches (git log)
  - View the history of a file
  - View the history of a line in a file (Git Blame).
  - View the history of an author
- Compare:
  - Compare branches
  - Compare commits
  - Compare files across commits
- Miscellaneous features:
  - Github avatars
  - Cherry-picking commits
  - Create Tag
  - Create Branch
  - Reset commit (soft and hard)
  - Reverting commits
  - Create branches from a commits
  - View commit information in a treeview (snapshot of all changes)
  - Merge and rebase
  
Open the file to view the history, and then Press F1 and select/type "Git: View History", "Git: View File History" or "Git: View Line History".

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
#### <img src="https://eamodio.gallerycdn.vsassets.io/extensions/eamodio/gitlens/2024.1.604/1704532048793/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**GitLens — Git supercharged**](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
Supercharge Git within VS Code — Visualize code authorship at a glance via Git blame annotations and CodeLens, seamlessly navigate and explore Git repositories, gain valuable insights via rich visualizations and powerful comparison commands, and so much more

GitLens is a powerful open-source extension for Visual Studio Code.

GitLens supercharges your Git experience in VS Code. Maintaining focus is critical, extra time spent context switching or missing context disrupts your flow. GitLens is the ultimate tool for making Git work for you, designed to improve focus, productivity, and collaboration with a powerful set of tools to help you and your team better understand, write, and review code.

GitLens sets itself apart from other Git tools through its deep level of integration, versatility, and ease of use. GitLens sits directly within your editor, reducing context switching and promoting a more efficient workflow. We know Git is hard and strive to make it as easy as possible while also going beyond the basics with rich visualizations and step-by-step guidance and safety, just to name a few.

---
#### <img src="https://visualstudioexptteam.gallerycdn.vsassets.io/extensions/visualstudioexptteam/vscodeintellicode/1.2.30/1673034060126/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**IntelliCode**](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
AI-assisted development

The Visual Studio IntelliCode extension provides AI-assisted development features for Python, TypeScript/JavaScript and Java developers in Visual Studio Code, with insights based on understanding your code context combined with machine learning.

You'll need Visual Studio Code October 2018 Release 1.29.1 or later to use this extension. For each supported language, please refer to the "Getting Started" section below to understand any other pre-requisites you'll need to install and configure to get IntelliCode completions.

---
#### <img src="https://idered.gallerycdn.vsassets.io/extensions/idered/npm/1.7.4/1689105633306/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**NPM**](https://marketplace.visualstudio.com/items?itemName=idered.npm)
Manage npm dependencies from sidebar. Supports npm, yarn, pnpm, bun.

Manage and analyze your Node.js dependencies.

---
#### <img src="https://yzhang.gallerycdn.vsassets.io/extensions/yzhang/markdown-all-in-one/3.5.1/1679819344347/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Markdown All in One**](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)

*Note:* VS Code has basic Markdown support out-of-the-box (e.g, Markdown preview), please see the official documentation for more information.

---
#### <img src="https://esbenp.gallerycdn.vsassets.io/extensions/esbenp/prettier-vscode/10.1.0/1690819498575/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Prettier - Code formatter**](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
Prettier is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

JavaScript · TypeScript · Flow · JSX · JSON
CSS · SCSS · Less
HTML · Vue · Angular HANDLEBARS · Ember · Glimmer
GraphQL · Markdown · YAML

---
#### <img src="https://wayou.gallerycdn.vsassets.io/extensions/wayou/vscode-todo-highlight/1.0.5/1635478170130/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**TODO Highlight**](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
Highlight `TODO`, `FIXME` and other annotations within your code.

Sometimes you forget to review the TODOs you've added while coding before you publish the code to production. So I've been wanting an extension for a long time that highlights them and reminds me that there are notes or things not done yet.

---
#### <img src="https://shardulm94.gallerycdn.vsassets.io/extensions/shardulm94/trailing-spaces/0.4.1/1657508114419/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**Trailing Spaces**](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)
Highlight trailing spaces and delete them in a flash!

A VS Code extension that allows you to…

highlight trailing spaces and delete them in a flash!

This extension is a port of the popular Sublime Text plugin Trailing Spaces.

---
#### <img src="https://redhat.gallerycdn.vsassets.io/extensions/redhat/vscode-yaml/1.14.0/1689778154971/Microsoft.VisualStudio.Services.Icons.Default" width="20"/> [**YAML**](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
YAML Language Support by Red Hat, with built-in Kubernetes syntax support

Provides comprehensive YAML Language support to Visual Studio Code, via the yaml-language-server, with built-in Kubernetes syntax support.

---

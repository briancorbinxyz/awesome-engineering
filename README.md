# Awesome Engineering

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Personally curated and opinionated collection of awesome engineering, coding & setup links & useful some snippets

## Contents

- [AI](#ai)
- [Coding & CLI Fonts](#codingcli-fonts)
- [EduTech](#edutech)
- [IDEs](#ides)
- [Documentation](#documentation)
- [Langauages](#languages)
- [Terminal](#terminal)
- [Terminal Tools](#terminal-tools)
- [UX](#ux)
- [Web Tools](#web-tools)
- [Workflow Automation](workflow-automation)

---

### AI

- Chats:
  - [OpenAI](https://chat.openai.com/) AI Chatbot
  - [Claude](https://claude.ai/chats) AI Chatbot
- CLIs:
  - [node-chatgpt-api](https://github.com/waylaidwanderer/node-chatgpt-api) Interact with ChatGPT on CLI or over REST
- LLMs:
  - [Ollama](https://github.com/ollama/ollama) Run large language models locally (https://ollama.com/download)

### Coding/CLI Fonts
- [Operator Mono](https://github.com/keyding/Operator-Mono) Break from the norm, more interesting coding font (PAID)
- [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) Nice clear coding font
- [Fira Code](https://github.com/tonsky/FiraCode) Font with nice ligatures that makes your code more compact and readable

### Culture
- [The Hot Co.](https://shop.thehot.co/) Awesome coding journals / notebooks and more (shameless plug!)

### Documentation
- [devdocs.io](https://devdocs.io) — API documentation for all popular programming languages and frameworks. Includes instant search and works offline too.

### Terminal

- [Cmder](https://cmder.app) Console emulator for Windows
- [Hyper](https://hyper.is/): Cross platform terminal replacement with plugins
  - Plugins ([Awesome](https://github.com/bnb/awesome-hyper?tab=readme-ov-file)):
    - [hyperpower](https://www.npmjs.com/package/hyperpower) completely unecessary but fun cursor (Run: ```wow``` for extra craziness)
      ```
      hyper i hyperpower
      ```

    - [hyper-pane](https://www.npmjs.com/package/hyper-pane) Pane navigation
      ```
      hyper i hyper-pane
      ```

    - [hyper-search](https://www.npmjs.com/package/hyper-search) Search the hyper terminal (Cmd/Ctrl-F)
      ```
      hyper i hyper-search
      ```

    - [hyper-tabs](https://www.npmjs.com/package/hyperterm-tabs): Let's you rearrange tabs by drag & dropping them.
      ```
      hyper i hyperterm-tabs
      ```

    - [hyper-capture](https://www.npmjs.com/package/hyper-capture): Capture the output of hyper to a video file (Run: ```togglecapture``` to start)
      ```
      hyper i hyper-capture
      ```
    
  - Awesome:
    - [Awesome Hyper](https://github.com/bnb/awesome-hyper): Another curated collection of hyper links

  - Snippets:

    - Fix the hyper command on OSX (if you're using ZSH): ```zsh: command not found: hyper```
       ```
       sudo ln -s "/Applications/Hyper.app/Contents/Resources/bin/hyper" /usr/local/bin/hyper
       ```

### Terminal Tools

- [httpie](https://httpie.org/) Alternative for cURL, wget
- [jq](https://github.com/jqlang/jq) Command-line JSON processor 
- [yq](https://github.com/kislyuk/yq) Command-line YAML processor (Also installs xq for XML and tomlq for TOML)
- [fkill]() Cross-platform process killer
- [thef*ck](https://github.com/nvbn/thefuck) Unfortunately named but super-useful for running the command you intended that just failed 

### UX

- [Excalidraw](https://github.com/excalidraw/excalidraw) Hand-drawn style sketching app/whiteboarding with collaboration
- [Balsamiq](https://balsamiq.com/) Wireframing tool (PAID)
- [Axure](https://www.axure.com/) UI/UX design tool (PAID)
- [Figma](https://www.figma.com/) UI/UX design tool (PAID)

### CIT

- Jenkins:
  - Plugins:
    - [BlueOcean](https://github.com/jenkinsci/blueocean-plugin) (https://plugins.jenkins.io/blueocean) Blue Ocean is a replacement interface for Jenkins that provides a modern and intuitive interface for navigating and interacting with Jenkins.

### Languages

#### HTML/CSS

- Frameworks:
  - [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss) (https://tailwindcss.com/) It's CSS but much faster to write!
    ```
    npm install -D tailwindcss
    npx tailwindcss init
    ```
  - [UI Kit](https://github.com/uikit/uikit) (https://getuikit.com/docs/slideshow) Clean and simple web UI framework
    ```
    npm i uikit
    ```
  - [Bootstrap](https://github.com/twbs/bootstrap) (https://getbootstrap.com/) World's most popular grid system framework, pretty easy to use (v 5 ditched JQuery)
    ```
    npm i bootstrap
    ```
- In-browser UI editor: https://www.codeply.com

#### JavaScript/Typescript:
	
- Repositories:
  - [npm](https://www.npmjs.com/): The package manager for JavaScript

- UI:
  - [React](https://github.com/facebook/react) (https://reactjs.org/) A JavaScript library for building user interfaces
- CLI:
  - [Chalk](https://github.com/chalk/chalk) (https://www.npmjs.com/package/chalk) Terminal string styling done right
	
#### Java
	
- Testing:
  - [assertj](https://github.com/joel-costigliola/assertj-core) (https://assertj.github.io/doc/) Assertion library for Java
  - [hamcrest](https://github.com/hamcrest/JavaHamcrest) (https://hamcrest.org/JavaHamcrest/) Matcher library for Java
  - [TestNG](https://github.com/cbeust/testng) (https://testng.org/doc/) Testing framework for Java (preferred)
  - [JUnit](https://github.com/junit-team/junit5) (https://junit.org/junit5/) Testing framework for Java
  - [Cucumber](https://github.com/cucumber/cucumber-jvm) (https://cucumber.io/) Behavior-Driven Development for Java
  - [Selenium](https://github.com/SeleniumHQ/selenium) (https://www.selenium.dev/) Browser automation framework ideal for testing
- Reactive: (https://www.reactivemanifesto.org/)
  - [RxJava](https://github.com/ReactiveX/RxJava) (https://github.com/ReactiveX/RxJava/wiki) Reactive Extensions for the JVM
	
#### Python

- Wheel
- Virtualenv
- Pipenv
- Poetry
- Autopep8
- Pylint
- Black
- Pandas
- Scikit-Learn
- Taichi
- Requests
	
### EduTech

 - [IntelliJ EduTools Plugin](https://plugins.jetbrains.com/plugin/10081-jetbrains-academy):
   - [Educator Start Guide](https://www.jetbrains.com/help/education/educator-start-guide.html): NB: JPGs, MP4s etc. work as well within IntelliJ 
 - [VideoScribe](https://www.videoscribe.co/en/) Create video diagrams / animated explainer videos for tutorials. 
- [carbon.now.sh](https://carbon.now.sh/) Simulated/Generated CLI / Code Screenshots (online)
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) Generated Code/Command line screenshots from the terminal
 - High quality animated screencasts:
   - GIFs: [asciinema](https://github.com/asciinema/asciinema) (https://asciinema.org/) free and open source solution for recording terminal sessions and sharing them
   - SVG: [svg-term-cli](https://github.com/marionebl/svg-term-cli) Share terminal sessions as razor-sharp animated SVG

### IDEs

#### IntelliJ / IDEA IDE

- Plugins:
  - [GREP Console](https://plugins.jetbrains.com/plugin/7125-grep-console) GREP the console in IntelliJ
  - [GitToolBox](https://plugins.jetbrains.com/plugin/7499-gittoolbox) Git integration for IntelliJ (e.g. Git Graph)
  - [Vim](https://plugins.jetbrains.com/plugin/164-ideavim) Vim emulation plugin for IntelliJ
- Themes:
  - [PaleNight (Material Theme)](https://plugins.jetbrains.com/plugin/8006-material-theme-ui) Material theme (esp. Palenight) is generally awesome
	
#### Vim

- [NeoVim](https://github.com/neovim/neovim) (https://neovim.io/) Vim-fork focused on extensibility and usability
  ```
  brew install neovim
  ```

#### Visual Studio
- Themes:
  - [PaleNight (Material Theme)](https://marketplace.visualstudio.com/items?itemName=gjactat.palenightvs2017) Material theme (esp. Palenight) is generally awesome

#### VS Code

- [VS Code](https://github.com/microsoft/vscode) (https://code.visualstudio.com/) Code editor redefined and optimized for building and debugging modern applications
- Plugins:
  - Code Screenshots: https://github.com/octref/polacode
  - GitHub Pull Requests and Issues: https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github
        § Atlassian Equivalent: https://marketplace.visualstudio.com/items?itemName=Atlassian.atlascode / https://support.atlassian.com/bitbucket-cloud/docs/jira-issues-in-vs-code/
  - Extensions Review - Awesome VSCode: https://viatsko.github.io/awesome-vscode/
  - [Java (Bundle)](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) Java Support
  - Vim: https://marketplace.visualstudio.com/items?itemName=vscodevim.vim
  - C++: https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools
  - C#: https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp
  - Python: https://marketplace.visualstudio.com/items?itemName=ms-python.python
  - Icons: https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons
  - Code Screenshotting: https://marketplace.visualstudio.com/items?itemName=pnp.polacode
  - Gradle: https://marketplace.visualstudio.com/items?itemName=naco-siren.gradle-language&source=post_page-----8de7d2b59902----------------------
        § Gradle for Java: 
  - Kotlin: https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin
  - GitLens: https://gitlens.amod.io/
  - SonarLint: https://www.sonarlint.org/vscode/
  - Instant Markdown: https://marketplace.visualstudio.com/items?itemName=dbankier.vscode-instant-markdown
  - Live Sharing/Collaboration: https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack
  - List of Extensions: https://x-team.com/blog/best-vscode-extensions/
        § Peacock: great for differentiating your coding windows: https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock
  - https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek
  - Hashicorp Terraform Plugin

- AI Assistants:
  - [Cody](https://marketplace.visualstudio.com/items?itemName=sourcegraph.cody-ai) AI code assistant by the sourcegraph folks with a free tier, even has natural language code search
  - [Codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium) 'Free Forver' code assistant - intelligently generates code as you type comments or use chat

- Themes:
  - [PaleNight (Material Theme)](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) Material theme (esp. Palenight) is generally awesome
  - [Fairyfloss](https://marketplace.visualstudio.com/items?itemName=nopjmp.fairyfloss) About as far from dark mode themes as I am willing to go. Cozy much?

### Icons and Images
- https://www.flaticon.com

### Screen Recorders / Screen Caster
- [ScreenToGif](https://github.com/NickeManarin/ScreenToGif) (https://www.screentogif.com/) Free screen recording tool for Windows
- [SnagIt](https://www.techsmith.com/screen-capture.html) Fully-featured screen capture tool (PAID)

### Comparison
- [Beyond Compare](https://www.scootersoftware.com/download.php) Best file comparison tool (PAID)

### Operating Systems

#### Arch Linux
- [Pacman](https://gitlab.archlinux.org/archlinux/packaging/packages/pacman) (https://wiki.archlinux.org/index.php/Pacman) Package manager for Arch Linux

#### OSX
- [Homebrew](https://github.com/Homebrew/brew) (https://brew.sh/) Package manager for OSX

#### Windows
- [choco](https://github.com/chocolatey/choco) (https://chocolatey.org/install) Windows package manager

### Interesting/Unsorted:
- https://www.barbarianmeetscoding.com/blog/2019/02/08/boost-your-coding-fu-with-vscode-and-vim
- https://www.robertcooper.me/elegant-development-experience-with-zsh-and-hyper-terminal
- https://www.maketecheasier.com/install-zsh-and-oh-my-zsh-windows10/
- https://www.labnol.org/internet/useful-tools-for-programmers/29227/- https://medium.com/@ssharizal/hyper-js-oh-my-zsh-as-ubuntu-on-windows-wsl-terminal-8bf577cdbd97
- https://github.com/athityakumar/colorls
	
### Web Tools

- [Postman](https://www.postman.com/) REST Client and API Platform
- [Postman Interceptor](https://chromewebstore.google.com/detail/postman-interceptor/aicmkgpgakddgnaphhhpliifpcfhicfo) Capture requests from any website and send them to Postman Client

### Workflow Automation

- [n8n](https://n8n.io/) Workflow Automation Tool (self-host)
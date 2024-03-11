# Awesome Engineering

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Personally curated and opinionated collection of awesome engineering, coding & setup links & useful some snippets for the productive 10X engineer.

## Contents

- [AI](#ai)
- [Books](#books)
- [Coding & CLI Fonts](#codingcli-fonts)
- [Comparison](#comparison)
- [Culture](#culture)
- [EduTech](#edutech)
- [IDEs](#ides)
- [Documentation](#documentation)
- [Languages](#languages)
- [Operating Systems](#operating-systems)
- [Scaffolding](#scaffolding)
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
- Frameworks:
  - [Langchain](https://github.com/langchain-ai/langchain) Language model training framework

### Coding/CLI Fonts

- Favorites:
  - [Operator Mono](https://github.com/keyding/Operator-Mono) Break from the norm, more interesting coding font (PAID)
  - [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) Nice clear coding font
  - [Fira Code](https://github.com/tonsky/FiraCode) Font with nice ligatures that makes your code more compact and readable
  - [Hack](https://github.com/source-foundry/Hack) Font designed for source code
- Lists:
  - [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) (https://www.nerdfonts.com) All the best fonts brought together in one place pre-patched for terminal with icons
  - [Programming Fonts](https://github.com/braver/programmingfonts) (https://programmingfonts.org) All the best fonts brought together in one place and previewable

### Comparison
- [Beyond Compare](https://www.scootersoftware.com/download.php) Best file comparison tool (PAID)

### Culture
- [The Hot Co.](https://shop.thehot.co/) Awesome coding journals / notebooks and more (shameless plug!)

### Documentation
- [devdocs.io](https://devdocs.io) — API documentation for all popular programming languages and frameworks. Includes instant search and works offline too.

### Scaffoling

- [Cookiecutter](https://github.com/cookiecutter/cookiecutter) (https://cookiecutter.readthedocs.io/en/latest/) A command-line utility that creates projects from cookiecutters (project templates)
- [Yeoman](https://github.com/yeoman/yo) (https://yeoman.io) A set of tools for automating the creation of projects, templates, boilerplates, modules and applications.

### Terminal

- [Cmder](https://cmder.app) Console emulator for Windows
- [Hyper](https://hyper.is/) Cross platform terminal replacement with plugins
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
- [Warp](https://www.warp.dev/) The terminal 'reimagined' - a real game changer for the age old terminal - terminal on steriods!

### Terminal Tools

- [httpie](https://httpie.org/) Alternative for cURL, wget
- [jq](https://github.com/jqlang/jq) Command-line JSON processor 
- [yq](https://github.com/kislyuk/yq) Command-line YAML processor (Also installs xq for XML and tomlq for TOML)
- [fkill]() Cross-platform process killer
- [thef*ck](https://github.com/nvbn/thefuck) Unfortunately named but super-useful for running the command you intended that just failed 
- [colorls](https://github.com/athityakumar/colorls) Nice ls with colorful output
- [lsd](https://github.com/lsd-rs/lsd) A Rust implementation of ls inspired by colorls

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

- [Awesome HTML5](https://github.com/diegocard/awesome-html5)
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
	
- [Awesome Javascript](https://github.com/sorrycc/awesome-javascript)
- [NativeScript](https://github.com/NativeScript/NativeScript) (https://nativescript.org/) Build truly native iOS, Android and Progressive Web Apps with JavaScript
- Repositories:
  - [npm](https://www.npmjs.com/): The package manager for JavaScript

- Testing:
  - [Cypress](https://github.com/cypress-io/cypress) (https://www.cypress.io/) Fast, easy and reliable testing for anything that runs in a browser.
- UI:
  - [React](https://github.com/facebook/react) (https://reactjs.org/) A JavaScript library for building user interfaces
  - [Svelte](https://github.com/sveltejs/svelte) (https://svelte.dev/) Cybernetically enhanced web apps (less verbosity than React - uses compiler)
- CLI:
  - [Chalk](https://github.com/chalk/chalk) (https://www.npmjs.com/package/chalk) Terminal string styling done right
	
#### Java
	
- [Awesome Java](https://github.com/akullpp/awesome-java)
- [Guava](https://github.com/google/guava) (https://github.com/google/guava) Google's core Java libraries (especially useful pre-JDK17)
- [Spring Boot](https://github.com/spring-projects/spring-boot) (https://spring.io/projects/spring-boot) Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run"
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

- [Awesome Python](https://github.com/vinta/awesome-python)
- [Wheel](https://github.com/pypa/wheel) (https://pythonwheels.com/) Build Python packages that work on Linux, Windows, and Mac
- [Virtualenv](https://github.com/pypa/virtualenv) (https://virtualenv.pypa.io/en/latest/) Virtual Python Environment builder
- [Pipenv](https://github.com/pypa/pipenv) (https://pipenv.pypa.io/en/latest/) Python Development Workflow for Humans
- [Poetry](https://github.com/python-poetry/poetry) (https://python-poetry.org/) Python dependency management and packaging made easy
- [Pip](https://github.com/pypa/pip) (https://pip.pypa.io/en/stable/) Package manager for Python
- [Autopep8](https://github.com/hhatto/autopep8) (https://pypi.org/project/autopep8/) AutoPEP8 is a tool that automatically formats Python code to conform to the PEP 8 style guide
- [Pylint](https://github.com/PyCQA/pylint) (https://www.pylint.org/) Python code static checker
- [Black](https://github.com/psf/black) (https://black.readthedocs.io/en/stable/) The uncompromising Python code formatter
- [Pandas](https://github.com/pandas-dev/pandas) (https://pandas.pydata.org/) Data analysis and manipulation tool
- [Scikit-learn](https://github.com/scikit-learn/scikit-learn) (https://scikit-learn.org/stable/) Machine learning library for Python
- [PyTorch](https://github.com/pytorch/pytorch) (https://pytorch.org/) an open source machine learning (ML) framework based on the Python for Deep Learning 
- [Taichi](https://github.com/taichi-dev/taichi) (https://docs.taichi.graphics/) Python-based scientific computing uses JIT compilation to offload the Python source code to native GPU or CPU instructions for performance
- [Requests](https://github.com/psf/requests) (https://requests.readthedocs.io/en/master/) Python HTTP Requests for Humans
- [Cookiecutter](https://github.com/cookiecutter/cookiecutter) (https://cookiecutter.readthedocs.io/en/latest/) A command-line utility that creates projects from cookiecutters (project templates)
- Homebrew / Niche Libraries:
  - [Anki CozmoSDK](https://github.com/anki/cozmo-python-sdk) (https://data.bit-bots.de/cozmo_sdk_doc/cozmosdk.anki.com/docs/index.html) Little robot - Cozmo SDK for python
  - [PyCozmo](https://github.com/zayfod/pycozmo) (https://pycozmo.readthedocs.io/en/stable/overview.html) Python SDK for the Cozmo robot in pure python
  - [PyATV](https://github.com/postlund/pyatv) (https://pyatv.dev/) Python library to interface with Apple TV
  - [Crayons](https://github.com/MasterOdin/crayons) (https://pypi.org/project/crayons/) Terminal string styling for Python (built atop colorama)
	
#### IaC

  - [Terraform](https://github.com/hashicorp/terraform) (https://www.terraform.io/) Tool for building, changing, and versioning infrastructure
	
### EduTech

- [IntelliJ EduTools Plugin](https://plugins.jetbrains.com/plugin/10081-jetbrains-academy):
  - [Educator Start Guide](https://www.jetbrains.com/help/education/educator-start-guide.html): NB : JPGs, MP4s etc. work as well within IntelliJ 
- [VideoScribe](https://www.videoscribe.co/en/) Create video diagrams / animated explainer videos for tutorials. 
- [carbon.now.sh](https://carbon.now.sh/) Simulated/Generated CLI / Code Screenshots (online)
- [carbon-now-cli](https://github.com/mixn/carbon-now-cli) Generated Code/Command line screenshots from the terminal
  - High quality animated screencasts:
    - GIFs: [asciinema](https://github.com/asciinema/asciinema) (https://asciinema.org/) free and open source solution for recording terminal sessions and sharing them
    - SVG: [svg-term-cli](https://github.com/marionebl/svg-term-cli) Share terminal sessions as razor-sharp animated SVG
- [ScreenToGif](https://github.com/NickeManarin/ScreenToGif) (https://www.screentogif.com/) Free screen recording tool for Windows
- [SnagIt](https://www.techsmith.com/screen-capture.html) Fully-featured screen capture tool (PAID)


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
  - Plugins:
    - [Cody](https://github.com/sourcegraph/sg.nvim) (https://github.com/sourcegraph/cody) Code search/navigation and ai assistance plugin for NeoVim
    - [Lazy](https://github.com/folke/lazy.nvim) (https://www.lazyvim.org/installation) Plugin/package manager for neovim
    - [Lualine](https://github.com/nvim-lualine/lualine.nvim) (https://github.com/nvim-lualine/lualine.nvim) A blazing fast and easy to configure neovim statusline plugin written in pure lua
    - [Mason](https://github.com/williamboman/mason.nvim) (https://github.com/nvim-lua/mason.nvim) Package manager for neovim for language servers, formatters
      - [terraform-lsp](https://github.com/hashicorp/terraform-lshttps://github.com) (https://github.com/hashicorp/terraform-ls) Terraform Language Server for Neovim
    - [Nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) (https://github.com/neovim/nvim-lspconfig) Quickstart configurations for the Nvim LSP client
    - [Oil](https://github.com/stevearc/oil.nvim) A file explorer that lets you edit your filesystem like a normal Neovim buffer
    - [Telescope](https://github.com/nvim-telescope/telescope.nvim) (https://github.com/nvim-telescope/telescope.nvim) Find, Filter, Preview, Pick. All lua, all the time.
    - [Trouble](https://github.com/folke/trouble.nvim) (https://github.com/folke/trouble.nvim) A pretty list for showing diagnostics, references, telescope results, quickfix and location lists to help you solve all the trouble your code is causing
    - [nVim Treesitter](https://github.com/nvim-treesitter/nvim-treesitter) (https://github.com/nvim-treesitter/nvim-treesitter) Neovim Treesitter configurations and abstraction layer for more advanced syntax highlighting

#### Visual Studio
- Themes:
  - [PaleNight (Material Theme)](https://marketplace.visualstudio.com/items?itemName=gjactat.palenightvs2017) Material theme (esp. Palenight) is generally awesome

#### VS Code

- [VS Code](https://github.com/microsoft/vscode) (https://code.visualstudio.com/) Code editor redefined and optimized for building and debugging modern applications
- Plugins: [Awesome VS Code](https://github.com/viatsko/awesome-vscode)
  - [Polacode](https://github.com/octref/polacode) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)) Produce screenshots of code/files in VS Code
  - [GitLens](https://github.com/eamodio/vscode-gitlens) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)) Supercharge the Git capabilities built into Visual Studio Code
  - [GitHub Pull Requests](https://github.com/Microsoft/vscode-pull-request-github) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)) GitHub Pull Requests and Issues
  - [Markdown All in One](https://github.com/yzhang-gh/vscode-markdown) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)) All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)
  - [Jira and Bitbucket](https://bitbucket.org/atlassianlabs/atlascode.git/src) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=Atlassian.atlascode)) Connect to Jira and Bitbucket
  - [CSS Peek](https://github.com/pranaygp/vscode-css-peek) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)) Peek into CSS
  - [C++](https://github.com/Microsoft/vscode-cpptools) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)) C/C++ IntelliSense, debugging, and code browsing.
  - [C#](https://github.com/OmniSharp/omnisharp-vscode) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)) C# support for Visual Studio Code
  - Java (Bundle): ([Marketplace](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)) Java Support
  - [Instant Markdown](https://github.com/yzhang-gh/vscode-markdown) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)) All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)
  - [Peacock](https://github.com/johnpapa/vscode-peacock) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)) Peacock makes it easy to switch between your editor theme colors
  - [Python](https://github.com/Microsoft/vscode-python) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-python.python)) Python support for Visual Studio Code
  - [Kotlin](https://github.com/fwcd/vscode-kotlin) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin)) Kotlin language support for Visual Studio Code
  - [Docker](https://github.com/microsoft/vscode-docker) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)) Docker extension for Visual Studio Code
  - [Settings Sync](https://github.com/shanalikhan/code-settings-sync) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)) Synchronize Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist.
  - [Sonarlint](https://github.com/SonarSource/sonarlint-vscode) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)) SonarLint for Visual Studio Code
  - [Terraform](https://github.com/mauve/vscode-terraform) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=mauve.terraform)) Terraform for Visual Studio Code
  - [Vim](https://github.com/VSCodeVim/Vim): ([Marketplace](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)) Vim emulation plugin for VS Code
  - [VSCode Icons](https://github.com/vscode-icons/vscode-icons) ([Marketplace](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)) Icons for Visual Studio Code

- AI Assistants:
  - [Cody](https://marketplace.visualstudio.com/items?itemName=sourcegraph.cody-ai) AI code assistant by the sourcegraph folks with a free tier, even has natural language code search
  - [Codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium) 'Free Forver' code assistant - intelligently generates code as you type comments or use chat

- Themes:
  - [PaleNight (Material Theme)](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) Material theme (esp. Palenight) is generally awesome
  - [Fairyfloss](https://marketplace.visualstudio.com/items?itemName=nopjmp.fairyfloss) About as far from dark mode themes as I am willing to go. Cozy much?

### Icons and Images
- https://www.flaticon.com

### Operating Systems

#### Linux
- [Distrobox](https://github.com/distrobox/distrobox) (https://distrobox.it/) Tool to create isolated environments for development (uses Docker, Pacman)
- [Pacman](https://gitlab.archlinux.org/archlinux/packaging/packages/pacman) (https://wiki.archlinux.org/index.php/Pacman) Package manager for Arch Linux

#### OSX
- [Homebrew](https://github.com/Homebrew/brew) (https://brew.sh/) Package manager for OSX

#### Windows
- [choco](https://github.com/chocolatey/choco) (https://chocolatey.org/install) Windows package manager

### Interesting Reads:
- https://www.barbarianmeetscoding.com/blog/2019/02/08/boost-your-coding-fu-with-vscode-and-vim
- https://www.robertcooper.me/elegant-development-experience-with-zsh-and-hyper-terminal
- https://www.maketecheasier.com/install-zsh-and-oh-my-zsh-windows10/
- https://www.labnol.org/internet/useful-tools-for-programmers/29227/- https://medium.com/@ssharizal/hyper-js-oh-my-zsh-as-ubuntu-on-windows-wsl-terminal-8bf577cdbd97
- https://medium.com/@cjolowicz/hypermodern-python-d44485d9d769
- https://neovim.io/doc/user/nvim.html#nvim-from-vim
	
### Web Tools

- [Postman](https://www.postman.com/) REST Client and API Platform
- [Postman Interceptor](https://chromewebstore.google.com/detail/postman-interceptor/aicmkgpgakddgnaphhhpliifpcfhicfo) Capture requests from any website and send them to Postman Client

### Workflow Automation

- [n8n](https://n8n.io/) Workflow Automation Tool (self-host)

## Books

- [Clean Code](https://www.goodreads.com/book/show/3735293-clean-code)  by **'Uncle' Bob Martin** - As someone who was a self-taught programmer this was the first time I read a book (and watched a set of eccentric videos) that pulled me out of the mindset of *"my code is excellent, it never breaks, so I don't need to write tests for it and I love to write the complex code to try new things"*, to making functional code that works for the reader and not just the writer. Highly recommend undertanding clean code concepts and SOLID software engineering. NB: Java-centric.

  <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1436202607i/3735293.jpg" width="150"/>
  
  > “Truth can only be found in one place: the code.”

  > “So if you want to go fast, if you want to get done quickly, if you want your code to be easy to write, make it easy to read.”

  > “One difference between a smart programmer and a professional programmer is that the professional understands that clarity is king. Professionals use their powers for good and write code that others can understand.”

  > “First Law You may not write production code until you have written a failing unit test. Second Law You may not write more of a unit test than is sufficient to fail, and not compiling is failing. Third Law You may not write more production code than is sufficient to pass the currently failing test.”

- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.goodreads.com/book/show/85009.Design_Patterns) - Design patterns are a general reusable solution to common problems in software design. A lot of modern languages have first class (or standard library) support for some software design patterns these days but if you have to build them yourself, select the best one for a job, or have a common 'language' for system design features with colleagues, then this book is a good place to start. Don't reinvent the wheel.

  <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1348027904i/85009.jpg" width="150"/>

  > “Design patterns should not be applied indiscriminately. Often they achieve flexibility and variability by introducing additional levels of indirection, and that can complicate a design and/or cost you some performance. A design pattern should only be applied when the flexibility it affords is actually needed.”

- [Data Structures and Algorithms](https://www.goodreads.com/author/show/15693.Michael_T_Goodrich) by **Michael T Goodrich** - Books on data structures and algorithms - your basic recipes and building blocks for solving software engineering problems. Many data structures these are first class in modern languages but when you understand them in a more abstract way then you'll make the right decisions about which to use and when.

  <div id="container" style="display: inline">
    <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1386920652i/27842.jpg" width="150"/><img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1361147120i/13838796.jpg" width="150"/><img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1347939315i/7405645.jpg" width="150"/>
  </div>

- [The Pragmatic Programmer](https://www.goodreads.com/book/show/4099.The_Pragmatic_Programmer) by **Andy Hunt** - The Pragmatic Programmer is a book about programming and software development. It is aimed at software developers who want to write better code and avoid common pitfalls.

  <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1401432508i/4099.jpg" width="150"/>

  > “Don't be a slave to history. Don't let existing code dictate future code. All code can be replaced if it is no longer appropriate. Even within one program, don't let what you've already done constrain what you do next -- be ready to refactor... This decision may impact the project schedule. The assumption is that the impact will be less than the cost of /not/ making the change.”

  > “You Can't Write Perfect Software. Did that hurt? It shouldn't. Accept it as an axiom of life. Embrace it. Celebrate it. Because perfect software doesn't exist. No one in the brief history of computing has ever written a piece of perfect software. It's unlikely that you'll be the first. And unless you accept this as a fact, you'll end up wasting time and energy chasing an impossible dream.”

  > “All software you write will be tested—if not by you and your team, then by the eventual users—so you might as well plan on testing it thoroughly.”

  > “Kaizen" is a Japanese term that captures the concept of continuously making many small improvements.”

- [Atomic Habits](https://www.goodreads.com/book/show/40121378-atomic-habits) by James Clear

  <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1655988385i/40121378.jpg" alt="Atomic Habits" width="150"/>

  Speaking of "Kaizen", its meaning is change for the better or continuous improvement, an awesome career in engineering is basically an unwritten agreement to continuously learn. So if you don't love that then it's time for a career change! Atomic Habits show how small improvements (e.g. read two pages of a book/article daily) can compound over time and lead to large rewards. It's worth applying that to your learning process.

  > “Every action you take is a vote for the type of person you wish to become. No single instance will transform your beliefs, but as the votes build up, so does the evidence of your new identity.”

  > “The only way to become excellent is to be endlessly fascinated by doing the same thing over and over. You have to fall in love with boredom.”

- [How to Work with (Almost) Anyone](https://www.goodreads.com/book/show/123051638-how-to-work-with-almost-anyone) by **Michael Bungay Stanier** - It's a fallacy that 'tech' is just about sitting down 'staring at a screen'. It's entirely possible to code in a silo but engineering is fundamentally a team sport. Whether it's collaborating on an API, a product, in a team, or asking for candid 360 feedback, or working with your manager, you'll find yourself in a situation where you need to work together. This book will help you to achieve your best possible relationship with your colleagues. (Print > Audiobook)

  <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1678429415i/123051638.jpg" width="150"/>

  > “The curse of competence traps you doing what you’re good at but not fulfilled by.”
  
  > “You do it well, so you don’t wholly trust others to do it. That’s the curse of competence.”

  Alternatively, opt for understanding:

- [Emotional Intelligence 2.0](https://www.goodreads.com/book/show/6486483-emotional-intelligence-2-0) by **Travis Bradberry & Jean Greaves** - Your IQ will only get you so far in this industry. Relationships count. Emotional intelligence is the ability to understand and manage your own and others' emotions.

  <img src="https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1328765863i/6486483.jpg" alt="Emotional Intelligence 2.0" width="150"/>

  > “Emotional intelligence is your ability to recognize and understand emotions in yourself and others, and your ability to use this awareness to manage your behavior and relationships.”

  > “The secret to winning this culture game is to treat others how they want to be treated, not how you would want to be treated.”

  > “Some of the most challenging and stressful situations people face are at work. Conflicts at work tend to fester when people passively avoid problems, because people lack the skills needed to initiate a direct, yet constructive conversation. Conflicts at work tend to explode when people don’t manage their anger or frustration, and choose to take it out on other people. Relationship management gives you the skills you need to avoid both scenarios, and make the most out of every interaction you have with another person.” 

## Contributing

Open in the sense of the 'O' in [SOLID](https://simple.wikipedia.org/wiki/SOLID_(object-oriented_design)) software engineering. i.e. "open" for extension, "closed" for modification! However, [suggestions welcome](https://freesuggestionbox.com/pub/zeolgfe)!

## Contributors

[![awesome-engineering contributors](https://contrib.rocks/image?repo=briancorbinxyz/awesome-engineering&max=2000)](https://github.com/briancorbinxyz/awesome-engineering/graphs/contributors)
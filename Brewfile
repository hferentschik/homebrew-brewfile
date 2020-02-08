# Brewfile
#
# Maintained by Hardy Ferentschik

# Install and manage GUI macOS applications
tap 'homebrew/cask'

# Alternate versions of Casks
tap 'homebrew/cask-versions'

# Integrates Homebrew formulae with macOS' `launchctl` manager
tap 'homebrew/services'

# A CLI tool upgrading every outdated app installed by Homebrew Cask
# INFO: brew cu
tap 'buo/cask-upgrade'

### System {{{
  ## System Libraries
  # Manage compile and link flags for libraries
  brew 'pkg-config'
  # Text-based UI library
  brew 'ncurses'
  # GNU internationalization (i18n) and localization (l10n) library
  brew 'gettext'
  # Library for command-line editing
  brew 'readline'
  # Core application library for C
  brew 'glib'
  # GNU multiple precision arithmetic library
  brew 'gmp'
  # Collection of portable C++ source libraries
  brew 'boost'
  # Vector graphics library with cross-device output support
  brew 'cairo'
  # Image manipulation library
  brew 'jpeg'
  # Library for manipulating PNG images
  brew 'libpng'
  # TIFF library and utilities
  brew 'libtiff'
  # Software library to render fonts
  brew 'freetype'
  # XML lib
  brew 'libxml2'

  ## Mac OS X
  # Homebrew GUI App for OS X
  cask 'cakebrew'
  # Mac App Store command line interface
  brew 'mas'
  # System Utilities for macOS
  cask 'onyx'
  # Swiss Army Knife for macOS
  brew 'm-cli'
  # System monitor for tray
  cask 'istat-menus'

  ## Mac OS X: Quick Look Plugins
  # An Application for Inspecting macOS Installer Packages
  cask 'suspicious-package'
  # View plain text files without a file extension
  cask 'qlstephen'
  # Preview source code files with syntax highlighting
  cask 'qlcolorcode'
  # Preview JSON files
  cask 'quicklook-json'
  # Display image size and resolution
  cask 'qlimagesize'

  ## Monitoring
  # An interactive process viewer for Unix
  brew 'htop'
  # Display an interface's bandwidth usage
  brew 'iftop'
  # Top-like interface for container metrics
  brew 'ctop'
  # Keep Mac clean
  cask 'cleanmymac'
### }}}


### File System {{{
  ## Cloud
  cask 'google-drive-file-stream'

  ## Recovery
  # Console program to recover files based on their headers and footers
  brew 'foremost'

  ## Online storage
  cask 'dropbox'
### }}}

### Web {{{
  ## Web Browser
  cask 'google-chrome'
  cask 'firefox-developer-edition'

  ## Flash Player for Web Browser
  # Adobe Flash Player NPAPI (plugin for Safari and Firefox)
  cask 'flash-npapi'
  # Adobe Flash Player PPAPI (plugin for Opera and Chromium)
  cask 'flash-ppapi'

  ## HTTP Request
  # Powerful HTTP and GraphQL tool belt
  cask 'insomnia'
  # API Development Environment
  cask 'postman'
  # The most advanced API tool for Mac
  cask 'paw'
  # Internet file retriever
  brew 'wget'
  # User-friendly cURL replacement (command-line HTTP client)
  brew 'httpie'

  ## Static Gen
  # The world’s fastest framework for building websites
  brew 'hugo'
### }}}

### Audio {{{
  ## Player
  cask 'spotify'
### }}}

### Video {{{
  ## Player
  # VLC media player
  cask 'vlc'

  ## Recorder
  # An open-source screen recorder built with web technology
  cask 'kap'

  ## Pair programming
  # Mac only pair programming tool
  cask 'tuple'
### }}}

### Image {{{
  ## Utility
  # Perl lib for reading and writing EXIF metadata
  brew 'exiftool'

  ## UI/UX
  # Connected space for product teams
  cask 'zeplin'
### }}}

### Messaging {{{
  cask 'slack'
  cask 'telegram'
  cask 'whatsapp'
  cask 'franz'
### }}}

### Email {{{
  brew 'neomutt'
  brew 'offlineimap'
  # IMAP filtering 
  brew 'imapfilter'
  # Mail indexing
  brew 'mu'
### }}} 

### Network {{{
  ## Analysis
  # The world’s foremost and widely-used network protocol analyzer
  cask 'wireshark'
  # Port scanning utility for large networks
  brew 'nmap'

  ## Proxy & VPN
  # Free software for OpenVPN on OS X
  cask 'tunnelblick'
  # For an instant, secure URL to your localhost server through any NAT or firewall
  cask 'ngrok'
  # Man in the middle proxy
  brew 'mitmproxy'

  ## Utility
  # MAC spoofing GUI for macOS
  cask 'linkliar'
### }}}

### Keyboard & Mouse {{{
  # Know your short cuts
  cask 'cheatsheet'
  # A simple utility application to trigger haptic feedback when tapping Touch Bar
  cask 'haptickey'
### }}}

### Utility {{{
  # GNU File, Shell, and Text utilities
  brew 'coreutils'
  ## Compress/Uncompress
  # 7-Zip (high compression file archiver) implementation
  brew 'p7zip'
  # General-purpose data compression with high compression ratio
  brew 'xz'
  # Executes a program periodically, showing output fullscreen
  brew 'watch'
  # Simplified and community-driven man pages
  brew 'tldr'

  # Boosts your efficiency with hotkeys, keywords, text expansion and more
  cask 'alfred'

  # Organize the menu bar icons
  cask 'bartender'
  # A single place for all of your web applications
  cask 'station'
  # The calendar app you won't be able to live without
  cask 'fantastical'

  # De-duplicate files
  brew 'fdupes'

  # GNU version of awk and sed
  brew 'gawk'
  brew 'gnu-sed'

  # JSON, YAML, XML transformation
  brew 'jq'
  brew 'yq'
  brew 'xmlstarlet'

  cask 'evernote'

  # Cut Raspberry Pi images
  cask 'balenaetcher'

  # MySQL DB viewer
  cask 'sequel-pro'

  # ToDo list managment
  cask 'remember-the-milk'
### }}}

### Programming Language {{{
  ## Node.js
  # Platform built on V8 to build network applications
  brew 'node@10'
  # Alternative JavaScript package manager by Facebook
  brew 'yarn'

  ## Python
  # Python3
  brew 'python'
  # Python2
  brew 'python@2'
  # Python dependency management tool
  brew 'pipenv'

  ## Golang
  # Open source programming language to build simple/reliable/efficient software
  brew 'go'

  ## Java
  # Java Standard Edition Development Kit 12
  # INFO: Need to reboot
  cask 'java'
  # An open and reproducible build & test system for OpenJDK
  # INFO: Need to install OpenJDK 8
  cask 'adoptopenjdk8'
  # Java build tool
  brew 'ant'
  # Java-based project management
  brew 'maven'

  ## Shellscript
  # Static analysis and lint tool, for (ba)sh scripts
  brew 'shellcheck'

  ## Lua
  # Powerful, lightweight programming language
  brew 'lua'
  # Just-In-Time Compiler (JIT) for the Lua programming language
  brew 'luajit'
  # Package manager for the Lua programming language
  brew 'luarocks'

  ## Ruby
  # Powerful, clean, object-oriented scripting language
  brew 'ruby'
  brew 'rbenv'
  brew 'rbspy'

  ## Dev Docs
  cask 'dash'
### }}}

### VCS {{{
  ## Git & GitHub
  # Distributed revision control system
  brew 'git'
  # Git extension for versioning large files
  brew 'git-lfs'
  # Small git utilities
  brew 'git-extras'
  # Extensions to follow Vincent Driessen's branching model
  brew 'git-flow'
  # Prevents you from committing sensitive information to a git repo
  brew 'git-secrets'
  # Remove crazy big files, passwords, credentials and other private data
  brew 'bfg'
  # Text interface for Git repositories
  brew 'tig'
  # A simple terminal UI for git commands
  brew 'lazygit'
  # OS X status bar application for Github
  cask 'gitee'
  # Extend your GitHub workflow beyond your browser <Paste>
  cask 'github'

  ## Mercurial
  # Scalable distributed version control system
  brew 'mercurial'

  ## ETC
  # Clone of cat with syntax highlighting and Git integration
  brew 'bat'

  # GitHub workflow
  brew 'hub'
### }}}


### Code Editor & IDE {{{
  ## Editor: Vim
  # Vi 'workalike' with many additional features
  brew 'vim'
  # Ambitious Vim-fork focused on extensibility and agility
  brew 'neovim'
  # Default catch all editor
  cask 'sublime-text'

  ## Editor: Microsoft Visual Studio Code
  cask 'visual-studio-code'

  ## IDE
  # JetBrain
  cask 'goland'
  cask 'rubymine'
  cask 'intellij-idea'
  cask 'datagrip'
### }}}


### Terminal {{{
  ## Terminal Emulator
  # Terminal Emulator for macOS
  cask 'iterm2'

  ## Terminal Multiplexer
  # Terminal multiplexer with VT100/ANSI terminal emulation
  brew 'screen'
  # A terminal multiplexer, allowing to access multiple separate terminal sessions
  # brew 'tmux', args: ['with-utf8proc']
  brew 'tmux'
  # Reattach process (e.g., tmux) to background
  brew 'reattach-to-user-namespace'

  ## Utility
  # Modern replacement for `ls`
  brew 'exa'

  ## Shell: Bash
  # Bourne-Again SHell, a UNIX command interpreter
  brew 'bash'
  # Programmable completion for Bash 4.1+
  brew 'bash-completion@2'

  ## Shell: Fish
  # User-friendly command-line shell for UNIX-like operating systems
  # INFO: Need to add `/usr/local/bin/fish` to `/etc/shells`
  brew 'fish'

  ## Shell: Zsh
  # UNIX shell (command interpreter)
  # INFO: Need to add `/usr/local/bin/zsh` to `/etc/shells`
  brew 'zsh'
  # Tips, tricks, and examples for zsh
  brew 'zsh-lovers'
#}}}

### Virtualization {{{
  ## Virtual Machine
  # Oracle VirtualBox
  # INFO: Need to enable their kernel extension
  cask 'virtualbox'

  ## Container
  # Docker Community Edition for Mac (Edge)
  cask 'docker-edge'
  # Container inspector
  brew 'dive'
  # The lazier way to manage everything docker
  brew 'lazydocker'
  # Kubernetes command-line interface
  brew 'kubernetes-cli'
  # The Kubernetes package manager
  #brew 'kubernetes-helm@2'
  # Customization of kubernetes YAML configurations
  brew 'kustomize'
  # Tool that can switch between kubectl contexts easily and create aliases
  brew 'kubectx'
  # Kubernetes CLI to manage cluters in style
  tap 'derailed/k9s'
  brew 'k9s'
  # Tool for repeatable Kubernetes development
  brew 'skaffold'
  # Kubernetes log viewer
  tap 'boz/repo'
  brew 'kail'
  # Production Grade K8s Installation, Upgrades, and Management
  brew 'kops'
  # Kube in Docker
  brew 'kind'
### }}}


### Development {{{
  # Automatic configure script builder
  brew 'autoconf'
  # Tool for generating GNU Standards-compliant Makefiles
  brew 'automake'
  # Cross-platform make
  brew 'cmake'
  # Generic library support script
  # INFO: In order to prevent conflicts with Apple's own libtool we have prepended a "g"
  brew 'libtool'
  # File watching daemon
  brew 'fswatch'
### }}}


### DevOps {{{
  # Tool to build, change, and version infrastructure
  brew 'terraform'
  # Tool to generate documentation from Terraform modules
  brew 'terraform-docs'
  # Thin wrapper for Terraform e.g. for locking state
  brew 'terragrunt'
  # Terraform linter for detecting errors that can not be detected by `terraform plan`
  tap 'wata727/tflint'
  brew 'tflint'

  # Tool for building and managing virtual machine environments
  cask 'vagrant'
  # Manage your vagrant machines in one place
  cask 'vagrant-manager'

  # Tool for creating identical machine images for multiple platforms
  brew 'packer'
  # Automate deployment, configuration, and upgrading
  brew 'ansible'

  # Enables you to reproduce the CircleCI environment locally
  brew 'circleci'
### }}}

### Cloud {{{
  brew 'awscli'
  brew 'awslogs'
### }}}  


### Cryptography {{{
  # SSL/TLS cryptography library
  brew 'openssl'

  ## PGP(Pretty Good Privacy)
  # GNU Pretty Good Privacy (PGP) package
  brew 'gnupg'

  # A password manager, digital vault, form filler and secure digital wallet
  cask 'dashlane'

  # Hashicorp secret store
  brew 'vault'

  # GPG key management
  cask 'gpg-suite'
### }}}

### Hacking {{{
  # GNU debugger
  brew 'gdb'
### }}}

### Font {{{
  # XML-based font configuration API for X Windows
  brew 'fontconfig'

  ## Font Family: Icons
  # Most popular icon toolkit
  cask 'homebrew/cask-fonts/font-fontawesome'
  # Simple and Minimal Line Icons
  cask 'homebrew/cask-fonts/font-simple-line-icons'
  # Material Design icons by Google
  cask 'homebrew/cask-fonts/font-material-icons'
  # An iconic font made for developers
  cask 'homebrew/cask-fonts/font-devicons'
  # WordPress admin icon font
  cask 'homebrew/cask-fonts/font-dashicons'
  # The premium icon font for Ionic Framework and web apps everywhere
  cask 'homebrew/cask-fonts/font-ionicons'

  ## Font Family: Nanum
  cask 'homebrew/cask-fonts/font-nanumgothic'
  cask 'homebrew/cask-fonts/font-nanumgothiccoding'
  cask 'homebrew/cask-fonts/font-nanummyeongjo'

  ## Font Family: Open Sans
  cask 'homebrew/cask-fonts/font-open-sans'
  cask 'homebrew/cask-fonts/font-open-sans-condensed'

  ## Font Family: ETC
  cask 'homebrew/cask-fonts/font-ubuntu'
  cask 'homebrew/cask-fonts/font-source-han-noto-cjk'
  cask 'homebrew/cask-fonts/font-source-code-pro'
  cask 'homebrew/cask-fonts/font-roboto'
  cask 'homebrew/cask-fonts/font-hack'
  cask 'homebrew/cask-fonts/font-d2coding'
  cask 'homebrew/cask-fonts/font-inconsolata'
  cask 'homebrew/cask-fonts/font-dejavu-sans'
  cask 'homebrew/cask-fonts/font-fira-code'
  cask 'homebrew/cask-fonts/font-fira-mono'

  ## Font Family: Powerline
  cask 'homebrew/cask-fonts/font-anonymice-powerline'
  cask 'homebrew/cask-fonts/font-consolas-for-powerline'
  cask 'homebrew/cask-fonts/font-dejavu-sans-mono-for-powerline'
  cask 'homebrew/cask-fonts/font-droid-sans-mono-for-powerline'
  cask 'homebrew/cask-fonts/font-fira-mono-for-powerline'
  cask 'homebrew/cask-fonts/font-inconsolata-for-powerline'
  cask 'homebrew/cask-fonts/font-liberation-mono-for-powerline'
  cask 'homebrew/cask-fonts/font-menlo-for-powerline'
  cask 'homebrew/cask-fonts/font-meslo-for-powerline'
  cask 'homebrew/cask-fonts/font-monofur-for-powerline'
  cask 'homebrew/cask-fonts/font-noto-mono-for-powerline'
  cask 'homebrew/cask-fonts/font-roboto-mono-for-powerline'
  cask 'homebrew/cask-fonts/font-source-code-pro-for-powerline'
  cask 'homebrew/cask-fonts/font-ubuntu-mono-derivative-powerline'
### }}}

### App Store {{{
appstore 1462114288 Grammarly for Safari (9.10)
appstore 409183694 Keynote (9.2.1)
appstore 405399194 Kindle (1.26.1)
appstore 409203825 Numbers (6.2.1)
appstore 409201541 Pages (8.2.1)
appstore 485812721 TweetDeck (3.16.1)
appstore 497799835 Xcode (11.1)
appstore 638161122 YubiKey Personalization Tool (3.1.24)
### }}}

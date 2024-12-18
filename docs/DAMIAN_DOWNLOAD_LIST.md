### Code Editors

#### Visual Studio Code
A versatile and widely used source code editor.

*   **Download Link:** [Visual Studio Code](https://code.visualstudio.com/download)
*   **Install Guide:**
    1.  Download the `.dmg` file from the official website.
    2.  Open the downloaded file.
    3.  Drag the VS Code icon to the Applications folder.
    4.  Launch from Applications or Dock.

### Local LLM Environment

#### LM Studio
An application to discover, download, and run local Large Language Models (LLMs). Supports various models including Llama, Mistral, and Qwen.

*   **Download Link:** [LM Studio](https://lmstudio.ai/)
*   **Install Guide:**
    1. Download the `.dmg` file from the official website.
    2. Open the downloaded file.
    3. Drag the LM Studio application to the Applications folder.
    4. Launch and follow on-screen instructions to download models such as Qwen 14B.

### Containerization

#### Docker Desktop
A popular containerization tool for developers.

*   **Download Link:** [Docker Desktop](https://www.docker.com/products/docker-desktop)
*   **Install Guide:**
    1.  Download the `.dmg` file from the official website.
    2.  Open the downloaded file.
    3.  Drag the Docker app to the Applications folder.
    4.  Launch and follow the installation steps.

### Version Management

#### asdf
An extendable version manager for multiple languages and tools.

*   **Download Link:** [asdf](https://asdf-vm.com/)
*   **Install Guide:**
    1.  Install dependencies: `brew install coreutils curl git`
    2.  Download asdf: `git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.14.1`
    3.  Add to your shell config (~/.zshrc or ~/.bashrc):
        ```bash
        . "$HOME/.asdf/asdf.sh"
        . "$HOME/.asdf/completions/asdf"
        ```

#### Python 3.12.5 via asdf
A specific version of Python managed by asdf.

*   **Install Guide:**
    1. Install asdf if you haven't yet as described above
    2. Add the Python plugin for asdf: `asdf plugin-add python`
    3. Install Python 3.12.5: `asdf install python 3.12.5`
    4. Set global version: `asdf global python 3.12.5`

#### Node.js Latest via asdf
Latest version of Node.js managed by asdf.

*   **Install Guide:**
    1.  Install asdf if you haven't yet as described above
    2.  Add the Node.js plugin for asdf: `asdf plugin-add nodejs`
    3.  Install latest Node.js: `asdf install nodejs latest`
    4.  Set global version: `asdf global nodejs latest`

### Package Managers

#### Homebrew
The missing package manager for macOS.

*   **Download Link:** [Homebrew](https://brew.sh/)
*   **Install Guide:**
    1.  Open Terminal
    2.  Paste and run this command:
        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    3. Follow the on screen prompts, and add the Homebrew path to your shell, as the installation will prompt.

### Shell

#### Zsh via Brew
Zsh is a powerful shell, installable via Homebrew

*   **Install Guide:**
    1. Install Homebrew if you haven't yet as described above
    2. Open Terminal and type: `brew install zsh`

#### Starship
A customizable, cross-shell prompt.

*   **Download Link:** [Starship](https://starship.rs/)
*  **Install Guide:**
    1. Follow the install steps via the documentation.
    2. Most commonly this involves installing via brew `brew install starship`
    3. Update your shell config file (`~/.zshrc` or `~/.bashrc`) as the installation will prompt.

### API Key Management

#### 1Password
A password manager that provides security and convenience

*   **Download Link:** [1Password](https://1password.com/downloads/mac/)
*   **Install Guide:**
    1.  Download the app from the website.
    2.  Open the `.dmg` file.
    3.  Drag the 1Password app to the Applications folder.
    4.  Launch the application and follow the setup instructions.

*   **Alternative:**
  *   LastPass (if you prefer): [LastPass](https://www.lastpass.com/downloads)

### Mobile Development

#### Android Studio
The official IDE for Android app development.

*   **Download Link:** [Android Studio](https://developer.android.com/studio)
*  **Install Guide:**
    1. Download the `.dmg` file from the official website.
    2. Open the downloaded file.
    3. Drag the Android Studio app to the Applications folder.
    4. Launch the application and follow the setup wizard.

#### Xcode
Apple's IDE for developing apps across Apple platforms.

*   **Download Link:** [Xcode](https://developer.apple.com/xcode/) (Available on the Mac App Store)
*  **Install Guide:**
    1. Open the Mac App Store.
    2. Search for "Xcode".
    3. Click "Install".
    4. Follow the on screen instructions.

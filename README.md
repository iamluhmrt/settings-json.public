# VSCode Settings Configuration

This repository contains a customized `settings.json` for Visual Studio Code, designed to enhance productivity and provide a clean, efficient development environment.

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/iamluhmrt/settings-json.public.git
   ```

2. **Navigate to the project folder:**

   ```bash
   cd settings-json.public
   ```

3. **Copy the `settings.json` file to your VSCode configuration folder:**

   * **Linux/macOS:** `~/.config/Code/User/settings.json`
   * **Windows:** `%APPDATA%\Code\User\settings.json`

   Or simply use:

   ```bash
   cp settings.json ~/.config/Code/User/settings.json
   ```

4. **Restart VSCode** to apply the new settings.

## 🎨 Customizations

### ✍️ Editor Configuration

* **Font Family:** IBM Plex Mono, Monaco, Courier New
* **Font Size:** 14px
* **Line Height:** 25px
* **Tab Size:** 2 spaces
* **Word Wrap:** Enabled
* **Bracket Pair Colorization:** Disabled

### 🖥️ Workbench & Theme

* **Startup Editor:** Opens a new untitled file
* **Activity Bar:** Visible
* **Sidebar Location:** Right side
* **Color Theme:** Catppuccin Macchiato

### 🗺️ Minimap

* **Render Characters:** Disabled
* **Minimap Visibility:** Disabled

### 🖋️ HTML & Prettier Formatting

* **Auto Close Tags:** Disabled
* **Format on Save:** Enabled
* **Wrap Attributes:** Auto
* **Prettier Configurations:**

  * JSX Single Quote: `true`
  * Tab Width: `2`
  * Single Quote: `true`

### 🔧 Terminal & Git

* **Integrated Terminal Environment:** Empty for Linux
* **Open Repositories in Parent Folders:** Disabled

### 📂 Explorer

* **Compact Folders:** Disabled

### 🔐 Security

* **Workspace Trust:** Automatically open untrusted files
* **Allowed UNC Hosts:** WSL.localhost

### 🔄 Miscellaneous

* **Live Server Settings:**

  * Info Message Disabled
  * Tag Verification Disabled
* **Telemetry:** Disabled
* **Outline Icons:** Disabled
* **Breadcrumbs Path:** Disabled
* **Glassit Transparency Level:** 233

## 🚀 Usage

After copying the `settings.json`, restart VSCode to apply the configurations. Enjoy the streamlined experience!

## 🤝 Contributions

Feel free to open issues or submit PRs if you have suggestions for improvements.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

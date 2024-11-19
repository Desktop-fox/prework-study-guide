# Prework Study Guide Webpage

## Description

This study guide is designed to help me learn the main topics covered in prework more effectively. Building this project taught me foundational skills in HTML, CSS, and JavaScript. These programming languages work together to create the visually appealing and functional websites we see today.

## Installation

### Setting Up Your Environment

1. **Download Git Bash (CLI)**  
   Install Git Bash to use the command line. Once installed, navigate to your desired folder (e.g., `/c/Users/YourUsername`) using CLI commands. Create a new folder for bootcamp files with the command:
   ```bash
   mkdir bootcamp
   ```
   Inside this folder, create another folder for your project:
   ```bash
   mkdir prework-study-guide
   ```

2. **Set Up GitHub and SSH Key**  
   Create a GitHub account if you don't have one. To connect Git Bash to your GitHub repository, you'll need an SSH key:
   - Check for existing SSH keys:
     ```bash
     ls -al ~/.ssh
     ```
   - If no key exists, follow the instructions [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key).
   - Add your SSH key to GitHub by following [this guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

3. **Download Visual Studio Code (VS Code)**  
   Download and install VS Code, a powerful text editor, from [here](https://code.visualstudio.com/download).

4. **Sync Local Environment with GitHub**  
   - Create a new repository on GitHub. Name it the same as your project folder (e.g., `prework-study-guide`).
   - Copy the repository's SSH link from GitHub.
   - In Git Bash, navigate to your project folder and clone the repository:
     ```bash
     git clone <paste SSH link>
     ```
   This syncs your local folder with your GitHub repository.

### Start Coding

1. Open the project folder in VS Code:
   ```bash
   code .
   ```
2. Add necessary files (e.g., `index.html`, `style.css`, `script.js`) and start building your webpage.

### Organize Assets

Create a folder for assets:
```bash
mkdir Assets
```
Place your CSS and JavaScript files in this folder and link them to your `index.html`.

## Usage

The guide provides sections on HTML, CSS, JavaScript, and Git. Open the webpage in a browser and use Chrome DevTools (console tab) to see JavaScript in action.

## Credits

N/A

## License

MIT License  
[Learn more](https://opensource.org/license/mit)
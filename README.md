# GitSync v2.0

An interactive CLI tool to safely and easily sync your Git branches. It provides a guided, step-by-step process to update your feature branch from a main development branch (like `main` or `develop`), automating the tedious `git checkout/pull/merge` workflow to prevent errors and save you time.

*(Pro-tip: You can record a short GIF of the terminal session and upload it to your repo to embed here\!)*



## Key Features

  * ** Interactive Experience:** No need to remember commands or arguments. The tool guides you with simple prompts.
  * ** Built-in Safety:** A final confirmation step before any merge or push action prevents costly mistakes.
  * ** Smart Defaults:** Automatically detects your current branch and suggests sensible defaults to speed up the process.
  * ** Flexible:** Easily specify any main branch you use, whether it's `develop`, `main`, or `master`.
  * ** Auto-Commit:** Safely commits any work-in-progress changes on your current branch before starting the sync process.

## Installation & Usage

### 1\. Download the Script

Save the `gitsync` script to a location on your computer.

### 2\. Make It Executable

Open your terminal and run the following command to give the script permission to execute:

```bash
chmod +x /path/to/your/gitsync
```

### 3\. Make It Globally Accessible (Recommended)

To run the script from any project directory, move it into your system's PATH. A common location is `/usr/local/bin/`.

```bash
# This command moves the script and renames it to 'gitsync' for easy use
sudo mv /path/to/your/gitsync /usr/local/bin/gitsync
```

### 4\. Run It\!

Navigate to your project's directory in the terminal and simply run the command:

```bash
gitsync
```

The script will then launch its interactive session and guide you through the rest of the process.

## License

This project is licensed under the MIT License.
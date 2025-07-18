# Git Sync Utility Script

A simple bash script to automate the process of committing current work and syncing a feature branch with the `develop` branch.

## What It Does
This script automates the following common workflow:
1.  Checks for uncommitted local changes and prompts for a commit message to save them.
2.  Switches to the `develop` branch and pulls the latest updates.
3.  Switches back to your original branch.
4.  Merges the updated `develop` branch into your feature branch.
5.  Pushes the synced branch to the remote repository.

## How to Use
1.  **Place the Script**: Put the `gitsync.sh` script somewhere in your system's PATH (e.g., `/usr/local/bin/`).
2.  **Make it Executable**: `chmod +x /path/to/your/gitsync.sh`
3.  **Run it**:
    * From within your project repo, simply run `gitsync.sh`.
    * To sync a specific branch, run `gitsync.sh <branch-name>`.

## License
This project is licensed under the MIT License.
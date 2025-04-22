# Linux User Info Script

A simple and efficient Linux shell script to retrieve and display detailed information about a specified user from the `/etc/passwd` file.

## 📌 Description

This script fetches and displays the following details about a user:
- Username
- UID (User ID)
- GID (Group ID)
- Comment field (usually user’s full name or description)
- Home directory path
- Path to the default shell
- Home directory size (in KB)

At the end, it also displays:
- The current user executing the script
- The home directory of the current user

## 📂 How It Works

1. Takes the username as an argument.
2. Extracts user information from the `/etc/passwd` file.
3. Uses commands like `cut`, `grep`, and `du` to parse and retrieve required fields.
4. Handles errors gracefully by redirecting them to `/dev/null`.


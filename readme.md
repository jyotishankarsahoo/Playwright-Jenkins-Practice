# 🚀 Project Setup Guide: Setting Up Git and Initial Commit

This guide explains the steps required to initialize a local Git repository, commit your initial code, and connect it to a remote repository on a service like GitHub.

## Prerequisites

Before starting, ensure you have completed the following:

1.  **Git Installed:** Git must be installed on your local machine.
2.  **Remote Repository Created:** You must have already created an **empty repository** on GitHub (or another service) and have its URL ready.

---

## Git Setup Steps (Using Visual Studio Code's Source Control)

This workflow is designed for developers using an integrated environment like Visual Studio Code's **Source Control** panel.

### Step 1: Initialize the Local Repository (`git init`)

This step turns your current project folder into a Git repository.

1.  Open the **Source Control** view (Ctrl+Shift+G or Command+Shift+G).
2.  Click the **Initialize Repository** button (or the equivalent option if a workspace is already open).

---

### Step 2: Stage All Changes (`git add .`)

This stages all current project files, preparing them for the first commit.

1.  In the **Source Control** view, locate the **Changes** section.
2.  Click the **"Stage All Changes"** button (usually a small **`+`** icon next to the "Changes" heading). All files should move to the "Staged Changes" section.

---

### Step 3: Create the Initial Commit (`git commit -m "message"`)

This officially saves the initial version of your project to your local repository history.

1.  Enter your commit message (e.g., "Initial project setup" or "First commit") into the **Message** text box at the top of the Source Control panel.
2.  Press the **Commit** button.

---

### Step 4: Connect to Remote & Push (`git remote add [URL]`, `git branch -m main`, & `git push`)

This final step connects your local repository to your remote GitHub repository and pushes the committed code.

1.  In the **Source Control** view, click the **More Actions** button (**`...`**).
2.  Select **Remote** → **Add Remote**.
3.  **Paste the Git Hub repository URL** you created and press Enter.
4.  When prompted, provide a name for the remote (e.g., **`origin`**) and press Enter.
5.  Click the **Publish Branch** button to complete the setup and push your initial commit.

Your code is now published and visible on GitHub! 🎉

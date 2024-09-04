# Contributing Process

Make sure you have git installed and can use it on your terminal/command prompt

- Clone the repo to your device
    ```bash
    git clone <url>

- Before you begin working on something, create an issue on GitHub describing your feature and assign it to yourself (and any other teammates). This ensures that multiple people aren't working on the same thing.

- Create a new branch for your feature. **DO NOT MAKE CHANGES TO THE MAIN BRANCH**. Use this command to create your branch. X is the issue number 1, 2, 3, ..., X.
    ```bash
    git switch -c <X-feature-branch>

- Once you finish your feature, check for changes to the **main** branch.
  ```bash
  git switch main
  git pull

- If there are any changes, merge **main** to **feature-branch** (test code after merging)
    ```bash
    git switch <feature-branch>
    git merge main

- Push the changes to **feature-branch**. **NOT MAIN**.
    ```bash
    git add <features>
    git commit -m "<explanation of feature>"
    git push origin <feature-branch>

- After pushing to `feature-branch` open a **pull request** on GitHub (website)

After you have made a PR, your code will be reviewed. If there are any concerns by your team-members, fix them. Then your code will be pushed to the **main** branch and the **feature_branch** will be deleted.

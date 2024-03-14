To commit your changes directly to the main branch in your Git repository using Git Codespaces, you can follow these steps:

Stage your changes: Use the git add command to stage the changes you've made to the index.html and styles.css files. Navigate to your project directory in the terminal and execute:

```bash
git add index.html styles.css
```

This command stages the changes in the specified files for commit.

Commit your changes: Use the git commit command to commit the staged changes. You should provide a meaningful commit message to describe the changes you've made. Execute:

```bash
git commit -m "Describe your changes here"
```

Replace "Describe your changes here" with an informative message summarizing the changes you've made.

Push your changes: Finally, use the git push command to push your committed changes directly to the main branch of your repository. Execute:

```bash
git push origin main
```

This command pushes your changes to the main branch of the remote repository named "origin".

After following these steps, your changes should be successfully committed and pushed to the main branch of your repository. Make sure you are authorized to push changes directly to the main branch, as this might depend on the repository's settings and your access permissions.


## Pull the changes from the GitHub repository using the git pull command:

```bash
git pull origin main
```

This command fetches the changes from the main branch of your GitHub repository (origin) and merges them into your local branch.
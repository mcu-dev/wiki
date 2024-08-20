# mcu-dev Documentation

MCU-Dev is dedicated to fostering innovation and collaboration in the embedded systems community by creating and sharing reusable projects, drivers, and applications. Our mission is to provide high-quality, open-source resources that anyone can freely copy, use, and modify, enabling developers worldwide to accelerate their projects and push the boundaries of what's possible with microcontroller technology. Through our commitment to open collaboration, we aim to empower engineers and hobbyists alike to build more efficient, reliable, and creative solutions.

## Links:

- MKDocs: [https://mcu-dev.github.io/wiki](https://mcu-dev.github.io/wiki/)

## How to Contribute

### Fork the Repository

 - Sign in to GitHub: Ensure you're signed in to your GitHub account. If you don’t have one, you’ll need to create it.
 - Navigate to the Repository: Go to the MCU-Dev GitHub repository you want to contribute to.
 - Fork the Repository: Click the "Fork" button at the top right corner of the repository page. This creates a personal copy of the repository under your GitHub account.

### Clone Your Fork

Clone to Your Local Machine: Open your terminal or command prompt, and clone your forked repository using the following command:

git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git

### Create a New Branch

 - Create and Switch to a New Branch: It’s good practice to create a new branch for each feature or bug fix you’re working on. This keeps your changes isolated and makes it easier to manage pull requests. Create a new branch using:

```
git checkout -b your-branch-name
```

### Make Your Changes

 - Edit the Code: Make the necessary changes in the codebase. This could be fixing a bug, adding a new feature, improving documentation, or any other contribution.
 - Test Your Changes: Before committing, make sure to test your changes to ensure everything works as expected.

### Commit Your Changes

 - Stage Your Changes: Add the files you’ve modified to the staging area:

```
git add .
```

 - Commit with a Message: Commit your changes with a clear and concise commit message:

```
git commit -m "Your descriptive commit message"
```

### Push Your Changes to GitHub

 - Push the Changes: Push your branch to your GitHub fork:

```
git push origin your-branch-name
```

### Create a Pull Request

 - Navigate to the Original Repository: Go back to the original MCU-Dev repository on GitHub.
 - Compare & Pull Request: You’ll see a prompt to compare the branches and create a pull request. Click on the "Compare & pull request" button.
 - Fill Out the PR Form: Provide a title and description for your pull request, explaining what changes you’ve made and why they should be merged.
 - Submit the Pull Request: Click "Create pull request" to submit your changes for review.

### Collaborate on the Review

 - Address Feedback: The project maintainers may provide feedback or request changes. Be sure to address any comments and push updates to your branch as needed.
 - Merge Your Changes: Once your pull request is approved, it will be merged into the main repository. In some cases, the maintainers will ask you to merge it yourself.

### Keep Your Fork Updated

 - Sync with Upstream: To keep your fork updated with the latest changes from the original repository, you can add the original repository as an upstream remote and pull in the latest changes:

```
git remote add upstream https://github.com/ORIGINAL-OWNER/REPOSITORY-NAME.git
git fetch upstream
git checkout main
git merge upstream/main
```

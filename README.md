## Cloning a Git Repository with Main and Development Branches

This guide provides step-by-step instructions for cloning a remote Git repository with the main and development branches and switching to the development branch where you can work on new features without affecting the main branch.

## Prerequisites
- Git installed on your local system
- A GitHub account

## Steps
1. Open your terminal window.
2. Navigate to the directory where you want to clone the repository by running the following command:
```sh
cd /path/to/your/directory
```
3. Run the following command to clone the repository with the main branch:
```sh
git clone https://github.com/paolochikalo/new-project.git
```
4. Run the following command to switch to the development branch:
```sh
git checkout development
```
Note: If you want to make changes to the code without affecting the main branch, make sure to switch to the development branch before making any changes.

5. You have now cloned the Git repository with both main and development branches and switched to the development branch. You can now make changes to the code and commit them to the development branch without affecting the main branch.


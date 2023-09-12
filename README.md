<h1 align="center">Simple & Eassy Notes Solved Some Common Git Error:)</h3>



![git-push-rejected](https://github.com/ikramuzzaman455173/some-common-error-solve-git/assets/106922916/08de691a-a40f-46fb-b86b-0f79a663771c)

# Git Push Error: Non-Fast-Forward Rejection

If you encounter the "non-fast-forward" error while trying to push your changes to a Git repository, it means that your local branch is behind its remote counterpart. This guide will help you resolve the issue.

## How to Fix the Error

Follow these steps to fix the "non-fast-forward" error:

```bash
# Step 1: Commit Your Changes
git commit -m "Your commit message"

# Step 2: Fetch Remote Changes
git fetch origin

# Step 3: Merge Remote Changes
git merge origin/main
# Replace 'main' with the name of your branch if different

# Step 4: Resolve Conflicts
# If there are merge conflicts, resolve them and commit the changes

# Step 5: Push Your Changes
git push origin main
# Replace 'main' with your branch name

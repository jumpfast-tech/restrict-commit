# Restrict Commit Hook

This repository contains a Git pre-commit hook designed to prevent commits on branches that have already been merged. Once a branch is marked as merged, this hook will block any further commits to ensure a clean and organized Git history, reducing potential conflicts and confusion in collaborative projects.

## Hook Installation Instruction
To install the restrict commit hook in your local Git repository, follow these steps:
```bash
# Download the hook script from the restrict-commit repository
curl -o .git/hooks/pre-commit https://raw.githubusercontent.com/jumpfast-tech/restrict-commit/main/hooks/pre-commit

# Make the hook executable
chmod +x .git/hooks/pre-commit
```
This will add the pre-commit hook to your Git repository, automatically running it before each commit to ensure no changes are made to already merged branches.

## Support
For any issues, questions, or feedback regarding the restrict commit hook, please contact our development team at [contact@jumpfast.tech](mailto:contact@jumpfast.tech)
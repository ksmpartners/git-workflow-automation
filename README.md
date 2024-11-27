# git-workflow-automation
Demonstrate proof of concept of using Git APIs to automate the branch creation and pull request process.

# GitHub Actions
There are currently two `.yml` files contained in this repository to create two GitHub Actions workflows. The first is intended to trigger branch creation upon creation of an issue in the repository. The second is intended create a pull request after any code is pushed to an `Issue/<x>` branch from a Domino workspace. Currently, the system can't tell if the source of the push is Domino. To be added later if possible.

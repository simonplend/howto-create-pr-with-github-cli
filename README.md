# How to create a pull request with the GitHub CLI

0. Open up your terminal, because this is all about the command line!

1. Follow the instructions here to install the GitHub CLI: https://github.com/cli/cli#installation

2. Run `gh auth login` to authenticate the GitHub CLI with your GitHub account.

> _Note: If you have an environment variable set in your shell named `GITHUB_TOKEN`,
the GitHub CLI will automatically use that._

3. If you're not already in the directory for the project which you want to open
a pull request for, `cd` there now and check with `git status` that all of your
changes are committed in your branch.

4. Run the command `gh pr create` and watch the magic unfold in front of your :eyes: !

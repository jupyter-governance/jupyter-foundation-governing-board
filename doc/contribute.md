# How to contribute to the team compass

We strongly encourage the Foundation Board to edit this documentation so that remains up-to-date and has useful information in it. The way to do so is by opening a pull request on GitHub. Here are two ways to do so:

## How to edit locally and push to GitHub

### Clone this repository

```bash
git clone https://github.com/jupyter-governance/jupyter-foundation-governing-board
cd jupyter-foundation-governing-board
```

### Install MyST

```bash
pip install -r requirements.txt
```

### Preview the documentation locally

```bash
cd doc
myst start
```

### Commit your changes and push them to the repository

```bash
git commit -m "Updating docs"
git push
```

### Open a pull request on GitHub

Finally, open a pull request to propose the changes.

## How to edit remotely using GitHub.dev

If you'd like to skip working locally, you can propose edits to the documentation directly from GitHub.
To do so, go to the following URL, which will open the repository in a VSCode instance running in the cloud:

[github.dev/jupyter-governance/jupyter-foundation-governing-board](https://github.dev/jupyter-governance/jupyter-foundation-governing-board)

Make the edits there, then use the VSCode interface to commit and push the changes to the repository.

## How to learn more about MyST

This team compass uses [the MyST Document Engine](https://mystmd.org/guide).
Visit that website for comprehensive documentation on how to author and build MyST documents like this one.

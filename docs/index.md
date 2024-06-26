# MkDocs with Codespaces

This repository demonstrates that it is possible to provide an out-of-the-box
environment for developers to maintain documentation without leaving their browsers.

Use the following steps to make changes to the documentation within a Codespace:

1. Create and checkout a branch for your changes. Do this using `git` commands in the terminal in the bottom panel, or with the Git extension in the toolbar panel on the left.
2. Make your changes and test the output by viewing the documentation in the "Simple Browser" tab or a separate browser window. The "PORTS" tab in the bottom panel will have an entry for the documentation served by this container. Note that any changes to the documentation files are reflected in the served pages immediately.
3. Create a pull request with your changes to the `main` branch.

## MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

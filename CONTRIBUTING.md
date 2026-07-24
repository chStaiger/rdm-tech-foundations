# Contributing To _Principles of Research Data Management Architecture_

**Welcome!**

_We're excited that you're here and want to contribute._

We welcome all contributions to this project via GitHub issues and pull requests. Please follow these guidelines to make sure your contributions can be easily integrated into the projects. As you start contributing, don’t forget that your ideas are more important than perfect pull requests. 

Please read through our [Code of Conduct](CODE_OF_CONDUCT.md) and make sure you familiarize yourself with its contents. We expect all of our contributors to comply with the terms specified there.

## How can I contribute?

You can contribute to the book in the following ways:
- Coming up with ideas for the book or let us know about errors or bugs, by [opening an Issue on GitHub](https://github.com/rdm-foundations/rdm-architecture/issues)
- [Directly contributing or editing content on GitHub](#pull-requests)

## Pull Requests

Changes to the book are always made through pull requests. We encourage all contributors to work on their own fork of the repository. Pull requests should be self-contained and as small as possible.

We follow the GitHub flow workflow:
- Create a feature branch on your fork.
- Commit changes.
- Open a pull request to the book's repository.
- Open a draft pull request if the work is still in progress.
- Open a pull request if you feel the work is ready for review.
- Complete the pull request template to provide information useful for reviewers.
- Iterate on changes in response to continuous integration and reviewer comments.
- Merge when all issues are addressed and changes are approved.

Try to keep changes focused. If you submit many changes at once it will be much more difficult to review.

### Markdown

_Principles of Research Data Management Architecture_ is written with **Quarto**, an open‑source scientific and technical publishing system.. You can find some guidance [here](https://quarto.org/docs/guide/).

## How to Build or View the Book locally

To render the book locally, install Quarto and then run the build commands below.

### 1. Install Quarto

You can download Quarto for Windows, macOS, or Linux from the official website:

- [Install Quarto](https://quarto.org/docs/get-started/)

To verify your installation:

```
quarto check
```

### 2. Render the Book

From the the `book/` directory run:

```
quarto render
```

This generates the book into the `_book/` directory by default.

### 3. Serve the Book Locally

For live preview with automatic rebuild on file changes:

```
quarto preview
```

This opens a local web server and refreshes the browser as you edit.

### 4. Project Structure

Quarto automatically detects the project configuration from:

- `book/_quarto.yml`  
- chapter `.qmd` files  
- assets such as figures, diagrams, and Mermaid blocks

If you add new chapters, include them in the `chapters:` list in `_quarto.yml`.

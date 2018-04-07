# README

<a href="https://www.udacity.com/">
  <img src="https://s3-us-west-1.amazonaws.com/udacity-content/rebrand/svg/logo.min.svg" width="300">
</a>

[Udacity Grow with Google](https://www.udacity.com/grow-with-google) Scholarship challenge course

[2018](https://sites.google.com/udacity.com/gwgdevscholarship/home) cohort

Intermediate Web Developer track

Collaborative projects

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Instructions](#instructions)
  - [Get started with Git and GitHub](#get-started-with-git-and-github)
  - [Fork, clone, and branch](#fork-clone-and-branch)
  - [Suggest a project](#suggest-a-project)
  - [Commit and push](#commit-and-push)
  - [Submit pull request](#submit-pull-request)

## Instructions

To initiate a collaborative project, please do the following:

### Get started with Git and GitHub

- Sign up for [GitHub](https://github.com) if you haven't already.
- Join the [Grow with Google - New England GitHub organization](https://github.com/growwithgooglema).
- Install Git
  - Mac:
    - Install [Homebrew](https://brew.sh/).
    - Install Git via Homebrew on the command line: `brew install git`
  - See the [Git Downloads page](https://git-scm.com/downloads) for more options.
  - *Why use Git?* It allows for maintenance of separate sets of the same code (branches), each with the ability to track and undo changes in high detail.
- Install the [GitHub Desktop](https://desktop.github.com/) git client.
- Install Git extensions for your text editor:
  - [Atom](https://atom.io/): [Git and GitHub support](https://github.atom.io/) built-in.
  - [Sublime Text](http://www.sublimetext.com/): [GitSavvy](https://packagecontrol.io/packages/GitSavvy)
  - [vscode](https://code.visualstudio.com/): [Git support](https://code.visualstudio.com/Docs/editor/versioncontrol) built in.
- Git and GitHub resources:
  - [Git docs](https://git-scm.com/)
  - [GitHub & Collaboration](https://www.udacity.com/course/github-collaboration--ud456) Udacity course
  - [Quick reference guide to Git and GitHub from @br3ndonland](https://github.com/br3ndonland/general/blob/master/guide-git.md)

### Fork, clone, and branch

- Fork the repository on GitHub. Forking creates a copy for your GitHub account.
- Clone the repository from the GitHub fork to your computer.
  - [GitHub Desktop can be used to clone](https://help.github.com/desktop/guides/getting-started-with-github-desktop/).
  - If cloning from the command line:

    ```bash
    cd <PATH-WHERE-YOU-WANT-THE-REPO>
    git clone git@github.com:growwithgooglema/projects.git
    ```

- Create a branch for your project.
  - Use a clear name for your branch. When submitting a pull request, the pull request name is auto-populated from the branch name.
  - Again, GitHub Desktop can be used for this.
  - Command line option:

    ```bash
    git checkout -b myspecialproject
    ```

  - The `checkout` command creates a branch and switches to the new branch.
  - The project can be further branched, for example onto a `dev` branch. The `dev` branch should be merged into the main project branch before pushing to GitHub.


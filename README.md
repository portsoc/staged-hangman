<div id="top"></div>

<!-- BRANCH TITLE -->

# Hangman in branches

<!-- TNavigation -->
<details>
  <summary>Navigate between branches</summary>  
  <nav class="menu">
    <li>Intro (this branch)</li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/0">0: Storing data in variables</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/1">1: Functions</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/2">2: NPM</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/3">3: DOM</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/4">4: Events</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/5">5: Debugging</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/6">6: Canvas</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/7">7: Modularisation</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/8">8: Server Part 1</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/9">9: Server Part 2</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/10">10: Style</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/11">11: Linting</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/12">12: Database</a></li>
    <li><a href="#https://github.com/portsoc/hangman-in-branches/tree/13">13: SVG</a></li>
  </nav>
</details>

<a href="https://github.com/portsoc/hangman-in-branches/tree/0" class="next">Next &raquo;</a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About the project</a></li>
    <li><a href="#prerequisites">Prerequisites</a>
      <ol>
        <li><a href="#on-university-machines">On University machines</a></li>
        <li><a href="#on-your-computers">On your computers</a></li>
      </ol>
    </li>
    <li>
      <a href="#cloning">Cloning</a>
      <ol>
        <li><a href="#using-git">Using Git</a></li>
        <li><a href="#using-github-cli">Using GitHub CLI</a></li>
        <li><a href="#using-github-desktop">Using GitHub Desktop</a></li>
        <li><a href="#using-visual-studio-code">Using Visual Studio Code</a></li>
      </ol>
    </li>
    <li>
      <a href="#selecting-a-branch">Selecting a branch</a>
      <ol>
        <li><a href="#using-git">Using Git</a></li>
        <li><a href="#using-github-desktop">Using GitHub Desktop</a></li>
        <li><a href="#using-visual-studio-code">Using Visual Studio Code</a></li>
      </ol>
    </li>
    <li><a href="#viewing-the-code">Viewing the code</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About the project

This repository contains a worked solution to the [2021-2022 coursework for the Application Programming module](https://docs.google.com/document/d/1cF3u2ldutHaBAzFOEsnVwfKrnPTylOrn-hAGFSDWca8/edit?usp). View the Core capabilities section within this document to see the requirements we need to satisfy.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- PREREQUISITES -->

## Prerequisites

### On University machines

1. Search for "Git GUI" and "Node.js" in [AppsAnywhere](https://appsanywhere.port.ac.uk) and launch them.

1. Launch an editor from AppsAnywhere (e.g., "Visual Studio Code" or "Atom").

### On your computers

1. Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and [Node](https://nodejs.org/en/download/).

1. Install an editor (e.g., [Visual Studio Code](https://code.visualstudio.com) or [Atom](https://atom.io)).

1. If you are new to GitHub, also install [GitHub Desktop](https://desktop.github.com) or [GitHub client](https://github.com/cli/cli).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CLONING -->

## Cloning

Don't download this repository as a zip file.
Instead, follow the instructions below to clone this repository on your machine.

### Using Git

Open the shell (Terminal on Linux/Mac or Command Prompt/PowerShell in Windows) and run:

```
git clone https://github.com/portsoc/hangman-in-branches.git
```

### Using GitHub CLI

Run the following in a shell:

```
gh repo clone portsoc/hangman-in-branches
```

### Using GitHub Desktop

While this repository is open in the browser, click the green "Code" button and then "Open with GitHub Desktop".

### Using Visual Studio Code

Follow this [instruction on how to clone a repository in Visual Studio Code](https://code.visualstudio.com/docs/editor/versioncontrol#_cloning-a-repository).

<!-- SELECTING A BRANCH -->

## Selecting a branch

This project is built in stages.
Each stage of our development is labeled with a number starting from zero.
The branch you are currently in is labeled as 'intro'.

For simplicity, we have made a branch for each stage (but be aware that this is not a conventional use of branches).

As an example, here is the link to the first branch:
[https://github.com/portsoc/hangman-in-branches/tree/0](https://github.com/portsoc/hangman-in-branches/tree/0).

To switch your copy of our code to a branch "x" (where x is a number):

### Using Git

Run the following in a shell (make sure to replace x with a branch number):

```
git checkout x
```

The following command shows you all the branches (hit <kbd>q</kbd> to exit):

```
git branch -all
```

### Using GitHub Desktop

Follow this [instruction on how to switch branches on GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#switching-between-branches).

### Using Visual Studio Code

Follow this [instruction on branches for Visual Studio Code](https://code.visualstudio.com/docs/editor/versioncontrol#_branches-and-tags).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- RUNNING AND VIEWING THE CODE -->

## Viewing the code

After selecting a branch, you can view the code in your favorite editor.
Make sure to open the hangman folder (not individual files).

Always start by reading the `README.md` file to see what were the objectives for the branch and notes on its implementation or features.

We point out that the `.gitignore` file has been automatically generated for us by GitHub on the creation of a Node repository.
Generally speaking, it helps to ignore files that you don't want to be saved in your repository (e.g., settings of the code editor, temporary files, etc.).

<p align="right">(<a href="#top">back to top</a>)</p>

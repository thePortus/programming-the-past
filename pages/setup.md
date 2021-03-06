---
title: Setting Up for this Course
author: David J. Thomas
layout: collection
permalink: /setup/
collection: top_pages
sidebar:
  nav: "sidebar_nav"
---

![Splash Image]({{ site.baseurl }}/assets/images/splash-image.png)

---

## General Course Setup

1. Install [Python3](https://python.org)
    1. Open a command line prompt and type `pip install flake8`
2. Install [Git-scm](https://git-scm.com/)
3. Install [Atom](https://atom.io)
    1. Start Atom
        1. For Windows: after starting atom open the 'File' menu and choose 'Preferences'
        2. For Mac: after starting atom open the 'Atom' menu and choose 'Preferences'
    2. Then select the 'Install' tab
    3. Search for and install the following addons (if they are not already installed)...
        1. `file-icons`
        2. `git-plus`
        3. `highlight-selected`
        4. `language-csv`
        5. `language-markdown`
        6. `linter`
        7. `linter-flake8`
        8. `platformio-ide-terminal`
        9. `tree-view-git-status`

---

## Setup Notebooks to Run Locally (VERY OPTIONAL)

1. Open the command prompt and go to where you want the new repo
2. Enter the following

```zsh

# clone the repository to your local computer
git clone https://github.com/thePortus/programming-the-past

# navigate inside the repo directory
cd programming-the-past

# install with pip (or pip3 if pip does not work)
pip install -r requirements.txt

# launch the notebooks using the new jupyter command
jupyter notebook

```

A window should launch inside your default browser allowing you to navigate and open notebooks.

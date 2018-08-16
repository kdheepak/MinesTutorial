Contents
========

- Contents
- Install git (for code version control)
- Install a programming oriented text editor
- Install text editor
- Check and Install Python

# Install `git`

* Windows
    * Download latest verison of `git` (2.8.3 x64) from <https://git-scm.com/downloads>
    * Ensure `Git Bash Here` is selected (default)
    * Ensure `Git GUI Here` is selected (default)
    * Select `Use Git from the Windows Command Prompt` (default)
    * Select `Checkout Windows-style, commit Unix-style line endings` (default)
    * Select `Use MinTTY (the default terminal of MSYS2)` (default)
    * Hit Next for remaining
* OSX
    * Download latest version of `git` (2.8.1) from <https://git-scm.com/downloads>
    System Preferences > Security & Privacy > General > Allow applications downloaded from > Anywhere
    * If using git for the first time from terminal, you will get a prompt to say GIT not installed do you want to download? Select yes (you don’t need the full Xcode)

# Install a programming oriented text editor (feel free to use your favorite)

*We will make extensive use of text files, so you will want a good quality, programmer oriented text editor. Feel free to substitute your favorite alternative editor.*

### Option 1: (RECOMMENDED)

1. Download and install [VSCode](https://code.visualstudio.com/)

### Option 2: Sublime Text (alternative)

1.  Download and install Sublime Text 3 from <https://www.sublimetext.com/3>

# Install Python

**Using Anaconda (RECOMMENDED)**

_Note: if you have previously installed Miniconda use `conda update anaconda` from the command line_

1. Download the latest version of Anaconda 3.6 x64 from <https://www.anaconda.com/download/>.
    * Windows
        * Click on Anaconda3-5.2.0-Windows-x86_64.exe and follow instructions.
        * I like to install it in `C:\anaconda3`. **This is not the default location but it'll make it easier to find your Miniconda installation later if you need it.**

    * OSX
        * Click on Anaconda3-5.2.0-MacOSX-x86_64.pkg and follow instructions
        * I like to install it in `~/anaconda3` (default).

2. Verify that conda has been installed
    * `conda --version` should result in `conda 4.5.9` or later
    * Windows : pip --version should result in something like `pip 10.0.1 from C:\anaconda3\lib\site-packages/pip (python 3.6)`
    * OSX : `pip --version` should result in something like `pip 10.0.1 from /Users/$USER/anaconda3/lib/python3.6/site-packages/pip (python 3.6)`

**Do not proceed if you do not see `anaconda` in the path string when you type `pip --version`.** If you do not see anaconda, reinstall anaconda and check if the installation was successful. If you still do not see anaconda in the path, check your `$PATH` variable to see if the directory to anaconda exists.


Footnotes
---------

[^1]: An easy way to start the terminal is to press Command-space and
    then start typing Terminal in the spotlight search box. It will most
    likely be the first hit.

[^5]: An easy way to start a command prompt under Windows 7 is through
    the Start Menu|Search for programs and files box. Type cmd and it
    should appear. Under Vista/XP, use the “Run…” option under the start
    menu and type cmd.

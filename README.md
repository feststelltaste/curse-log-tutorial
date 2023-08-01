# Curse Log Tutorial
This is a mini tutorial for teaching Python, pandas and matplotlib.

## Scenario

In the future, every human has a microchip implant that tracks uttered curses.

From a data leakage, we have the curse log (`dataset/curse_log.gz`) and a list of user profiles (`dataset/profiles.csv.gz`).

**Let's analyzed it!!**

## Prerequisites
You can choose between online environment (might be unstable) or install the needed software packaged on your own computer.

### Online environment
You can work through the tutorial here online:
* Go to / click this link: https://mybinder.org/repo/feststelltaste/curse-log-tutorial/HEAD?urlpath=tree/ (and wait a few seconds...)

### Local installation
If you want to have a local version of the data analysis environment, this section is for you!

#### Installation

##### Option 1: All-inclusive package Anaconda3 (recommended)
* Download and install Anaconda3 (version with Python 3.x): https://www.anaconda.com/download

##### Option 2: Manual installation of Python and pandas

* Download the following software package:
   * Python 3: https://www.python.org/downloads/
   * pip (if not already installed with Python 3): https://pip.pypa.io/en/stable/installation/
* Then, use the `pip` command to install the following Python packages
   * Jupyter Notebook: `python3 -m pip install --upgrade pandas`
   * pandas: `python3 -m pip install --upgrade pandas`

#### Download the tutorial for local installation

You need to download the tutorial files:
1. Click here to download the files as a ZIP file: https://github.com/feststelltaste/curse-log-tutorial/archive/refs/heads/master.zip
2. Unzip the files in a folder of your choice
3. Copy the file path of this folder into the clipboard (for the next step)

#### Open Jupyter notebook

1. Open the application named "Anaconda Prompt". A so called "command line" will open where you can enter commands later on.
2. Go to the tutorial directory
   * you can do this by copying the directory path where you've installed (already done in the previous step)
   * then type `cd ` (with a whitespace at the end) on the command line, paste the file path from your clipboard after this and press the enter key. This should have take you to the tutorial directory.
   * type `jupyter notebook` and press the enter key. This starts the Jupyter notebook environment. After this has finished, a URL starting with `http://`is shown. Please hold the `Ctrl` button and press with your mouse cursor on the link. A browser window will open and you see a screen like this:
 
    <img width="491" alt="image" src="https://github.com/feststelltaste/curse-log-tutorial/assets/1470822/b8b26ddd-40e9-4fa2-83fb-8276b8e9c75e">
 

## Open the tutorial notebook
After starting the environment, you see the directory with the tutorial's content.

There are two versions of the tutorial notebook:
* `Curse Log Analysis Solution.ipynb`: this version contains the solutions if you can not come up with your own
* `Curse Log Analysis.ipynb`: this version is the tutorial with blanks that you have to fill in by your own

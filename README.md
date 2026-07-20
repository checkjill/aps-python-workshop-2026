# Python in Action: AI Integration and Applied Case Studies in Plant Pathology

Move your Python skills from theory to practice while tackling real plant pathology challenges. You'll work with case studies covering disease detection, genomic analysis, and pathogen modeling, all while learning how to harness AI to speed up coding workflows. Master prompt strategies, troubleshoot AI-generated code, and ensure your analyses are reproducible and accurate. Whether you're an experienced coder or just starting, you'll leave with reusable scripts, practical techniques, and new approaches to apply directly in your research projects.

Presented at the 2026 National American Phytopathological Society conference meeting

Authors: Jani Baruah, Jill Check, Cole Regnier, Santosh Sanjel

## APS Python Workshop - Environment Setup Guide

Welcome to the APS Python Workshop!

Please complete the setup below before attending the workshop. This will ensure that everyone can start the exercises immediately.

## Overview

By the end of this tutorial you will have: 

- Visual Studio Code (VS Code) installed
- Python installed
- Python extension installed in VS Code
- Git installed
- Workshop repository downloaded
- Verified that everything works corretly

## Step 1 - Install Visual Code Code (VS Code)

Visual Studio Code (VS Code) will be our integrated develoment environment (IDE) during the workshop.

**Download VS Code**

Go to:

https://code.visualstudio.com

and download the version for your operating system:

- Windows
- macOS
- Linux

**Install VS Code**

Follow the installation wizard using the default settings.
After installation, open VS Code.

**Expected Result**

You should see a screen similat to this:

[IMAGE]

Screenshot showing:
- VS Code opened for the first time
- Welcome page

## Step 2 - Install Python

Python is the programming language used throughout the workshop.

**Download Python**

Go to:

https://www.python.org/downloads

Download the latest stable Python release.

**Windows Users (Important)**

During installation, make sure to check:

- Add Python to PATH

Before clicking "install Now".

[IMAGE]

**Verify installation**

Open:

Windows:

Commad Prompt

macOS/Linux:

Terminal

**Run:**

```
python --version
```

or 

```
python3 --version
```

**Expected output**

```
Python 3.x.x
```

[IMAGE]

## Step 3 - Install the Python Extension in VS Code

Open VS Code.

Click the Extensions icon on the left sidebar.

**Search for:**

Python

Install the extension published by Microsft.

**Verify installation**

After installation, you should see:

Python (Microsoft)

with the label:

Installed

[IMAGE]

## Step 4 - Install Git

Git is used to download and manage workshop materials

**Download Git**

Go to:

https://git-scm.com/downloads

Download the appropriate version for your operating system.

**Install Git**

Use the default installation settings.

**Verify installation**

**Open a terminal and run:**

```
git --version
```

**Expected output**

```
git version X.X.X
```

[IMAGE]

## Step 5 - Clone the Workshop Repository

Open:

**Windows**

Command Prompt

or 

Git Bash

**macOS/Linux**

Terminal

Navigate to the folder where you want the workshop materials stored.

**Example**

```
cd Documents
```

**Clone the repository:**

```
git clone https://github.com/WORKSHOP-ORGANIZATION/WORKSHOP-REPOSITORY.git
```

Replace the URL above with the official workshop repository.

**Move into the Repository**

```
cd WORKSHOP-REPOSITORY
```

**Verify**

You should see files such as:

```
README.md
modules/
data/
notebooks/
```

[IMAGE]

**Step 6 - Open the Workshop Folder in VS Code**

Open VS Code.

**Click:**

File → Open Folder

Select the repository you just downloaded.

[IMAGE]

**Step 7 - Select the Python Interpreter**

Inside VS Code:

**Press:**

```
Ctrl + Shift + P
```

(or Command + Shift + P on macOS)

**Search:**

Python: Select Interpreter

Select the installed Python version.

[IMAGE]

## Step 8 - Run a Test Script

Create a new file called:

```
test_setup.py
```

**Copy and paste:**

print("Hello APS Workshop!")

```
import sys

print("Python version:")
print(sys.version)
```

Save this file.

**Execute**

Open a terminal inside VS Code.

**Run:**

```
python test_setup.py
```

**Expected output:**

```
Hello APS Workshop!
```

```
Python version:
3.x.x
```

[IMAGE]

## Step 9 - Test Package Installation

**Run:**

```
pip install pandas numpy matplotlib
```

**Verify**

Open Python:

python

and run:

```
import pandas
import numpy
import matplotlib
```

```
print("Packages installed successfully!")
```

Expected output:

```
Packages installed successfully!
```

Exit Python:

```
exit()
```

[IMAGE]

## Final Checklist

Before attending the workshop, verify that all items below are complete:

- VS Code installed
- Python installed
- Python Extension Installed
- Git Installed
- Repository Cloned
- Repository Opened in VS Code
- Test Script Executed
- Python Packages installed

## Need help?

If you encounter any issues, please contact the workshop organizers before the event or bring your issues to the next virtual meeting.

We look forward to seeing you at the APS Python Workshop!

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

## Step 1 - Install Visual Studio Code (VS Code)

First, we need to install `Visual Studio Code (VS Code)`, which will be our integrated development environment (IDE) during the workshop.

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

<img width="1918" height="1027" alt="image" src="https://github.com/user-attachments/assets/086bdceb-fa5c-4809-bf7f-544ceb683f48" />

Screenshot showing:
- VS Code opened for the first time
- Welcome page

## Step 2 - Install Python

After installing our IDE (VS Code), we will install the programming language.

Python is the programming language used throughout the workshop.

**Download Python**

Go to:

https://www.python.org/downloads

Download the latest stable Python release.

You need to click on your operating system (Windows, macOS, or Linux) inside the red box indicated by the arrow.

<img width="1835" height="905" alt="python_download" src="https://github.com/user-attachments/assets/23756eba-1e45-4eff-b16d-7f9c5555ea8e" />

**For Windows:**

<img width="1569" height="905" alt="windows" src="https://github.com/user-attachments/assets/b0310e07-e0e5-497d-8e34-a2eb1dc8f448" />

**For Linux:**

<img width="1584" height="905" alt="Linux" src="https://github.com/user-attachments/assets/174f9cfa-eab8-4346-95b9-fae852bb3035" />

**For MacOS:**

<img width="1569" height="905" alt="macOS" src="https://github.com/user-attachments/assets/c4a88c10-429a-4b46-81cd-170abd422815" />

**Windows Users (Important)**

During installation, make sure to check:

- Add Python to PATH

Before clicking "install Now".

<img width="649" height="408" alt="install_python" src="https://github.com/user-attachments/assets/1b3b84ff-dc74-4f95-92b5-dd9be535d575" />

**Verify installation**

Windows:

Open the `Commad Prompt`

macOS/Linux:

Open the `Terminal`

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
Python 3.14.6
```
<img width="1105" height="619" alt="prompt" src="https://github.com/user-attachments/assets/fa53acc5-7f5c-4196-bc3a-430aad3bd08c" />

## Step 3 - Install the Python Extension in VS Code

Open VS Code.

Click the Extensions icon on the left sidebar indicated by the arrow.

<img width="1885" height="546" alt="extensions" src="https://github.com/user-attachments/assets/5ef09a5f-d6bf-4c89-b29a-4cf4c974fa3f" />

**Search for:**

Python writing on the left sidebar as indicated by the first red box above.

and

Install the extension published by Microsft as indicated by the second red box on the left.

<img width="1918" height="1148" alt="python_extension" src="https://github.com/user-attachments/assets/cd69e0eb-4c62-43fd-92ff-757e6f09e6ee" />

**Verify installation**

After installation, you should see:

`Python (Microsoft)` with the label `Installed` as indicated by the red box on the left.

<img width="1915" height="1139" alt="python_installed_extension" src="https://github.com/user-attachments/assets/3971792e-84ca-4e76-9df7-3992ac735404" />

## Step 4 - Install Git

Git is used to download and manage workshop materials

**Download Git**

Go to:

https://git-scm.com/downloads

Download the appropriate version for your operating system.

**For Windows:**

<img width="1149" height="932" alt="git_windows" src="https://github.com/user-attachments/assets/d71b348a-dd70-4553-8772-2ea81751fc7a" />

**For macOS:**

<img width="1015" height="837" alt="git_macOS" src="https://github.com/user-attachments/assets/e38c0391-93fa-40f1-bb28-5aea3f2a9dc8" />

**For Linux:**

<img width="971" height="1275" alt="git_linux" src="https://github.com/user-attachments/assets/51d1de8c-2774-4d96-b47d-ac5c902448e6" />

**Install Git**

Use the default installation settings.

<img width="592" height="460" alt="git_install" src="https://github.com/user-attachments/assets/1cc243f1-8578-4665-bad4-35599bded24b" />

**Verify installation**

**Open a `Terminal` or `Command Prompt` and run:**

```
git --version
```

**Expected output**

```
git version 2.55.0.windows.3
```
<img width="1108" height="614" alt="git_prompt" src="https://github.com/user-attachments/assets/105c76d5-f63e-4439-af2d-99917e016b31" />

## Step 5 - Clone the Workshop Repository

Open the `Command Prompt`, `Terminal`, or `Git Bash` on your compute.

Navigate to the folder where you want the workshop materials stored.

**Example**

This way, I will store the workshop materials directly in my `Documents` folder. However, you can choose any path you like.

```
cd Documents
```
Next, clone the workshop repository to the `Documents` folder on your computer.

**Clone the repository:**

```
git clone https://github.com/checkjill/aps-python-workshop-2026.git
```
You will see something similar to this:

<img width="1108" height="617" alt="git_terminal" src="https://github.com/user-attachments/assets/1ab0f111-2c04-4221-9624-bf02bd9adc48" />

Next, after those two processes, you will have a cloned repository on your computer, similar to this:

<img width="1919" height="194" alt="git_documents" src="https://github.com/user-attachments/assets/20111326-4c4c-4443-bf4c-060de8b5762e" />

## Step 6 - Open the Workshop Folder in VS Code

Open VS Code.

**Click:**

File → Open Folder

<img width="1918" height="1148" alt="open_folder" src="https://github.com/user-attachments/assets/c26c980b-7a3a-4820-93f8-fc6e73008d1f" />

Select the repository you just downloaded.

<img width="939" height="587" alt="repository_vscode" src="https://github.com/user-attachments/assets/6b3bb53f-787a-4860-8201-6ba73cf7e4ad" />

After you select the workshop folder, you will have all the documents on your VS Code.

<img width="1910" height="1148" alt="folder_vscode" src="https://github.com/user-attachments/assets/01906db8-5f86-4bc4-93cf-5d1884173512" />

## Step 7 - Select the Python Interpreter

Now, we need to select the python interpreter that will support our analysis on VS Code.

Inside VS Code:

**Press:**

`Ctrl + Shift + P`

(or Command + Shift + P on macOS)

**Search:**

```
Python: Select Interpreter
```

<img width="1912" height="1145" alt="python_interpreter" src="https://github.com/user-attachments/assets/abfb8001-48e5-4c95-8378-d59aca79f889" />

Select the installed Python version

<img width="1910" height="1151" alt="python_version_inter" src="https://github.com/user-attachments/assets/095cc827-dcf4-4acd-adf8-fcf22fef602a" />

## Step 8 - Run a Test Script

After completing these steps, we need to test whether the program is working correctly. To do this, we need to create a `.venv` environment to run the tests.

First, we need to open a terminal in VS Code to perform a few tasks. To do this, select the terminal option at the top and click `New Terminal`.

<img width="1915" height="1146" alt="new_terminal" src="https://github.com/user-attachments/assets/f30017a3-7c80-4539-bc07-5ffe1fd841ff" />

With the terminal created, let's activate our `.venv` environment using the terminal:

**For Windows:**

```
py -3.14 -m venv .venv

```
**For macOS or Linux:**

```
py -3.14 -m venv .venv

```
After copying and pasting the code above, you need to press the Enter key on your computer, and you will see something like what is shown below—a command line starting with `(.venv)`.

<img width="1913" height="1149" alt="venv" src="https://github.com/user-attachments/assets/9ab2a15b-a013-44ce-bcc8-fce0d5ece1b9" />

Now, let's verify if the Python version in our `(.venv)` is 3.14.3. To do this, you need to copy, paste, and press the Enter key in the terminal.

**For Windows:**

```
python --version

```

**For macOS or Linux:**

```
python --version

```

You will see something like what is shown below - `Python 3.14.3`.

<img width="1918" height="1151" alt="python_version" src="https://github.com/user-attachments/assets/4fcfa0f8-6139-4787-bc1f-c4c9e1479b7f" />

Alright, now that the environment is set up, we will install the package we will be using in the workshop.

To do this, we can run the code below, which will allow us to install all the requirements.

**Requirements:**

```
python -m pip install -r requirements.txt
```

<img width="1915" height="1150" alt="requirements" src="https://github.com/user-attachments/assets/c9888bf2-e8d4-4318-9170-e76835a73308" />

Now we have the Python interpreter, the created environment, and the installed packages.

Finally, let's run some tests to familiarize ourselves with the platform.

You need to install the Jupyter extension to run the test script in VS Code. To do this, search for `Jupyter` in the extensions section, just as you did to install the Python extension in step 3. Then, select the first option and click `Install`, as shown in the image below.

<img width="1919" height="1148" alt="jupyter" src="https://github.com/user-attachments/assets/c438295e-56b6-46de-8e6b-fd25d3774889" />

Next, open the `installation_test.ipynb` file on the left and select the kernel, which is a Python process responsible for executing the code in this notebook.

First, click on `Python 3.14.3`, as highlighted by the red box; then, select the `Select Another Kernel..` option inside the green box.

<img width="1919" height="1146" alt="kernel1" src="https://github.com/user-attachments/assets/7ceb0379-1051-4d0f-997b-62c9341e2a25" />

Click on `Python Environments..`

<img width="1914" height="1144" alt="kernel2" src="https://github.com/user-attachments/assets/f622e2c7-5bc0-400e-aa1f-7ff995c63f5c" />

Select an option similar to one of these options.

- `.venv (Python 3.14.3)`
- `.venv (3.14.3.final.0) (Python 3.14.3)`
- - `APS Workshop (.venv`

<img width="1913" height="1146" alt="kernel3" src="https://github.com/user-attachments/assets/66049e00-a922-4bf1-8abf-ffc017d0e4b2" />

After that, you will see a new label on the right side, as highlighted by the red box.

<img width="1911" height="1147" alt="kernel4" src="https://github.com/user-attachments/assets/623913c3-0ba5-465f-b6a9-75120974d76e" />

Done.

Now, we can explore the platform and understand some interesting aspects.

Above, highlighted by the red box, you can see an available support option to 

`Generate` - Use AI to generate or improve code.
`+ Code` - Add a new code cell.
`+ Markdown` - Add a new text cell for notes and instructions.
`Run All` - Run all notebook cells from top to bottom.
`Restart` - Restart the Python kernel and clear variables from memory.
`Clear All Outputs` - Remove all cell outputs while keeping the code.
`Jupyter Variables` - View variables currently stored in memory.
`Outline` - Display a navigation panel for notebook sections.

<img width="1916" height="1150" alt="bar_jupyter" src="https://github.com/user-attachments/assets/e2d6ba39-cf90-4135-96f8-74b78e80e402" />

<img width="1916" height="1148" alt="run_jupyter" src="https://github.com/user-attachments/assets/c1ab57b7-ee64-4a2b-b27c-5037783f1171" />

## Final Checklist

Before attending the workshop, verify that all items below are complete:

- VS Code installed
- Python installed
- Python Extension Installed
- Git Installed
- Repository Cloned
- Repository Opened in VS Code
- Python Packages installed
- Test Script Executed

## Do you need help?

If you encounter any issues, please contact the workshop organizers before the event or bring your issues to the next virtual meeting.

We look forward to seeing you at the APS Python Workshop!

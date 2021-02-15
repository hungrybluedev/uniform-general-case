# Prerequisites

1. Git - 2.27 or higher
2. Python - 3.8 or higher
3. Pip (should be included with Python 3 by default)

Install the `virtualenv` package from pip and make sure it is available globally from the command-line.

# Initialization

```bash
# Navigate to a suitable directory
cd path/to/directory

# Obtain the source code from Github
git clone https://github.com/hungrybluedev/uniform-general-case.git

# Create a virtual environment
virtualenv venv

# Activate the environment
# 1. For Windows (powershell recommended)
venv/Scripts/activate
# 2. For Linux/MacOS
. venv/bin/activate

# Install all dependencies
pip install -r requirements.txt
```

# Regular Usage

When starting a new session, remember to activate the virtual environment as shown in the previous step (using the activate script). Then type `jupyter notebook`. A new browser tab should open containing your notebook.

# More Information

Detailed instructions can be found on this page: [Setting up Jupyter](https://hungrybluedev.in/article/setting-up-jupyter/).

In case of any doubts, contact me through the channels mentioned in this page: [Contact Me](https://hungrybluedev.in/contact/)

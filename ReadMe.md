# projectDentAI

## Building Development Environment (MacOS and Linux)

```
# Install home brew package manager
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# update the brew
brew update
brew upgrade

# prepare python development environment
brew install python@3.9
python3.9 -m venv venv
source venv/bin/activate
pip install --upgrade pip

# Clone the repo
git clone git@github.com:DeNovaLux/projectDentAI.git
pip install -r requirements.txt
```

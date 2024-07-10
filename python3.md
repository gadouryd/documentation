reference: https://opensource.com/article/19/5/python-3-default-mac

# Install pyenv
```brew install pyenv```

# Install Python
```pyenv install 3.9.9```

# Set global default
```
pyenv global 3.9.9
pyenv version
```

# Update path
```echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.zshrc```

# Alias Python
```
brew info python
echo "alias python=/opt/homebrew/bin/python3" >> ~/.zshrc
echo "alias python3=/opt/homebrew/bin/python3" >> ~/.zshrc
```
# Update using Homebrew
```brew update && brew upgrade python```

# Alias Pip
```
echo "pip=/opt/homebrew/bin/pip3" >> ~/.zshrc
echo "pip3=/opt/homebrew/bin/pip3" >> ~/.zshrc
```


#venv
python3 -m venv env
python -m venv env


python3 -m venv path/to/venv
    source path/to/venv/bin/activate
    python3 -m pip install xyz

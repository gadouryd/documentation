
# Install pyenv
```brew install pyenv```

# Install Python
```pyenv install 3.9.9```

# Set global default
```pyenv global 3.9.9
pyenv version```

# Update path
```echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.zshrc```

# Alias Python
```echo "alias python=/opt/homebrew/bin/python3" >> ~/.zshrc
echo "alias python3=/opt/homebrew/bin/python3" >> ~/.zshrc```

#venv
python3 -m venv env
python -m venv env

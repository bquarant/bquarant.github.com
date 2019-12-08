## Python for Data Stuff
## 15 November 2019
## Brian Quaranto MD

# Fixing Python environment on macOS Catalina
$ brew install pyenv
$ pyenv install 3.8.0
$ pyenv global 3.8.0
$ pyenv version
$ echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.zshrc
$ which python
## old path
$ exec $0
$ which python
## new path

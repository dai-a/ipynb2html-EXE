# ipynb2html EXE

# os
macOS Mojave 10.14.5

# env and run

## env
PYTHON_CONFIGURE_OPTS="--enable-framework" pyenv install 3.7.4
pyenv global 3.7.4
pip install -U pip
pip install pyinstaller
pip install jupyter

## run
pyinstaller ipynb2html.py --onefile
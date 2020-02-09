# ipynb2html EXE

# os
macOS Mojave 10.14.5

# env and run

## env
PYTHON_CONFIGURE_OPTS="--enable-framework" pyenv install 3.7.4<br>
pyenv global 3.7.4<br>
pip install -U pip<br>
pip install pyinstaller<br>
pip install jupyter<br>

## run
pyinstaller ipynb2html.py --onefile
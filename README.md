# nn-digit_recognition

# Getting Started

### Cloning the Repository

    git clone https://github.com/jkmathilda/nn-digit_recognition.git

### Setting up a Virtual Environment

    cd ./nn-digit_recognition

    pyenv versions

    pyenv local 3.11.6

    echo '.env'  >> .gitignore
    echo '.venv' >> .gitignore

    ls -la

    python -m venv .venv        # create a new virtual environment

    source .venv/bin/activate   # Activate the virtual environment

    python -V                   # Check a python version

### Install the required dependencies

    pip list

    pip install -r requirements.txt

    pip freeze | tee requirements.txt.detail
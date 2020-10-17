# No more shitty burocracy

Repo in an attempt to create a script in Python that extracts data from PDF format bills and writes it in an Excel sheet.

### End-objective:

> Simplify the extraction of data from **`DAETSIINF`** bills.

## Installation:

1. Clone this repo
    - SSH:  
    ```bash
    $ git clone git@github.com:DA-ETSIINF:no-more-shitty-burocracy
    ```

    - HTTPS:  
    ```bash
    $ git clone https://github.com://DA-ETSIINF:no-more-shitty-burocracy
    ```

2. Install [python](https://www.python.org/downloads/) on your computer:
    - Linux:
    ```bash
    $ sudo apt install python3; sudo apt install python3-pip
    ```
    - MacOS (Homebrew):
    ```zsh
    $ brew install python3; brew install python3-pip
    ```

3. Create virtual environment:  
    ```bash
    $ python -m venv .venv
    ```

4. Change source to use the environment: 
    ```bash
    $ source .venv/bin/activate
    ```

5. Install requirements:
    ```bash
    $ pip install -r requirements.txt
    ```
6. And you're ready to go!
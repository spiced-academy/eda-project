# EDA Project

The project took house sale data from a database hosted by Spiced Academy. This was our first individual project during their 3 month Data Science Bootcamp. The assignment.md outlines the task and the deliverables. I chose the client Erin Robinson, a buyer who wishes to invest in poor neighborhoods, involved in buying & selling but in a socially responsible manner in that she wishes to recoup her costs and make a little profit.

## Data

The PostgreSQL database was inspected using DBeaver and the dataset extracted using sqlalchemy.

The dataset for the house_client.ipynb notebook is stored in the `data.zip` file. To unzip the data folder directly in the terminal run

```sh
unzip data.zip
```

## Presentation

To update the presentation run

```sh
jupyter nbconvert house_client.ipynb --to slides
```

## Requirements

- pyenv
- python==3.11.3

## Set up your Environment

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the contained notebooks.

### **`macOS`** type the following commands : 


- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `BASH` CLI :
    ```
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

    ```Bash
    python.exe -m pip install --upgrade pip
    ```


# Pokémon Trainer Club Account Generator

# Getting started
1. Install [Python3](https://www.python.org/downloads/) :snake:
2. Install [Jupyter with pip](https://jupyter.org/install)
3. Download this repository
4. Create a virtual environment with the following command
```sh
python -m venv env
```
5. [Activate](https://docs.python.org/3/tutorial/venv.html) the virtual environment
6. Install the jupyter kernel in your virtual environment ([guide](https://janakiev.com/blog/jupyter-virtual-envs/))
```sh
pip install ipykernel
```
7. Add the environment to Jupyter
```sh
python -m ipykernel install --name=PoGOAccounts
```
8. Install [Geckodriver](https://github.com/mozilla/geckodriver)


# Usage
1. Start Jupyter with this command: `jupyter notebook`
2. Open the notebook (`account_generator.ipynb`) in the browser window that has been opened
3. Run the first cell (`CTRL` + `ENTER`) of the notebook
4. A new Firefox browser window should appear, filling everything and generating a new e-mail
5. After the first cell has been fully executed, complete the CAPTCHA on the PTC page and confirm the input
6. Go to the second tab and wait for the confirmation email to arrive
7. Verify your account
8. Open Pokémon Go on your device
9. Select "New Player" in the opening screen
10. Enter your credentials (they will be saved in the file `accounts.csv` as well as being displayed in the notebook)
10. Rinse and repeat :coffee:
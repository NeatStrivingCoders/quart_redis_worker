# QuartRedisWorker

This project gives a template for a distributed quart redis worker architecture.

## Getting Started

Follow these instructions to get the project running for development purposes.
### Prerequisites

1. Make sure you installed [pyenv](https://github.com/pyenv/pyenv-installer) to manage your python versions.
Add the following lines to your .bashrc or .bash_profile.
    ```
    export PYENV_ROOT="$HOME/.pyenv"
    export PATH="$PYENV_ROOT/bin:$PATH"
    eval "$(pyenv init -)"
    ```
   The python version in your terminal is now set via pyenv.
   
2. Install Python 3.7.7 for the project.
    ```
    pyenv install 3.7.7.
    ```
   Switch into the root directory of the repository and type:
    ```
    pyenv local 3.7.7
    ```

3. Install pipenv to manage package dependencies and create a virtual environment with it.
    ```commandline
    pip install pipenv
    pipenv shell
    ```

### Installing

Install all necessary packages with the help of pipenv, by simply executing:
```
pipenv install
```
It reads out package dependencies from the "Pipfile" and gets the correct versions via hash values.

If you want to install a new package install it via ```pipenv install <packageName>```. It than will be tracked
in the "Pipfile".

Visualize package dependencies via ```pipenv graph```.

## Running the tests

### Break down into end to end tests

tbd

### And coding style tests

tbd

## API Documentation

tbd

## Deployment

tbd

## Built With
 tbd

## Authors

Sebastian Schmidt <br>
E-Mail:
[sebastian.schmidt.business@gmail.com](mailto:sebastian.schmidt.business@gmail.com)<br>


Michael Gebauer <br> 
E-Mail:
[gebauerm23@gmail.com](mailto:gebauerm23@gmail.com)

## Acknowledgments


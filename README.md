# Rasa MLOPs example

Example repro that accompanies the blog [MLOps for developing Conversational AI in Rasa, using DVC and CML]().

The Rasa component here was created by running `rasa init`. No substantive changes have been made.
To Create the dvc repo, we ran the command `dvc init`.

## Getting started

To create the virtual environment required to run the code, run `make virtualenv`.

To activate the virtual environment run: `source ./build/virtualenv/bin/activate`.

To recreate the workflow run: `dvc repro`.


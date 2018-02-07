# defogger

## Setup
 - Install matplotlib
   - On Ubuntu: `sudo apt install python3-matplotlib`
   - `https://matplotlib.org/users/installing.html`
 - Create a virtual environment using: `virtualenv venv --python=python3`
 - Install pip3 requirements using: `pip install -r requirements.txt`

## Development
 - When adding new requirements, list direct requirements in `requirements.in` and run `pip-compile --output-file requirements.txt requirements.in` to document all direct and indirect requirements.

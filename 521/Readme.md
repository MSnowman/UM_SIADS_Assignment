# UM SIADS 521 Assignment 3

How to run the notebook

## Setup Instructions

Clone the repository and install the dependencies in a virtual environment:

```bash
# 1. Clone the repository
git clone https://github.com/MSnowman/UM_SIADS_Assignment.git
cd your-repo-name

# 2. Create and activate a virtual environment
python3.13 -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

# 3. Install requirements
pip install -r requirements.txt

#3.5 Set up environment for jupyter
python -m ipykernel install --user --name=venv313 --display-name "Python 3.13 (venv)"

# 4. Launch Jupyter Notebook
jupyter notebook

# 5. Set the kernel environment
Select Python 3.13 (venv)

# 6 Run the Notebook
Run the notebook and the Dashboard will open locally at the end

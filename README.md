# Desktop-Assistant-using-python

# How to run?

# STEPS:

 Clone the repository
Project repo: https://github.com/

# STEP 01- Create a conda environment after opening the repository

conda create -n dekstop python=3.10 -y

conda activate desktop

# STEP 02- install the requirement

pip install -r requirements.txt

# Create a .env file in the root directory and add your GOOGLE_API_KEY credentials as follows:

GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

# Finally run the following command
streamlit run app.py

# Now,
open up localhost:

# Techstack Used:
- Python
- Gemini API
- Streamlit
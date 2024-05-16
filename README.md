{\rtf1\ansi\ansicpg1252\cocoartf2639
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Taxi Trip EDA GUI\
\
## Project Description\
\
This project is a graphical user interface (GUI) for performing exploratory data analysis (EDA) on a taxi trip dataset. The application allows users to load a dataset, visualize data, and perform various EDA tasks using an intuitive GUI.\
\
## Features\
\
- Load and display a taxi trip dataset\
- Visualize data through various charts and plots\
- Perform EDA tasks such as data filtering, aggregation, and statistical analysis\
\
## Setup Instructions\
\
### Prerequisites\
\
- Anaconda or Miniconda installed\
- Python 3.9\
\
### Environment Setup\
\
1. **Clone the Repository:**\
\
    ```sh\
    git clone https://github.com/yourusername/taxi_EDA_GUI.git\
    cd taxi_EDA_GUI\
    ```\
\
2. **Create and Activate the Conda Environment:**\
\
    ```sh\
    conda env create -f environment.yml\
    conda activate taxi_eda_env\
    ```\
\
3. **Install the Required Packages:**\
\
    Ensure you have the necessary Python packages installed:\
\
    ```sh\
    pip install -r requirements.txt\
    ```\
\
4. **Run the Application:**\
\
    ```sh\
    python gui_script.py\
    ```\
\
### Additional Setup for Missing Dependencies\
\
If you encounter issues with missing dependencies (`pyarrow`, `fastparquet`), ensure they are included in your `requirements.txt` and `environment.yml`.\
\
Add the following lines to `requirements.txt` if not already present:\
\
```plaintext\
fastparquet==0.8.1\
pyarrow==12.0.1\
\
Owner: Mariam Dolidze }
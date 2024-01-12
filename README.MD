# README - Setup Guide for Virtual Environment

## Purpose of the Repository
This repository is dedicated to replicating the results displayed in our study currently under revision for publication in a peer-reviewed journal. It includes all necessary Python scripts, data processing tools, and documentation needed to reproduce the findings as presented in our submission. Our goal is to facilitate transparency, validation, and further research by providing a comprehensive and accessible resource for replicating our study's results.

## Introduction
This guide provides step-by-step instructions to set up the virtual environment required for running the Python analysis code. The code utilizes several libraries including `matplotlib`, `numpy`, `pandas`, `mpl_toolkits.axes_grid1`, `seaborn`, and `scipy`.

## Prerequisites
- Python (latest stable release recommended)
- Git (for version control, optional)
- Command Line Interface (CLI) such as Terminal on MacOS/Linux or Command Prompt/Powershell on Windows.

## Setting Up the Virtual Environment

### 1. Clone the Repository (Optional)
If the code is hosted on a version control platform like GitHub:
```bash
git clone [URL of the Repository]
cd [Repository Name]
```

### 2. Creating a Virtual Environment
Navigate to the project directory and create a virtual environment.
```bash
# On MacOS/Linux
python3 -m venv venv

# On Windows
python -m venv venv
```

### 3. Activating the Virtual Environment
Activate the created virtual environment.
```bash
# On MacOS/Linux
source venv/bin/activate

# On Windows
venv\Scripts\activate
```

### 4. Installing Dependencies
Install the required libraries using the provided `requirements.txt` or `environment.yml`.
```bash
pip install -r requirements.txt
```

### 5. Deactivating the Virtual Environment
After running the code, you can deactivate the virtual environment.
```bash
deactivate
```

## Troubleshooting
If you encounter any issues with library versions or compatibility, ensure you're using the Python version recommended and the correct versions of the libraries as specified in `requirements.txt`.

## Additional Notes
- Ensure that your data files, if any, are placed in the designated directories as per the project's file structure.
- For any specific configurations or environment variables, refer to the project's documentation.
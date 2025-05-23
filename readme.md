# Setting Up the Environment

## Step 1: Create a Conda Environment
Run the following command to create a Conda environment with Python 3.11.9:
```bash
conda create --name gesture_env python=3.11.9
```

Activate the Conda environment:
```bash
conda activate gesture_env
```

## Step 2: Install Required Packages
Create a `requirements.txt` file with the following content:
```plaintext
opencv-python
mediapipe
autopy
```

Install the dependencies using pip within the Conda environment:
```bash
pip install -r requirements.txt
```

## Step 3: Verify Installation
Run the following command to verify the packages are installed:
```bash
pip list
```

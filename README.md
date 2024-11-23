 #StrykerAI2024

### Repository for the 2024 Stryker AI in Orthopaedics Hackathon

This project aims to classify orthopedic patients into two classes (**normal** and **abnormal**) based on six biomechanical and image-derived predictors using a machine-learning algorithm. Additionally, the project involves describing the steps to successfully deploy this solution into an orthopaedic outpatient clinical setting. The bonus challenge extends upon this by catagorisng patients into three classes (**normal**, **herniated disc** and **spondylolisthesis**)

---

## Team Members
- **Yusuf Salim**
- **GuruVignesh Balaji**
- **Rohan Reddy**
- **Mohamed Jama**

---
### Repository breakdown

The repository consists of a `requirements.txt` text file and a `Stryker_AI_Hackathon_notebook.ipynb` jupyter notebook file.  
`requirements.txt` contains all the required libraries and dependencies for the project. 
`Stryker_AI_Hackathon_notebook.ipynb` is the notebook containing our teams submission code.

## Instructions for Setup

#### **Option 1: Using a Virtual Environment (Recommended)**

Venv setup on vscode:
1) Go to terminal
2) Enter/create a folder for this project
3) Enter command: python -m venv env_name
4) This will create a folder in your current folder with name env_name
5) To activate venv enter command:  .\env_name\Scripts\activate 
6) Install required libraries with command: pip install requirements.txt (or \path\to\requirements.txt)
7) If unable to activate Venv enter command: Get- Execution Policy
8) If this returns restricted you will need to enter command: Set -ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
9) Step 8 will need to be done each time before activating Venv (some systems prevent script execution by default and Step 8 overrides this for a single session)
10) Once Venv is activated open notebook on vscode and select the Venv as your kernal
11) Code as normal! :)
12) Deactive Venv using the command: deactivate, in the terminal

#### **Option 2: Pip Install requirements individually and use either Vscode/ Jupyter Notebook or Google Collab **
This method is not recommended due to the inability to consistently control library versions across multiple instances of the code.  
Copy each of the libraries from requirements.txt, setup a new cell on the notebook and pip install each library individually.


    
## Dataset License
The dataset used in this project is licensed under a **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.
- DOI: [10.24432/C5K89B](https://doi.org/10.24432/C5K89B)
- License Details: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

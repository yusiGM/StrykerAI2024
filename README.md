# StrykerAI2024
Repository for the 2024 Stryker AI in Orthopaedics hackathon.
Team consists of Yusuf Salim, GuruVignesh Balji, Rohan Reddy and Mohamed Jama.

Required libraries are in requirements.txt
If on Jupyter notebook either pip install each of them individually or setup a Virtual Enviroment (Venv)(recommended). 
The latter is recommended to better manage python dependencies, avoid conflicts and make the enviroment consistent across multiple systems.

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
12) Deactive Venv using the command deactivate in the terminal

    
## Dataset License
The dataset used in this project is licensed under a **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.
- DOI: [10.24432/C5K89B](https://doi.org/10.24432/C5K89B)
- License Details: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

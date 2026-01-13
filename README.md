# CCDS Tech for Good Hackathon 2026

Welcome to the CCDS Tech for Good Hackathon 2026! This repository provides the foundation for building impactful solutions using Beautiful Soup, Pygame and LangChain!

## Before You Start
Make sure you have the following installed on your computer:

- **[Visual Studio Code](https://code.visualstudio.com/download/)** (VS Code)
- **[Python](https://www.python.org/downloads/)** (version 3.10 or later)
- **[Git](https://git-scm.com/install/)** 
- **[uv](https://docs.astral.sh/uv/getting-started/installation/)** (Python package manager) 

You can check if they’re installed by running these commands in a terminal:

```
python --version
git --version
uv --version
```

## Project Setup

Follow these steps to run your project locally:

#### 1. Create a Project Folder
- Go to your Desktop
- Create a new folder
- Rename it to `CCDS-Hackathon`

#### 2. Open the Folder in VS Code

- Open **VS Code**
- Click File → Open Folder
- Select the `CCDS-Hackathon` folder

#### 3. Open the VS Code Terminal

- Click Toggle Panel (Ctrl + J) → Select Terminal
- Select **Command Prompt** for Windows

#### 4. Clone the Repository

- Run the following command in the terminal:
 ```
 git clone https://github.com/Alvin0523/CCDS_Tech_for_Good_Hackathon_2026.git
 ```

#### 5. Open the Cloned Project Folder
- Click File → Open Folder
- Select the `CCDS_Tech_for_Good_Hackathon_2026` folder inside `CCDS-Hackathon`

#### 6. Install Dependencies with uv
```
uv sync
```

#### 7. Activate the Virtual Environment
- For Windows
```
.venv\Scripts\activate.bat
```
- For macOS / Linux
```
source .venv/bin/activate
```
You should see (ccds-tech-for-good-2026) before the working directory in your terminal

#### 8. Set Up Environment Variables
- Rename the `.env.example` file to `.env`
- Open `.env`and replace the AZURE_OPENAI_API_KEY with
```
API KEY
```
**DO NOT** push this API Key to Github<br>
Always ensure `.env` is included in `.gitignore` before pushing to Github


## Project Structure 

The repository is organized as follows:

* **`src/Langchain/`**: Contains LangChain Workshop Notebook and Python logic for LLM integration.
* **`src/PyGame/`**: Assets and notebook for the graphical interface and game logic.
* **`src/resources/`**: Documentation
* **`uv.lock` & `pyproject.toml`**: Dependency management using `uv`.

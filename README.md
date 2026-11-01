## 🛠 Setup Instructions

Follow these steps to run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/iemsel/CoolNeighborhoods.git
```

### 2️⃣ Install Python (if needed)

* Python 3.11+ is required.
* Download from: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
* Make sure to check **"Add Python to PATH"** during installation.
* Verify installation:

```bash
python --version
```

### 3️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

This will create a local virtual environment in the `venv/` folder.

### 4️⃣ Activate the Virtual Environment

#### Command Prompt (cmd)

```bash
venv\Scripts\activate
```

#### PowerShell

```powershell
.\venv\Scripts\Activate.ps1
```

You should see the prompt change to:

```
(venv) C:\path\to\CoolNeighborhoods>
```

### 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

This installs all Python packages used in the project (pandas, numpy, matplotlib, seaborn, scikit-learn, notebook, etc.).

### 6️⃣ Run the Jupyter Notebook

```bash
jupyter notebook
```

* A browser will open.
* Open `project.ipynb` to start the analysis.
* All plots and results are reproducible after running the notebook cells.

### 7️⃣ Notes

* Do **NOT** upload the `venv/` folder to GitHub.
* Keep `requirements.txt` up-to-date if you add new libraries:

```bash
pip freeze > requirements.txt
```

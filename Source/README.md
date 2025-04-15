## 🚀 Installation
All libraries needed are in the `requirements.txt` file. You can install them using pip:
```bash
pip install -r requirements.txt
```

## 📌 How to Install Graphviz on Windows

To use the `graphviz` library in Python for visualizing decision trees or graphs, you need to install the **Graphviz** software and add it to the system `PATH`. Follow the detailed instructions below:

---

### 🔧 Step 1: Download and Install Graphviz

#### 📥 Download Graphviz:
- Visit the official website: [https://graphviz.org/download/](https://graphviz.org/download/)
- Download the Windows version (`.zip`)
- Extract the contents to a folder, e.g., `C:\Graphviz`.

---

### ⚙️ Step 2: Add Graphviz to PATH

1. Locate the `bin` folder: `C:\Graphviz\bin`

2. Add the path to system environment variables:
   - Press `Windows + R`, type `sysdm.cpl`, and hit Enter
   - Go to the `Advanced` tab → click **Environment Variables**
   - Under **System variables**, find `Path` → click **Edit**
   - Click **New**, then paste the path to the `bin` folder
   - Click OK to save

---

### ✅ Step 3: Verify Installation

Open **Command Prompt** and type:

```bash
dot -V
```
If successful, you will see 
```bash
dot - graphviz version 12.1.2 (20240928.0832)
```

## Run the code
For each notebook, press Run All in the menu bar to run all cells in the notebook.

## Project Structure
```
DecisionTree/
├── Docs/
│   └── Report.pdf                       # Project report
├── Source/
│   ├── data/
│   │   ├── NHANES_age_prediction.csv    # Data for age prediction from NHANES
│   │   ├── wdbc.csv                     # Wisconsin Breast Cancer data
│   │   ├── winequality-combined.csv     # Combined wine quality data
│   │   ├── winequality-red.csv          # Red wine quality data
│   │   └── winequality-white.csv        # White wine quality data
│   ├── age_prediction.ipynb             # Notebook for age prediction
│   ├── breast_cancer.ipynb              # Notebook for breast cancer classification
│   ├── wine_quality.ipynb               # Notebook for wine quality classification
│   |── wine.ipynb                       # General notebook for wine-related tasks
|   |─ README.md                         
```

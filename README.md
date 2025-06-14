# 🚀 FaceTrace-AI-Based-Detection-of-Missing-Wanted-Individuals

Welcome to the FaceTrace AI-Based Detection project! This guide will help you set up and run the application on your local machine.

---

## ✨ Project Overview

This project utilizes AI for the detection of missing and wanted individuals. It requires a Python environment and a SQLite database viewer for full functionality.

---

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

1.  **Anaconda Navigator** (Recommended for managing Python environments and launching Spyder)
2.  **DB Browser for SQLite** (To manage and view your project's databases)
3.  **YOLOv3 Weights File** (`yolov3.weights`) - This large file is not included in the repository.

### ⬇️ Download Links

*   **Anaconda Navigator:**
    Download the Anaconda Distribution for your operating system from the official website:
    👉 [Download Anaconda Distribution](https://www.anaconda.com/download)

*   **DB Browser for SQLite:**
    Download the appropriate installer for your operating system from the official website:
    👉 [Download DB Browser for SQLite](https://sqlitebrowser.org/dl/)

*   **YOLOv3 Weights (`yolov3.weights`):**
    This file is crucial for the YOLOv3 object detection part of the project. Please download it and place it in the `yolov3/` directory of your project.
    👉 [Download yolov3.weights](https://github.com/surajs41/FaceTrace-AI-Based-Detection-of-Missing-Wanted-Individuals/releases/tag/yolov3-weights-initial) (This is a common source, please verify if this is the exact one you used)

---

## 📝 Setup Instructions

Follow these steps to get your development environment ready and run the project:

### Step 1: Install Anaconda Navigator & DB Browser for SQLite

1.  📥 Download Anaconda Distribution using the link above and follow the installation instructions.
2.  📥 Download DB Browser for SQLite using the link above and install it.

### Step 2: Prepare your Anaconda Environment

1.  **Open Anaconda Navigator.** You can find it by searching in your Start Menu (Windows) or Applications (macOS).
2.  On the left sidebar, click on **"Environments"** 🧪.
3.  Create a new environment for this project (e.g., `facextrace-env`) and install necessary packages (like `opencv-python`, `tensorflow`, `pandas`, `numpy`, `scikit-learn`, `sqlite3` - though `sqlite3` is usually built-in with Python). You can use the "Channels" and "Not Installed" options to search and install.

    *   Alternatively, you can open an Anaconda Prompt (from your Start Menu), activate your environment, and install packages using `pip` or `conda`:
        ```bash
        conda create -n facextrace-env python=3.8 # or your preferred Python version
        conda activate facextrace-env
        pip install opencv-python tensorflow pandas numpy scikit-learn
        ```

### Step 3: Launch Spyder and Load Project Files

1.  In **Anaconda Navigator**, go to the **"Home"** tab 🏠.
2.  Look for **"Spyder"** and click on the **"Launch"** button (▶️ green play button).
3.  Once Spyder opens, click on the **folder icon** 📁 in the toolbar (usually at the top).
4.  Navigate to your project directory (e.g., `C:\Users\suraj\OneDrive\Desktop\Original_Criminal_Identification`) and select it. This will open all your project files in Spyder's file explorer.

### Step 4: Place YOLOv3 Weights

1.  Ensure you have downloaded the `yolov3.weights` file as mentioned in the "Download Links" section.
2.  Place this downloaded file inside the `yolov3/` directory within your project folder.
    (e.g., `C:\Users\suraj\OneDrive\Desktop\Original_Criminal_Identification\yolov3\yolov3.weights`)

### Step 5: Run the Project!

1.  In Spyder, open the main Python script you wish to run (e.g., `gui_main.py` or `GUI_master.py`).
2.  Click the **RUN** ▶️ in Spyder's toolbar to run the script.

---

## 🐞 Troubleshooting

*   If you encounter issues with missing modules, make sure your Anaconda environment is activated and you have installed all necessary packages (`pip install -r requirements.txt` if you have one, or install individually).
*   Ensure the `yolov3.weights` file is correctly placed in the `yolov3/` directory.

---

Feel free to reach out if you have any questions!

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vgbm4cZ0)
# 📄 ADGM Document Automation Assignment

## 📌 Overview
This project is part of a take-home AI engineering assignment.  
It automates the process of:
- Downloading official ADGM document templates from given links.
- Saving them in organized folders by category.
- Making the process repeatable and error-free.

**Main goals:**
- Demonstrate clear problem-solving steps.
- Produce clean and readable Python code.
- Make the project runnable in Google Colab or locally.

---

## 🛠 Features
- ✅ Direct download of official ADGM documents from provided URLs.
- 📂 Automatic folder creation for each category (e.g., `Company Formation`, `Employment & HR`).
- 🧹 Clear, beginner-friendly Python code with comments.
- ☁ Google Colab-friendly — no local setup needed.

---

---

## 🚀 Getting Started

### **1️⃣ Run on Google Colab**
Click the button below to open the notebook directly in Colab:  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/blob/main/ADGM_Document_Downloader.ipynb)

1. Run each cell in order.
2. All downloaded files will be stored in the `downloaded_files/` folder.
3. You can download them as a ZIP if needed.

---

### **2️⃣ Run Locally (Optional)**
#### **Requirements**
- Python 3.8+
- `requests` library (install with `pip install requests`)

#### **Steps**
# Clone the repository
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git

# Navigate into the project folder
cd YOUR_REPO_NAME

# Install dependencies
pip install -r requirements.txt

# Run the notebook locally
jupyter notebook ADGM_Document_Downloader.ipynb```

## 📂 Project Structure
ADGM-Document-Automation/
│
├── ADGM_Document_Downloader.ipynb # Main Google Colab notebook
├── requirements.txt # Python package dependencies (if any)
├── README.md # This file
└── downloaded_files/ # Folder with downloaded ADGM docs (auto-created)

🧠 Notes
All links are directly from official ADGM sources.

The script skips any failed downloads and reports them at the end.

You can modify the categories and links in the dictionary at the top of the notebook.

📜 License
This project is for educational and assessment purposes only.
All document rights belong to ADGM.

👩‍💻 Author
Shubhi
📧 pandeyshubhi2605@gmail.com
🔗 www.linkedin.com/in/shubhi-pandey26

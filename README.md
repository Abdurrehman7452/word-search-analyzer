# Word Search Analyzer 🧠📄

A Python-based desktop application that allows users to search for words across multiple `.txt` files with advanced options like whole word matching and case sensitivity. It also compares the performance of two string search algorithms: **Brute Force** and **Knuth-Morris-Pratt (KMP)**.

## 🚀 Features

- 🔍 **Search across multiple text files**
- 🧩 **Whole Word Match** toggle
- 🔠 **Case Sensitivity** toggle
- ⏱️ **Execution time comparison** between Brute Force and KMP
- 🖥️ Built with a clean, dark-themed **Tkinter GUI**

## 📸 GUI Preview

> _![image](https://github.com/user-attachments/assets/55dc8aa3-0806-4c41-a2a5-618e89182f86)
_

## 🛠️ Technologies Used

- Python 3.x
- Tkinter for GUI
- Standard libraries: `os`, `time`, `tkinter.messagebox`, `tkinter.filedialog`, `tkinter.font`, `tkinter.scrolledtext`

## ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/word-search-analyzer.git
   cd word-search-analyzer

2. **Run the Application**
   Make sure Python 3.x is installed on your system. Ensure Tkinter is available with your Python installation. It typically comes pre-installed on most systems.
   Open the Jupyter Notebook and run the code. 

## 🧪 How to Use the Application

### Launching the Application:

- Run the script using Python in an environment where Tkinter is available.

### Selecting Files:

- Click the "Select Files" button to open a file dialog.

- Choose one or more .txt files you want to search.

### Entering the Search Term:

- Type your search term in the field labeled "Enter Search Term".

### Setting Search Options:

- Check "Whole Word Match" to restrict results to full word matches only.

- Check "Case Sensitive" to enforce exact case matches.

### Initiating the Search:

- Click the "Search" button.

- The application will display the results, including match positions and timing for both algorithms.

### Viewing Results:

 - Output includes:

📄 File name where the term is found

🔢 Line number and column position

⏱️ Time taken by Brute Force and KMP algorithms

### Error Handling:

- If a non-.txt file is selected or if the file cannot be read, a popup will notify the user.

- If no search term is entered, an error message will prompt the user.

📁 Automatic File Sorter (Python)

A simple Python script that automatically organizes files in a specified directory into categorized folders based on their file extensions. 
This utility helps keep your folders clean and tidy by sorting .csv, .txt, .png, and .pdf files into their respective subfolders.

🔧 How It Works
- Scans a specified folder (path) for files.
- Creates subfolders (if they don’t already exist) for:
    * CSV files
    * Image files (currently only .png)
    * Text files
    * PDF files
- Moves files into the appropriate folder based on their extension
- 
🗂️ Supported File Types

Extension	Destination Folder

- csv	-> csv files/
- png	-> image files/
- txt	-> text files/
- pdf	-> pdf files/

  📦 Requirements
- Python 3.x
- Uses only built-in libraries: os, shutil

🚀 How to Use

- Set the path variable in the script to the directory you want to organize:

      path = r"C:/Users/YourUsername/Documents/AutomaticFileSorted/"

- Run the script:

      python automatic_file_sorter.py

- The script will:

      Create subfolders (if not present)

- Move files into the correct folder

👨‍💻 Author
Developed by ricki309

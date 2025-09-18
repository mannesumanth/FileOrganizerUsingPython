**📂 File Organizer using Python & Tkinter**
This is a simple desktop-based File Organizer application built using Python and Tkinter. The program helps organize files in the current working directory based on their file extensions into categorized folders such as Images, Videos, Documents, Python files, etc.

**🧠 How It Works**

The script scans the current folder where it's run and:

Identifies file types based on their extensions.

Moves each file into a subfolder based on its type (e.g., .jpg files go into an IMAGES folder, .pdf files into a PDF folder).

Creates folders automatically if they don't exist.

Skips folders and only processes files.

Removes empty folders after organizing.

**🧰 Tech Stack**

Python (Standard Library)

Tkinter for GUI (comes with Python)

os and pathlib for file handling

**📁 Supported Categories**

Files are sorted into the following directories:

Category	Extensions
HTML	.html, .htm, .xhtml, etc.
IMAGES	.jpg, .png, .gif, .svg, etc.
VIDEOS	.mp4, .avi, .mov, etc.
DOCUMENTS	.doc, .docx, .pptx, .xlsx, etc.
ARCHIVES	.zip, .rar, .tar, .gz, etc.
AUDIO	.mp3, .wav, .aac, etc.
PLAINTEXT	.txt, .in, .out
PDF	.pdf
PYTHON	.py
XML	.xml
EXE	.exe
SHELL	.sh
C-LANG	.c
CPP	.cpp
JAVA	.java, .class

**🖥️ GUI Overview**

When you launch the script, a small GUI window opens.

It shows the number of files organized.

You can click the "Organize Files" button to start the process.

**▶️ How to Run**

Make sure you have Python installed.

Place the script in the folder where your unorganized files are.

Run the script:

python file_organizer.py


Click the "Organize Files" button in the GUI to clean up your folder.

**🧹 Example**

Before running:

📁 your_folder/
├── image1.jpg
├── song.mp3
├── resume.pdf
├── script.py


After clicking "Organize Files":

📁 your_folder/
├── IMAGES/
│   └── image1.jpg
├── AUDIO/
│   └── song.mp3
├── PDF/
│   └── resume.pdf
├── PYTHON/
│   └── script.py

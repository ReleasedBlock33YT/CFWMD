# CFWMD File Manager CLI

**CFWMD** is a simple, lightweight command-line tool for creating, reading, writing to, and deleting '.cfwmd' files - a custom plaintext format with optional section-based structure.


---

## 📦 Features

- ✔️ Create '.cfwmd' files
- 🧹 Delete '.cfwmd' files
- 📖 Read and display contents
- ✍️ Write a section + data to file
- 🛠️ Packaged as a standalone executable


---

## 🚀 Usage

- Help for the executable
cfwmd.exe --help

- Creating a file
cfwmd.exe --create myFile

- Write a Section and Data
cfwmd.exe --write-section myFile SectionName "Some data here"

- Read File Contents
cfwmd.exe --read myFile

- Deleting a file
cfwmd.exe --delete myFile

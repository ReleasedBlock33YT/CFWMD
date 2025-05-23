# CFWMD File Manager CLI

**CFWMD** is a simple, lightweight command-line tool for creating, reading, writing to, and deleting '.cfwmd' files - a custom plaintext format with optional section-based structure.


---

## [box] Features

- [checkmark] Create '.cfwmd' files
- [broom] Delete '.cfwmd' files
- [open_book] Read and display contents
- [hand_writing] Write a section + data to file
- [wrench_and_hammer] Packaged as a standalone executable


---

## [rocketship] Usage

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

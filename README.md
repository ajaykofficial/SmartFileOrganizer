📁 Smart File Organizer with Search & Insights
A Python-based desktop application that organizes files automatically, allows intelligent file searches, and provides insights like file statistics, trends, and types — all built with core Python (strings, data types, OOPs, exception handling, DSA).

🚀 Features
✅ Auto-Organize Files by type, date, extension, or custom rules

🔍 Smart Search using filters (by name, extension, date, size)

📊 File Insights Dashboard showing:

File counts per type

Storage usage

Oldest/largest files

♻️ Duplicate File Detection & Cleanup

🛠️ Custom Rules Engine to define user-based organizing logic

📦 Robust Error Handling & Logging

🧠 Optimized with DSA concepts (hash maps, sorting, recursion, etc.)

🧪 Unit Tested Modules for critical functions

📂 Folder Structure

smart-file-organizer/
│
├── src/
│   ├── organizer.py             # Main class for organizing files
│   ├── search.py                # File search logic
│   ├── insights.py              # File statistics and analysis
│   ├── rules.py                 # Custom rule parser
│   ├── utils.py                 # Helper functions and validators
│   ├── exceptions.py            # Custom exception classes
│   └── main.py                  # Main script with CLI or GUI entry
│
├── data/                        # Sample directory with test files
│
├── tests/
│   ├── test_organizer.py
│   ├── test_search.py
│   └── ...
│
├── logs/
│   └── app.log                  # Runtime logs
│
├── requirements.txt
├── README.md
└── LICENSE

⚙️ Installation

Prerequisites
Python 3.8+
OS: Windows/Linux/macOS

Steps

git clone https://github.com/ajaykofficial/SmartFileOrganizer.git
cd smart-file-organizer
pip install -r requirements.txt

🧪 Usage
python src/main.py

Example CLI

python src/main.py --organize --path "/Users/AK/Downloads"
python src/main.py --search --name "report" --ext "pdf"
python src/main.py --insights

🧰 Tech Stack
Language: Python 3

Modules Used:
os, shutil, datetime, collections, hashlib
argparse (for CLI support)
logging, json, pickle (for logging/config)
unittest (for testing)

💡 Concepts Demonstrated
Topic	Implementation
Strings	Parsing filenames, extensions, content filters
Data Types	Lists, Dicts, Tuples for file grouping and stats
OOPs	Classes like FileOrganizer, FileSearcher, FileAnalyzer, etc.
Exception Handling	Try-except for file errors, custom exceptions like InvalidPathError
DSA	Sorting files, Hash Maps for duplicate detection, Recursion for folder scanning

🧪 Testing
python -m unittest discover -s tests/
🔒 License
MIT License. See LICENSE.

🧠 Credits
Built with ❤️ by Ajay K

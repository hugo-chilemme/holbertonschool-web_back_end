# Caching

## 🔖 Table of Contents

- [Description](#description)
- [Objectives](#objectives)
- [Requirements](#requirements)
- [Instructions](#instructions)
- [Tech Stack](#tech-stack)
- [Files Description](#files-description)
- [Installation and Usage](#installation-and-usage)
- [Thanks](#thanks)
- [Authors](#authors)

## 📄 Description

This project explores various caching algorithms and their Python implementations. Caching systems store and retrieve data efficiently, reducing the need for recalculations or slower data-fetching processes. Implementations include algorithms such as `FIFO`, `LIFO`, `LRU`, `MRU`, and `LFU`.

## 🎓 Objectives

By the end of this project, you should be able to:

- Explain what a caching system is and its purpose.
- Define and implement the following caching algorithms:
    - `FIFO` (First In, First Out)
    - `LIFO` (Last In, First Out)
    - `LRU` (Least Recently Used)
    - `MRU` (Most Recently Used)
    - `LFU` (Least Frequently Used)
- Understand the limitations of caching systems.

## 📋 Requirements

- All files must end with a new line.
- The first line of all files should be `#!/usr/bin/env python3`.
- A `README.md` file at the root of the project is mandatory.
- Code must follow `pycodestyle` (version 2.5).
- All files must be executable.
- File lengths will be tested using `wc`.
- Modules, classes, and functions must include proper documentation.

## 📝 Instructions

### Tasks Overview

1. **Basic Dictionary**: Implement a caching system with no size limit.
2. **FIFO Caching**: Implement a caching system using the FIFO algorithm.
3. **LIFO Caching**: Implement a caching system using the LIFO algorithm.
4. **LRU Caching**: Implement a caching system using the LRU algorithm.
5. **MRU Caching**: Implement a caching system using the MRU algorithm.
6. **LFU Caching**: Implement a caching system using the LFU algorithm.

Each task includes specific requirements and test cases to validate your implementation.

## 🔨 Tech Stack

<p align="left">
        <img src="https://img.shields.io/badge/PYTHON-3776ab?logo=python&logoColor=white&style=for-the-badge" alt="Python badge">
</p>

## 📂 Files Description

| **File**           | **Description**                                           |
|---------------------|-----------------------------------------------------------|
| `0-basic_cache.py`  | Basic dictionary-based caching implementation.            |
| `1-fifo_cache.py`   | Caching system using FIFO algorithm.                      |
| `2-lifo_cache.py`   | Caching system using LIFO algorithm.                      |
| `3-lru_cache.py`    | Caching system using LRU algorithm.                       |
| `4-mru_cache.py`    | Caching system using MRU algorithm.                       |
| `100-lfu_cache.py`  | Caching system using LFU algorithm.                       |
| `base_caching.py`   | Base class containing shared functionality and constants. |
| `README.md`         | Project documentation.                                    |

## 💻 Installation and Usage

### Installation

1. Clone the repository:
     ```bash
     git clone https://github.com/fchavonet/holbertonschool-web_back_end.git
     ```
2. Navigate to the `caching` directory:
     ```bash
     cd holbertonschool-web_back_end/caching
     ```
3. Ensure all files are executable:
     ```bash
     chmod +x *.py
     ```

### Usage

Run the test files for each task:
```bash
python3 0-main.py
python3 1-main.py
python3 2-main.py
python3 3-main.py
python3 4-main.py
python3 100-main.py
```

Modify the test files as needed to test other caching systems.

## ♥️ Thanks

Special thanks to my peers at Holberton School for their support and collaboration throughout this project.

## 👷 Authors

**Fabien CHAVONET**  
- GitHub: [@fchavonet](https://github.com/fchavonet)

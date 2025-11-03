# 🎧 Audiobook Management System using AVL Tree  
**Project Status:** Completed ✅  

> A fast, balanced, and educational implementation of an audiobook library manager — powered by an **AVL Tree** in C.

---

## 📘 Overview
This project implements an **Audiobook Management System** in C using an **AVL Tree**, a self-balancing binary search tree that ensures all major operations — **insert, search, delete, and traversal** — run in **O(log n)** time.  

It demonstrates how advanced data structures like AVL Trees can power real-world applications such as **library databases**, where performance and order maintenance are critical.

---

## ✨ Features
- 🌳 **Balanced AVL Tree** for efficient `insert`, `delete`, and `search` operations  
- 🎵 **Audiobook record management**: add, delete, and update user progress  
- 🔍 **In-order traversal** for sorted audiobook listings  
- 💻 **Command-Line Interface (CLI)** for interactive use  
- ⚙️ **Comprehensive AVL rotations**: LL, RR, LR, and RL cases  
- 📚 Designed for **educational demonstration** and DSA coursework  

---

## 💡 Motivation
Built as part of a **Data Structures & Algorithms** coursework project, this system explores the practical application of **self-balancing trees** beyond textbook examples.  

The **audiobook library** scenario was chosen to simulate a dynamic dataset with frequent insertions, deletions, and searches — making the **AVL tree’s balancing capability** both visible and meaningful.

---

## 🧠 Tech Stack
| Component | Details |
|------------|----------|
| **Language** | C (ISO C99 or later) |
| **Data Structure** | AVL Tree (Self-Balancing BST) |
| **Platform** | Cross-platform (Linux/macOS/Windows) |
| **Build Tool** | GCC or compatible C compiler |
| **Interface** | CLI-based interaction |

---

## ⚙️ How It Works
1. Each audiobook record is stored as a **node** in the AVL Tree, uniquely identified by an `ID`.  
2. **Insertions** and **deletions** automatically trigger **rotations** (LL, RR, LR, RL) to maintain balance.  
3. The **CLI menu** enables users to:
   - Insert new audiobook records  
   - Delete existing records  
   - Search by ID or title  
   - Display all audiobooks in sorted order  
4. The self-balancing nature of AVL Trees keeps performance **consistent** as the dataset grows.

---

## File Structure

AudiobookManagement/

├── audiobooklinAVLTREE.c      # Core AVL Tree implementation and CLI

├── README.md                  # Documentation

└── sample_inputs/ (optional)  # Sample data or test files


## 🧪 Usage

### 🛠️ Commands
```bash
gcc -o audiobook_system audiobooklinAVLTREE.c
./audiobook_system

# ⚙️ C++ Development Setup Guide

Set up your C++ environment quickly and start coding like a pro! 💻✨  

---

## 🛠️ Step 1: Install a C++ Compiler

| OS | Recommended Compiler | Link |
|----|--------------------|------|
| Windows | **MinGW / MSVC** | [MinGW Download](https://www.mingw-w64.org/) |
| MacOS | **Xcode Command Line Tools** | Run in terminal: `xcode-select --install` |
| Linux | **g++ (GNU Compiler)** | `sudo apt install g++` (Ubuntu/Debian) |

> ✅ Tip: After installation, check compiler version:  
> ```bash
> g++ --version
> ```

---

## 🖥️ Step 2: Choose a Code Editor / IDE

| Editor / IDE | Features | Link |
|--------------|---------|------|
| **VS Code** | Lightweight, extensions for C++ | [VS Code](https://code.visualstudio.com/) |
| **CLion** | Full-featured IDE, debugging support | [CLion](https://www.jetbrains.com/clion/) |
| **Code::Blocks** | Beginner-friendly IDE | [Code::Blocks](http://www.codeblocks.org/) |

> 💡 Tip: Install the **C/C++ extension** in VS Code for syntax highlighting & debugging.

---


## ⚡ Step 3: Configure Environment

1. Set PATH variable (Windows) to include compiler bin folder.  
2. Verify compiler in terminal / cmd:  
   ```bash
   g++ --version
---
   **Test by creating a hello.cpp file:**

#include <iostream>
using namespace std;

int main() {
    cout << "Hello, World!" << endl;
    return 0;
}

---

***Learn & Practice***

Beginner-friendly C++ tutorials: cplusplus.com

Practice problems: HackerRank C++

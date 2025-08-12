# Graphics Lab Assignment 3

**Student Name:** Tajul Islam  
**Course:** Computer Graphics & Multimedia  
**Assignment:** Create a cyan colored window with full name as window title. Close window on pressing 'T' key (first letter of the name).

---

## 📌 Description

This project creates an OpenGL window with a **cyan background**.  
The window title displays my full name: **"Tajul Islam"**.  
The program continuously renders a triangle whose color changes dynamically over time.  
Pressing **'T'** (the first letter of my name) closes the window.

---

## 🎯 Features

- **Window size:** 800×600 pixels  
- **Window title:** "Tajul Islam"  
- **Background color:** Cyan (RGB: `0, 255, 255`)  
- **Key press event:** Press 'T' to close window  
- **Dynamic graphics:** Triangle color changes over time  

---

## 🖥 Requirements

- Windows 11 (or compatible OS)  
- [MSYS2](https://www.msys2.org/) with MinGW64 toolchain installed  
- [GLFW](https://www.glfw.org/) library  
- [GLAD](https://glad.dav1d.de/) OpenGL loader  
- C++ compiler (`g++` with C++11 or higher)  

---

## ⚙️ Build & Run

1. Open **MSYS2 MinGW64** terminal  
2. Navigate to the project folder  
3. Build the project:
   ```bash
   make

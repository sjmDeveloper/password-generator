# Random Password Generator

## 1. About the Project
A lightweight desktop application built with C++ that generates secure, random passwords quickly and reliably.

## 2. Motivation & Features
* **Motivation:** Created to practice and demonstrate clean, high-performance desktop application development using C++.
* **Key Features:**
  * **Random Password Generation:** Generates unpredictable combinations of characters (letters, numbers, and symbols).
  * **Fast & Lightweight:** Built with C++ for instant execution and minimal resource usage.

## 3. Prerequisites & Installation
Before building and running the application, ensure you have **CMake** and a C++ compiler installed on your system:

### Linux
* **Ubuntu / Debian / Mint:**
  ```bash
  sudo apt-get update && sudo apt-get install cmake build-essential
  ```
* **Fedora / RHEL / CentOS:**
  ```bash
  sudo dnf install cmake gcc gcc-c++
  ```
* **Arch Linux / Manjaro:**
  ```bash
  sudo pacman -S cmake base-devel
  ```
* **openSUSE:**
  ```bash
  sudo zypper install cmake gcc gcc-c++
  ```
* **Alpine Linux:**
  ```bash
  sudo apk add cmake build-base
  ```

### Windows
Download and install **CMake** from the [Official CMake Download Page](https://cmake.org) along with a C++ compiler (MinGW or MSVC).

## 4. Build & Run

### 1. Clone & Build
Open your Terminal (Linux) or Command Prompt (Windows) and run:
```bash
git clone https://github.com
cd YOUR_REPO_NAME
mkdir build && cd build
cmake ..
cmake --build .
```

### 2. Run the Application
* **On Linux:**
  ```bash
  ./Generator
  ```
* **On Windows (CMD):**
  ```cmd
  Generator.exe
  ```

## 5. Version
`1.0.0`

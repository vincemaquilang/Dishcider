# Running Dishcider Locally Using Python's HTTP Servers

This guide explains how to set up and run the **Dishcider** template locally using Python's built-in HTTP server. This method is lightweight, easy to set up, and requires minimal installation.

---

## Prerequisites

### 1. Install Python
Before proceeding, make sure Python is installed on your system. Here’s how to check or install it:

- **Check if Python is already installed:**
  Open a terminal or command prompt and type:
  ```bash
  python --version
  ```
  or
  ```bash
  python3 --version
  ```

- **Install Python** (if not installed):
  - Download Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
  - Follow the installation steps for your operating system.
  - During installation, make sure to check the **"Add Python to PATH"** option.

---

## Steps to Run Dishcider Locally

### 1. Navigate to the Dishcider Directory
Open a terminal or command prompt and navigate to the folder where the **Dishcider** project files are located. Use the `cd` command to change directories.

Example:
```bash
cd path/to/Dishcider
```

If your project is located in `D:/Dishcider`, you would run:
```bash
cd D:/Dishcider
```

### 2. Start the HTTP Server
Run the following command in the terminal to start a local web server:
```bash
python -m http.server
```

If `python` doesn’t work, try:
```bash
python3 -m http.server
```

By default, the server will run on port `8000`.

### 3. Open the Dishcider Template in Your Browser
Once the server is running, open your browser and visit:
```
http://localhost:8000
```

- If you need to use a different port, specify it after the command. For example:
  ```bash
  python -m http.server 8080
  ```
  Then access the site at:
  ```
  http://localhost:8080
  ```

---

## Troubleshooting

### 1. Python Command Not Found
- Ensure Python is installed and added to your system’s PATH during installation.
- Reinstall Python if necessary and check the **"Add Python to PATH"** option.

### 2. Files Not Loading Correctly
- Confirm you’re in the correct directory containing the **Dishcider** project files before starting the server.
- Ensure all file paths within the project are relative, not absolute.

---

## Benefits of Using `python -m http.server`
- Simple setup, no need to install additional software.
- Lightweight and ideal for testing static websites.
- Works out of the box with most operating systems.

---

By following these steps, you can easily view and interact with the **Dishcider** template locally. Happy coding!

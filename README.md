

# 🗒️ TO DO App (Flask)

This is a **simple To-Do App** built using **Flask**.
It allows you to create and manage tasks in a clean, modern web interface.

---

## ⚙️ Prerequisites

Before running the app, make sure you have **Python**, **pip**, and **venv** installed.

### 🪟 On Windows:

Open **Command Prompt (cmd)** or **PowerShell**, then check:

```bash
python --version
pip --version
```

### 🐧 On Ubuntu / Linux:

```bash
python3 --version
pip3 --version
```

---

## 🧩 If Python, pip, or venv are NOT Installed

### 🪟 Windows Installation:

1. Download and install Python from 👉 [https://www.python.org/downloads/](https://www.python.org/downloads/)
2. During installation, **tick “Add Python to PATH”**.
3. After installation, confirm:

   ```bash
   python --version
   pip --version
   ```

### 🐧 Ubuntu / Linux Installation:

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install python3 -y
sudo apt install python3-pip -y
sudo apt install python3.10-venv -y
```

> ⚠️ **Note:**
> Depending on your system, the Python command may be `python`, `py`, or `python3`.

---

## 💾 Clone This Repository (on Windows)

1. Open **PowerShell or Command Prompt**.
2. Move to the **C drive**:

   ```bash
   cd C:\
   ```
3. Clone the repository:

   ```bash
   git clone https://github.com/prathmesh-ghatmal/python-flask-todo.git
   ```
4. Go inside the project folder:

   ```bash
   cd python-flask-todo
   ```

---

## ▶️ Run on Windows

1. **Create Virtual Environment:**

   ```bash
   python -m venv venv
   ```

2. **Activate Virtual Environment:**

   ```bash
   venv\Scripts\activate
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask App:**

   ```bash
   python app.py
   ```

5. Open your browser and visit:
   👉 [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧳 Migrate Project to Linux (using FileZilla)

You can easily move your Flask app to a Linux machine or VM (e.g., VirtualBox Ubuntu).

### 📤 Before transferring:

1. **Delete your local environment folders** — they are Windows-specific:

   ```
   venv/
   instance/
   ```

   (Don’t worry, new ones will be created on Linux.)

2. **Zip** your project folder or directly transfer files using FileZilla.

---

### 📥 Upload to Linux

1. Open **FileZilla**.
2. Connect to your Linux system using credentials (example):

   ```
   Host: 192.168.xx.xx
   Username: imcc
   Password: <your password>
   Port: 22
   ```
3. On the right side (Linux), navigate to:

   ```
   /home/imcc/
   ```
4. Create or choose a folder (e.g., `flaskapp`) and upload your project there.

---

## ▶️ Run on Linux

1. Open **Terminal** inside the project directory:

   ```bash
   cd /home/imcc/python-flask-todo
   ```

2. **Create new virtual environment:**

   ```bash
   python3 -m venv venv
   ```

3. **Activate it:**

   ```bash
   source venv/bin/activate
   ```

4. **Install requirements:**

   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Flask app:**

   ```bash
   python3 app.py
   ```

6. Open your browser and visit:
   👉 [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧠 Notes

* Always activate your `venv` before running the app.
* If you make code changes, restart the Flask server to see updates.
* Use `Ctrl + C` in terminal to stop the running Flask app.


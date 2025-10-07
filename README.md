# HackTheBox Machines

## 📘 About

Write-ups and notes for HackTheBox Starting Point and retired machines. Intended for educational purposes in ethical hacking and penetration testing.

---

## 🌐 Read them online

If you prefer not to install ``mkdocs-material`` and its dependencies locally to be able to edit the notes, you can just read them online at: 

https://hollowdragonx.github.io/htb-machines/

---

## 🚀 Getting Started

These notes were made using ``mkdocs-material`` for a clean, navigable, and responsive experience, so it is highly recommended to use it for reading them.

To view this notes as a website locally (intended use):

## 1. Clone the repository

```bash
git clone https://github.com/HollowDragonX/htb-machines.git
cd htb-machines
```

## [OPTIONAL] Create a virtual environment
```bash
python3 -m venv myvenv

# Activate the environment on Windows (CMD)
myvenv\Scripts\activate.bat

# Activate the environment on Windows (PowerShell)
myvenv\Scripts\activate.ps1

# Activate the environment on MacOS
source myvenv/bin/activate
```

## 2. Install mkdocs-material
```bash
pip install mkdocs-material
```

## 3. Serve the site locally

⚠️ **Note:** Make sure to be in the folder where the notes are located (and where the ``mkdocs.yml`` file of those notes is located).

```bash
mkdocs serve
```

Now you can see the notes properly by visiting http://127.0.0.1:8000 in the browser.

If you want to serve the site for all the devices on the same network, run this instead:

```bash
mkdocs serve -a 0.0.0.0:8000
```

Then in the browser visit http://your-local-ip:8000
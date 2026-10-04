# Python

 # Python Virtual Environment Setup (Git Bash on Windows)

## 1. Verify `pip` Installation

Check that `pip` is installed and available:

```bash
pip -V
```

Example output:

```text
pip 25.x.x from C:/Python313/Lib/site-packages/pip (python 3.13)
```

---

## 2. Create a Virtual Environment

Create a virtual environment named `venv2`:

```bash
python -m venv venv2
```

This creates a folder structure similar to:

```text
venv2/
├── Include/
├── Lib/
├── Scripts/
└── pyvenv.cfg
```

---

## 3. Activate the `venv2` Environment

In Git Bash on Windows:

```bash
source venv2/Scripts/activate
```

The command prompt changes to:

```text
(venv2)
cocon@john MINGW64 /d/GitHubProgressivePull/Jim_Bakery (main)
$
```

---

## 4. Switch to Another Virtual Environment

If another environment named `venv` already exists, activate it with:

```bash
source venv/Scripts/activate
```

The prompt changes to:

```text
(venv)
cocon@john MINGW64 /d/GitHubProgressivePull/Jim_Bakery (main)
$
```

---

## 5. Deactivate the Current Environment

To exit the active virtual environment:

```bash
deactivate
```

The environment name disappears from the prompt.

---

## 6. Verify the Active Python Interpreter

Check which Python executable is being used:

```bash
which python
```

Example:

```text
/d/GitHubProgressivePull/Jim_Bakery/venv2/Scripts/python
```

---

## Common Commands

```bash
# Create virtual environment
python -m venv venv2

# Activate venv2
source venv2/Scripts/activate

# Activate venv
source venv/Scripts/activate

# Install packages
pip install requests

# List installed packages
pip list

# Deactivate environment
deactivate

# Show current Python path
which 

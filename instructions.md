# Python Virtual Environment Setup - Windows

## Creating a Virtual Environment

1. Navigate to your project directory:
```cmd
cd C:\path\to\your\project
```

2. Create the virtual environment:
```cmd
python -m venv venv
```

## Activating the Virtual Environment

### Using Command Prompt:
```cmd
venv\Scripts\activate
```

### Using PowerShell:
```cmd
venv\Scripts\Activate.ps1
```

When activated, you'll see `(venv)` at the beginning of your command prompt.

## Installing Packages

Install packages as usual:
```cmd
pip install package-name
```

Example:
```cmd
pip install requests numpy pandas
```

Save packages to requirements.txt:
```cmd
pip freeze > requirements.txt
```

Install from requirements.txt:
```cmd
pip install -r requirements.txt
```

## Deactivating

When you're done:
```cmd
deactivate
```


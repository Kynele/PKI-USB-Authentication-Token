# -------------------------------
# OS-Specific Files (MacOS, Linux)
# -------------------------------
.DS_Store
._*
.Spotlight-V100
.Trashes
.vscode/
.idea/
*.swp
*~

# -------------------------------
# Python
# -------------------------------
__pycache__/
*.pyc
*.pyo
*.pyd
*.env
*.venv
venv/
env/
Pipfile
Pipfile.lock
poetry.lock

# -------------------------------
# C / C++ Compiled Files
# -------------------------------
*.o
*.obj
*.so
*.out
*.a
*.dylib
*.exe
*.dll

# -------------------------------
# Raspberry Pi USB Gadget Mode
# -------------------------------
/sys/kernel/config/usb_gadget/*

# -------------------------------
# TPM-Specific Files (Sensitive!)
# -------------------------------
tpm_key_*.ctx
*.priv
*.pub
*.pem
*.der
*.crt
*.csr
*.key
*.enc
tpm-sealed-data/

# -------------------------------
# Build System / Temporary Files
# -------------------------------
build/
dist/
node_modules/
*.log
*.bak
*.tmp
*.lock
*.pid

# -------------------------------
# Virtual Machines / Emulators
# -------------------------------
*.vbox
*.vdi
*.vmdk
*.qcow2
*.img
*.iso

# -------------------------------
# Miscellaneous
# -------------------------------
*.zip
*.tar.gz
*.7z
*.rar

# Barcode Generator

## Description

This project uses:
- Python: 3.9.6
- Flask: 3.0.2

## How to run

First, we need to create a virtual environment (.venv/):

```bash
  python3 -m venv .venv
```

Also we need to install all dependencies listed in <requirements.txt>:

```bash
  pip3 install -r requirements.txt
```

To initialize the server, after configuration, we only need to execute:

```bash
  python3 run.py
```

### Where are my generated barcodes?

All barcodes generated via http requests are stored in <public/assets/barcodes/>

# pykx-introduction

An introductory Jupyter Notebook that demonstrates how to use the [PyKX](https://code.kx.com/pykx/) Python library to interact with the powerful **kdb+/q** time-series database. This guide is ideal for developers and data engineers looking to explore the capabilities of PyKX and get hands-on experience with kdb+ from within Python.

## 📘 Overview

This repository contains:

- A beginner-friendly **Jupyter Notebook** showcasing PyKX usage.
- Examples that bridge **q language** and **Python** through the PyKX API.
- Quick setup instructions for using PyKX in a development environment.

## 🧠 What is PyKX?

[PyKX](https://code.kx.com/pykx/) is a Python interface for [kdb+](https://kx.com/kdb/), a high-performance time-series database. PyKX provides seamless integration between Python and q, allowing you to leverage the speed of kdb+ with the flexibility of Python.

## 📁 Contents

- `pykx-introduction.ipynb`: A Jupyter Notebook demonstrating how to:
  - Initialize PyKX
  - Run q expressions in Python
  - Create and manipulate kdb+ tables
  - Interface with pandas DataFrames
  - Leverage PyKX types and utilities

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/chankeypathak/pykx-introduction.git
cd pykx-introduction
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

Ensure you have `pykx` installed. Note that PyKX may require access credentials to the KX platform or a valid license.

```bash
pip install jupyter pykx pandas
```

> 🔐 **Note:** PyKX is available via [KX Developer](https://code.kx.com/pykx/installation/). You may need to [register for access](https://kx.com/developers/) to download and install PyKX.

### 4. Launch the Notebook

```bash
jupyter notebook
```

Then open `pykx-introduction.ipynb` in the browser.

## 📊 Example Use Cases

- High-frequency trading data ingestion and analysis
- Time-series data transformation and aggregation
- Integrating machine learning models with real-time databases

## 🧩 Requirements

- Python 3.7+
- PyKX (requires kdb+ license or access)
- Jupyter Notebook
- pandas

## 🚀 Getting Started with kdb+ and q

If you're new to kdb+ and q, check out:

- [KX Academy](https://kx.com/academy/)
- [q for Mortals](https://code.kx.com/q4m3/)
- [PyKX Documentation](https://code.kx.com/pykx/)

## 🤝 Contributions

Contributions and feedback are welcome! Feel free to open issues or submit pull requests if you have improvements or suggestions.

## 📝 License

This project is provided for educational purposes and does not include a license file. Please check individual file headers or reach out to the repository author for usage permissions.

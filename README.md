# Agentic Framework Project using SendGrid

[![Stars](https://img.shields.io/github/stars/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid?style=flat-square)](https://github.com/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid/stargazers)
[![Forks](https://img.shields.io/github/forks/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid?style=flat-square)](https://github.com/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid/network/members)
[![Issues](https://img.shields.io/github/issues/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid?style=flat-square)](https://github.com/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid?style=flat-square)](https://github.com/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid/pulls)
[![License](https://img.shields.io/github/license/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid?style=flat-square)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue?style=flat-square)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-ready-orange?style=flat-square)](Agentic_framework_project_using_sendgrid.ipynb)

A demonstration of how to build a simple agentic framework that sends emails via SendGrid, all contained in a Jupyter notebook.

##  Table of Contents

- [Features](#-features)  
- [Prerequisites](#-prerequisites)  
- [Installation](#-installation)  
- [Configuration](#-configuration)  
- [Usage](#-usage)  
- [Project Structure](#-project-structure)  
- [Contributing](#-contributing)  
- [License](#-license)  

##  Features

- **Agentic Workflow**: Step-by-step pipeline for message generation and dispatch.  
- **SendGrid Integration**: Use the official SendGrid Python SDK to send transactional emails.  
- **Notebook-Driven**: Everything lives in a single Jupyter notebook for easy experimentation.

##  Prerequisites

- Python 3.8 or higher  
- A SendGrid account and API key  
- `pip` for package installation

##  Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Rishi-Kora/Agentic-Framework-Project-using-Sendgrid.git
   cd Agentic-Framework-Project-using-Sendgrid


2. (Recommended) Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies:

   ```bash
   pip install sendgrid jupyter
   ```

## 🔧 Configuration

1. Create a SendGrid API key at [https://app.sendgrid.com/settings/api\_keys](https://app.sendgrid.com/settings/api_keys)
2. In the notebook, set your API key as an environment variable:

   ```python
   import os
   os.environ["SENDGRID_API_KEY"] = "YOUR_SENDGRID_API_KEY"
   ```

##  Usage

1. Launch Jupyter:

   ```bash
   jupyter notebook
   ```
2. Open `Agentic_framework_project_using_sendgrid.ipynb`.
3. Follow the cells to see how the agent constructs and sends emails.

##  Project Structure

```
.
├── Agentic_framework_project_using_sendgrid.ipynb   # Main demo notebook
├── LICENSE                                          # MIT License
└── README.md                                        # This file
```

##  Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/xyz`)
3. Commit your changes (`git commit -m 'Add xyz'`)
4. Push to branch (`git push origin feature/xyz`)
5. Open a Pull Request

Please open issues for bug reports or feature requests!

## 📄 License

This project is licensed under the [MIT License](LICENSE).



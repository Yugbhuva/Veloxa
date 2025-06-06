# Veloxa 🚀

A modern CLI tool to quickly scaffold Flask project structures with best practices.

[![PyPI version](https://badge.fury.io/py/veloxa.svg)](https://pypi.org/project/veloxa/)
[![Python](https://img.shields.io/pypi/pyversions/veloxa.svg)](https://pypi.org/project/veloxa/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## ✨ Features

- **8 Pre-built Flask Templates** - From simple hello world to production-ready structures
- **Two Usage Modes** - Create new projects or initialize in existing directories
- **Interactive CLI** - Beautiful prompts with easy navigation
- **Modern Structure** - Follows Flask best practices and conventions
- **Zero Configuration** - Works out of the box
- **Cross Platform** - Windows, macOS, and Linux support

## 🚀 Quick Start

### Installation

```bash
pip install veloxa
```

### Usage

#### Create a New Project
```bash
veloxa
```
This will:
1. Ask for your project name
2. Let you choose a Flask structure
3. Create a new directory with all files

#### Initialize in Current Directory
```bash
mkdir my-flask-app
cd my-flask-app
veloxa init
```
This will:
1. Let you choose a Flask structure
2. Create files directly in the current directory
\
Note: While initializing your folder should be empty

## 📁 Available Project Structures

| Structure | Description | Best For |
|-----------|-------------|----------|
| **Single File Structure** | Simple hello world app | Learning, prototyping |
| **Basic Modular Structure** | Organized into modules | Small to medium apps |
| **Application Factory Pattern** | Factory pattern with config | Scalable applications |
| **Blueprint-Based Structure** | Modular with blueprints | Medium to large apps |
| **Factory + Blueprints + Config** | Complete structure with config classes | Production applications |
| **Flask with Celery** | Async task queue integration | Background job processing |
| **Flask with API** | RESTful API structure | API development |
| **Full-Scale Production** | Complete production setup | Enterprise applications |

## 🛠️ Examples

### Creating a Simple API Project
```bash
veloxa
# Enter project name: "my-api"
# Select: "Flask with API (RESTful Structure)"
cd my-api
pip install -r requirements.txt
python run.py
```

### Setting up in Existing Directory
```bash
mkdir awesome-flask-app
cd awesome-flask-app
veloxa init
# Select desired structure
pip install -r requirements.txt
python run.py
```

## 📋 What's Included

Each generated project includes:
- ✅ **Proper Flask structure** following best practices
- ✅ **Requirements.txt** with necessary dependencies
- ✅ **Configuration files** for different environments
- ✅ **Sample routes and views**
- ✅ **Template files** (where applicable)
- ✅ **Static file organization**
- ✅ **Database models** (in applicable structures)
- ✅ **Error handling**
- ✅ **Blueprint organization** (where applicable)

## 🎯 Project Structure Examples

### Basic Modular Structure
```
my-app/
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── models.py
│   └── templates/
├── config.py
├── requirements.txt
└── run.py
```

### Blueprint-Based Structure
```
my-app/
├── app/
│   ├── __init__.py
│   ├── main/
│   ├── auth/
│   ├── api/
│   └── templates/
├── migrations/
├── config.py
├── requirements.txt
└── run.py
```

## 🔧 Requirements

- Python 3.7+
- pip

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Setup
```bash
git clone https://github.com/yugbhuva/veloxa.git
cd veloxa
pip install -e .
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature request? Please open an issue on [GitHub Issues](https://github.com/yugbhuva/veloxa/issues).

## 📞 Support

- **Documentation**: [GitHub Repository](https://github.com/yugbhuva/veloxa)
- **Issues**: [GitHub Issues](https://github.com/yugbhuva/veloxa/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yugbhuva/veloxa/discussions)

## 🙏 Acknowledgments

- Flask community for the amazing framework
- All contributors who help improve Veloxa

## 📈 Changelog

### v0.1.0
- Initial release
- 8 Flask project templates
- Interactive CLI with questionary
- Support for both project creation modes

---

**Made with ❤️ by [Yug Bhuva](https://github.com/yugbhuva)**

*Scaffold Flask projects at the speed of light* ⚡"# Veloxa" 
"# Veloxa" 
"# Veloxa" 
"# Veloxa" 

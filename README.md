# Project Name

## Description
Brief description of the project.

## Prerequisites
- Python 3.x
- pip (Python package installer)

## Installation

### Clone the repository
```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Create a virtual environment
#### On macOS and Linux
```
python3 -m venv venv
source venv/bin/activate
```

#### On Windows
```
python -m venv venv
.\venv\Scripts\activate
```

### Install dependencies
```
pip install -r requirements.txt
```

## Running tests
### Run all tests
```
pytest
```

### Run specific tests
```
pytest path/to/test_file.py
```

## Troubleshooting
If you encounter ```FileNotFoundError: [Errno 2] No such file or directory``` when try to run tests - click on Run test sign 
and select Modify Run configuration. Then change Working directory to the project root directory.
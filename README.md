# Rule Engine with AST

## Overview
This project is a 3-tier rule engine application to determine user eligibility based on attributes like age, department, income, and spend. The system uses an Abstract Syntax Tree (AST) to represent conditional rules, allowing dynamic creation, combination, and modification of these rules.

## Getting Started

### Prerequisites
- Docker
- Python 3.8+
- Node.js

### Setup Instructions

#### Backend Setup
```bash
# Clone the repository
git clone https://github.com/anshikavashistha/Rule-Engine-with-AST.git
cd rule-engine-ast/backend

# Install dependencies
pip install -r requirements.txt

# Run backend server
python manage.py runserver

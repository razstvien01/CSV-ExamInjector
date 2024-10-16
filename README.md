# CSV-ExamInjector

## Overview
CSV-ExamInjector is a simple command-line application designed to facilitate the importing and management of exam questions stored in CSV files. This tool allows users to load questions from specified directories, start exams, and view scores.

## Features
- **Import CSV Files**: Easily import exam questions from CSV files located in user-defined directories.
- **Dynamic Loading**: Select and load all or specific CSV files to prepare for an exam.
- **User-Friendly Interface**: Clear prompts and messages guide the user through the process.
- **Error Handling**: Graceful error handling for file access and loading issues.

## Getting Started

### Prerequisites
- Python 3.x
- Required Python libraries (install via `pip`)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
    ```bash
    cd CSV-ExamInjector
    ```
    
3. **Set up a virtual environment** (recommended):
   - For Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
   - For Linux or macOS:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Installation
1. Run the application:
    ```bash
    python main.py
    ```
2. Follow the on-screen instructions to import exam paths and load questions.
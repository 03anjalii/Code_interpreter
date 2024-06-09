# Code Interpreter for Various File Formats

## Description

This project implements a code interpreter that reads content from various file formats (PDF, XLSX, CSV, DOCX), generates Python code using the OpenAI GPT-3.5 API based on the content and user prompts, executes the generated code, and returns the output.

## Setup

1. Clone the repository.
2. Install the required libraries:
    ```bash
    pip install PyPDF2 pdfplumber openpyxl pandas python-docx openai
    ```
3. Replace `your-api-key` in the `generate_code` function with your OpenAI API key.

## Usage

1. Place your files in the project directory.
2. Modify the `file_path` and `file_type` variables in the `main` function.
3. Run the script:
    ```bash
    python main.py
    ```

## Modules

### File Reader Module

Contains functions to read content from PDF, XLSX, CSV, and DOCX files.

### Code Writer Module

Generates Python code using the OpenAI GPT-3.5 API based on the file content and user prompt.

### Code Executor Module

Safely executes the generated Python code and captures the output.

### Integration Module

Handles file uploads, generates code, executes it, and returns the output.

## License

This project is licensed under the MIT License.

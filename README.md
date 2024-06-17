# Online Course Slides Generator

This project transforms an input text file into PowerPoint and PDF files following a specified template.

## Installation

1. Clone the repository:
    ```sh
    git clone <REPOSITORY_URL>
    cd <REPOSITORY_NAME>
    ```

2. Create a virtual environment and install dependencies:
    ```sh
    python -m venv venv
    source venv/bin/activate   # Linux and macOS
    .\venv\Scripts\activate    # Windows
    pip install -r requirements.txt
    ```

3. Install [wkhtmltopdf](https://wkhtmltopdf.org/downloads.html), necessary for the conversion from PPTX to PDF.

## Usage

1. Place the input text file in the root of the project.
2. Run the main script:
    ```sh
    python main.py --text ./aula1_slides.txt
    ```
3. The generated files will be saved in the `output` folder.

## Project Structure

- `main.py`: Main script to generate the files.
- `template.pot`: PowerPoint template to be used.
- `requirements.txt`: Project dependencies.
- `README.md`: Project documentation.
- `output/`: Folder where the generated files will be saved.

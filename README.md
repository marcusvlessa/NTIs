# Intelligence Analysis Tool

## Description

This project contains tools for data analysis in intelligence operations. The user interface is built using Tkinter and CustomTkinter.

## Modules

### `project.py`

This file contains the main User Interface (UI) code with the following functions:

- `launch_iped()`: Launches the iPED program.
- `open_erb()`: Opens the ERB website.

### `pdf_processor.py`

This module contains the PDF processing functions:

- `analyze_pdfs()`: Analyzes PDF files to extract specific data.

## Requirements

- Python 3.x
- Tkinter
- CustomTkinter
- PyPDF2
- pandas
- matplotlib
- pytest (for testing)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/marcusvlessa/NTIs
   ```

   Navigate to the project directory:
   ```bash
   cd NTIs
   ```

   Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run `project.py` for the main GUI.

```bash
python project.py
```

Use the GUI buttons to execute specific functions like launching iPED, analyzing PDFs, or opening the ERB website.

## Testing

Run the tests using pytest:

```bash
pytest test_project.py
```

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) to get started.

## License

This project is under the MIT license. See the [LICENSE.md](LICENSE.md) file for more details.

## Authors

Marcus Lessa

# Advanced-GUI
You can convert a selected Excel sheet into a CSV file. Additionally, you could specify the separator &amp; decimal value for the CSV file.
# Excel-to-CSV Converter

## Overview

The Excel-to-CSV Converter is a simple Python script designed to provide a graphical user interface (GUI) for converting Excel files to CSV format. This tool utilizes the `pandas` library for data processing and `PySimpleGUI` for creating the GUI.

## Prerequisites

Ensure you have the following installed before running the script:

- [Python](https://www.python.org/downloads/)
- [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [PySimpleGUI](https://pysimplegui.readthedocs.io/en/latest/#install)

## Usage

1. **Run the Script:**

   ```bash
   python excel_to_csv_converter.py
   ```

2. **Main Window:**

   - **Input File:** Browse and select the Excel file you want to convert.
   - **Output Folder:** Choose the folder where the converted CSV file will be saved.

3. **Buttons:**

   - **Settings:** Configure separator, decimal, and Excel sheet name.
   - **Display Excel File:** View the data types and content of the selected Excel file.
   - **Convert To CSV:** Convert the Excel file to CSV format.

4. **Menu:**

   - **Toolbar:** Commands for future functionality.
   - **Help:**
      - **Settings:** Adjust converter settings.
      - **About:** View information about the converter.
      - **Exit:** Close the application.

## Settings

The script uses an INI file (`config.ini`) to store settings. You can configure:

- **CSV Settings:**
  - Separator
  - Decimal representation

- **Excel Settings:**
  - Default sheet name

- **GUI Settings:**
  - Theme
  - Font family
  - Font size

## Contributing

Feel free to contribute by reporting issues, suggesting new features, or submitting pull requests. Refer to the [contribution guidelines](CONTRIBUTING.md) for details.

## License

This project is licensed under the [MIT License](LICENSE).

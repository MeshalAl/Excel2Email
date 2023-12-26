# Excel2Email

Excel2Email is a Python script that reads an Excel file, connects to an SMTP email server, and sends emails based on the content of the Excel file.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Pandas library: `pip install pandas`
- Openpyxl library: `pip install openpyxl`

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Excel2Email.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Excel2Email
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Update the configuration file:

    Open the `config.py` file and provide the necessary details such as SMTP server, email credentials, and Excel file path.

5. Run the script:

    ```bash
    python excel2email.py
    ```

    The script will read the Excel file, connect to the SMTP server, and send emails based on the content of the Excel file.

## Configuration

The `config.py` file contains the following configuration options:

- `SMTP_SERVER`: The SMTP server address.
- `SMTP_PORT`: The SMTP server port.
- `EMAIL_ADDRESS`: The email address used to send the emails.
- `EMAIL_PASSWORD`: The password for the email address.
- `EXCEL_FILE_PATH`: The path to the Excel file containing the email content.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

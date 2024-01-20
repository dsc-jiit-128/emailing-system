Email Automation Script README

This project is a Python script that automates the process of sending emails to a list of recipients using Gmail. The script reads email addresses from an Excel file, prompts the user for their email credentials, subject, and HTML body, and then sends personalized emails to the recipients.

Getting Started
Follow these steps to use the script:

Clone the Repository:
Clone this repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/your-username/email-automation-script.git
Install Dependencies:
Ensure you have the required Python packages installed. You can install them using the following command:

Copy code
pip install pandas
Update Excel File Path:
Open the script file (email_script.py) and locate the line where the Excel file path is specified. Update the path to point to your Excel file containing the list of email addresses.

python
Copy code
df = pd.read_excel("/path/to/your/email.xlsx")
Run the Script:
Execute the script by running the following command in your terminal:

Copy code
python email_script.py
User Input Prompts
During script execution, you will be prompted to provide the following information:

Email: Your Gmail email address.
Email Password: Your Gmail account password.
Subject: The subject line for the email.
HTML Body: The HTML body of the email. Use \n to indicate new paragraphs.
Important Note
Make sure to handle your email credentials with caution and do not share them with others. Additionally, it's recommended to use an App Password for Gmail if you encounter any authentication issues.

Disclaimer
This script is provided as-is and may require modifications based on your specific use case. Use it responsibly and ensure compliance with Gmail's policies on automated email sending.

If you encounter any issues or have suggestions for improvements, feel free to open an issue on the GitHub repository.

Happy Emailing!
# VirusTotal File Scanner

This Python application leverages the VirusTotal API to scan files for viruses and other security threats. It provides a simple GUI for users to select and scan files, and displays the scan results in real-time.

## Features
- **VirusTotal API Integration**: Utilizes the VirusTotal API for comprehensive file scanning.
- **Graphical User Interface**: Easy-to-use interface built with PySimpleGUI for selecting and scanning files.
- **Real-Time Feedback**: Provides immediate scan results and feedback within the application window.

## How It Works
The application reads the API key from the environment variables and uses it to send files to VirusTotal for scanning. It then periodically checks for the scan report and displays the results to the user through the GUI.

## Setup
1. Obtain an API key from VirusTotal.
2. Set the `VT_API_KEY` environment variable with your API key.
3. Install the required Python packages: `requests` and `PySimpleGUI`.
4. Run the script to start scanning files.

## Usage
Upon launching the application, use the 'Browse' button to select a file for scanning. Click 'Scan' to initiate the process. The scan results will be displayed in the output area of the window.

## Disclaimer
This tool is for informational purposes only. Always ensure to comply with VirusTotal's terms of service when using their API.

## Contributions
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request for review.

---

This description provides a comprehensive overview of your project, including its features, setup instructions, and usage. Make sure to include any additional information that might be helpful for users, such as troubleshooting tips or contact information for support.

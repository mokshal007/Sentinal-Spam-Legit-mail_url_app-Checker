# Sentinal-Spam-Legit-mail_url_app-Checker
# Threat Analysis Tool



## Description

Sentinal is a command-line threat analysis tool designed to provide insights into different types of cyber threats using machine learning models. The tool supports three main types of analysis: Malware Analysis with ML, Email Spam Analysis with ML, and URL Spam Analysis with ML. It utilizes machine learning algorithms to predict whether a given input is indicative of a threat or not.

## Features

- **Malware Analysis with ML:** Analyze executable files to determine if they contain malicious code using machine learning.
- **Email Spam Analysis with ML:** Analyze email content to predict whether it's spam or legitimate using machine learning.
- **URL Spam Analysis with ML:** Analyze URLs to determine if they are spam or secure using machine learning.

## Prerequisites

- Python 3.x
- Required Python packages (install using `pip`):
  - `argparse`
  - `subprocess`
  - `random`
  - `pyfiglet`
  - `extractPE` (replace with actual package name)
  - `malwareML` (replace with actual package name)
  - `spamML` (replace with actual package name)
  - `urlML` (replace with actual package name)

## Usage

1. Clone this repository to your local machine.

2. Install the required Python packages using the following command:
   pip install argparse subprocess random pyfiglet

3. Navigate to the directory containing the cloned repository.

4. Run the CyberMachine tool using the command line. You can use the following arguments:

- To perform Malware Analysis with ML:
  ```
  python3 cybermachine.py --exe <file_path>
  ```

- To perform Email Spam Analysis with ML:
  ```
  python3 cybermachine.py --mail <email_content>
  ```

- To perform URL Spam Analysis with ML:
  ```
  python3 cybermachine.py --url <url>
  ```

5. The tool will provide machine learning predictions based on the analysis performed.

## Disclaimer

Sentinal is intended for educational and informational purposes only. It demonstrates the use of machine learning in threat analysis. The tool should not be used for any malicious or unauthorized activities. Always follow ethical guidelines and laws while using this tool.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Note:** Replace URLs, package names, and logos with actual ones. Adjust package installation commands if needed.


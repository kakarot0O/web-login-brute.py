# Website Login Brute-Force Script

This script is designed to perform a brute-force attack on a website login form. It uses a list of usernames and passwords to attempt logging into the target website and detects a successful login based on a specified "needle" response.

**Note:** This script is intended for educational and ethical purposes only. Unauthorized use against systems you do not own or have permission to test is illegal.

## Features

- Performs a brute-force attack on a website login form using given usernames and passwords.
- Provides real-time progress updates during the brute-forcing process.
- Stops and reports back when a successful login is detected.

## Prerequisites

- Python 3.x
- `requests` library (install using `pip install requests`)

## Usage

1. Clone this repository to your local machine.
2. Navigate to the repository directory.
   
  - git clone https://github.com/kakarot00/web-login-brute.py.git
  - cd login-brute-force

3. Open the script and provide the necessary information:

  - Set the target variable to the URL of the target website's login form.
  - Set the usernames variable to the path of the file containing the list of usernames.
  - Set the passwords variable to the path of the file containing the list of passwords.
  - Set the needle variable to the message that appears on a successful login.

4. Run the Script

  - python3 web-login-brute.py

## Disclaimer
This script is provided for educational purposes only. Unauthorized use of this script against systems you do not own or have explicit permission to test is illegal. The author is not responsible for any misuse or damage caused by this script.

  

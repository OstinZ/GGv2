# Grass2.0 by Ostinz

Welcome to Grass2.0! This open-source project, generously shared by Twitter user Snow God of War (@Hy78516012)and modified by Ostinz, is completely free to use. The "2.0" indicates "Season 2" rather than doubling the original version, so please note this distinction!

## Registration
If you're new to Grass, please consider supporting by signing up through my referral link: [Register Here](https://app.getgrass.io/register?referralCode=ACtBvEoVAYeltgK). Thank you!

## Important Warnings and Precautions
- All risks associated with "witch" activities are assumed by the user.
- This program supports only one account, but it can be used with multiple IP addresses.

## Proxy Information
This script is intended for educational and reference purposes only. Users are solely responsible for their actions. 

**Proxy Formats Supported**:
```plaintext
http://host:port
socks5://host:port
http://user:password@host:port
socks5://user:password@host:port
```

## Setup Instructions

### Prerequisites
- Ensure that Python and Git are installed on your device.

### Installation Steps

1. **Clone the Repository**
   Open your terminal (CMD/PowerShell/Terminal) and run:
   ```bash
   git clone https://github.com/ostinz/GG
   ```
   Alternatively, you may download the repository as a ZIP file, extract it, and navigate to the extracted folder.

2. **Navigate to the Grass2.0 Directory**
   ```bash
   cd grass2.0
   ```

3. **Install Required Libraries**
   Run the following command to install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```

4. **Configure Proxies**
   Open the `proxies.txt` file and enter your proxy information in one of the supported formats. If no proxies are specified, the program will default to your public IP.

5. **Set Up Authentication**
   Run the `setup.py` file. You’ll be prompted to enter your Grass account email and password to obtain your authentication credentials (ID and token). If you encounter issues, you may need to manually retrieve your User ID and Token.

### Troubleshooting
- If you receive a `ModuleNotFoundError` for `httpx`, install it with:
   ```bash
   pip install httpx
   ```
- For further assistance, copy the error message and consult with a support resource or AI helper.

6. **Run the Main Program**
   Launch the main program by executing:
   ```bash
   python main.py
   ```

## Retrieving User ID and Token

### How to Obtain User ID
1. Log into the Grass website.
2. Open your browser’s Developer Tools Console and run:
   ```javascript
   copy(JSON.parse(localStorage.getItem("userId")))
   ```
   Your **User ID** will be copied to your clipboard. Paste it into the `userid.txt` file.

### How to Obtain Token
1. Similarly, run this code in the Console to retrieve your **Token**:
   ```javascript
   copy(JSON.parse(localStorage.getItem("accessToken")))
   ```
   Copy and paste this Token into the `token.txt` file.

---

# wpsql-exp

Author: Rockman
Telegram: [rockman365_2](https://t.me/rockman365_2)
Telegram Channel: [rockmanstore](https://t.me/rockmanstore)

## Description

This Python script is designed to perform an exploit on a WordPress website. It performs an SQL injection exploit on the target website after authenticating using provided credentials. The script can be used in two modes: a single scan mode for a single target IP and a mass scan mode for multiple IPs.

In the single scan mode, it prompts for the target IP interactively. In the mass scan mode, it reads a list of target IPs from a text file and displays results differently for successful and failed scans.

## Usage

1. Clone or download the script to your local machine.

2. Make sure you have Python installed on your system.

3. Install the required Python packages, if not already installed:
   ```shell
   pip install requests


   
**Run the script:**
For a single scan, use option 1 and provide the target IP interactively.
For a mass scan, use option 2 and provide the path to a text file containing a list of target IPs, one per line.
Script Output

**In single scan mode:**
The script performs the exploit on the provided target IP.
Results are displayed in the console, showing success or failure for the given IP.

**In mass scan mode:**
The script reads a list of target IPs from the specified text file.
It performs the exploit on each IP in the list.
Results are displayed in the console, with successful scans shown in green and failed scans in red.

**Disclaimer**
This script is provided for educational purposes and should only be used with proper authorization. Unauthorized use for any malicious purposes is strictly prohibited. The author and contributors of this script are not responsible for any misuse or damage caused by its usage.

**License**
This script is provided under an open-source license. You are free to use, modify, and distribute it as per the terms of the license.

**Support and Contact**
If you have any questions or need support, you can contact the author on Telegram: rockman365_2 or check out the rockmanstore channel for updates and related content.

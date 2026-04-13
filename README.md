# port-scanner-01

## Description

This is a basic Python script that scans a target host for open ports. It checks a predefined list of common ports and displays whether they are open or closed, along with their associated services.

## Features

* Scans common ports (FTP, SSH, HTTP, etc.)
* Identifies open and closed ports
* Simple and easy-to-understand code
* Fast scanning using socket connection

## Requirements

* Python 3.x

## How to Use

1. Run the script:

   ```bash
   python scanner.py
   ```

2. Enter the target (IP address or domain name), for example:

   ```
   Enter target: google.com
   ```

3. View the results:

   ```
   [OPEN]   port 80 → HTTP
   [closed] port 21 → FTP
   ```

## Ports Scanned

* 21 (FTP)
* 22 (SSH)
* 25 (SMTP)
* 53 (DNS)
* 80 (HTTP)
* 443 (HTTPS)
* 3306 (MySQL)
* 3389 (RDP)
* 8080 (HTTP-Alt)

## Notes

* This tool is for educational purposes only.
* Scanning networks without permission may be illegal.

## License

Free to use for learning and personal projects.

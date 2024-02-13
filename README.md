Simple IP Scanner

**Description**

This project is a simple IP scanner written in Python. It allows users to scan a range of IP addresses within a specified network to determine which hosts are active (i.e., responding to ping requests). The scanner utilizes the `ping` command and regular expressions to extract relevant information from the ping results.

Usage

1. **Input IP Addresses:**
   - Run the Python script.
   - Enter the first and last IP addresses of the range you want to scan when prompted.

2. **Scan Process:**
   - The scanner will extract the network and host portions from the entered IP addresses.
   - It will then loop through the range of host addresses, performing ping tests for each IP address.
   - The ping results will be concatenated and searched using a regular expression pattern to identify active hosts.

3. **Output:**
   - The scanner will print the network address, the first host in the range, and the last host in the range.
   - For each host within the specified range, it will indicate whether the host is UP or DOWN based on the ping response.
   - Once the scanning process is completed, a "Completed" message will be displayed.

## Installation

1. Clone the repository or download the source code files to your local machine.

2. Ensure you have Python installed on your system.

3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
## License

This project is currently unlicensed, meaning all rights are reserved by the author. Unauthorized use, modification, or distribution is not permitted.

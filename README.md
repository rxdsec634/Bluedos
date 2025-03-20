# RXDSEC Bluetooth Security Toolkit

A high-performance Bluetooth security analysis toolkit designed for comprehensive device vulnerability assessment and targeted network penetration testing. you need to extract zip for tool:

![Version](https://img.shields.io/badge/Version-2.0-red)
![Compatibility](https://img.shields.io/badge/Bluetooth-5.0/5.3-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

- **Real-Time Device Detection**: Scan for and identify all nearby Bluetooth devices using modern BLE protocols.
- **Security Analysis**: Perform comprehensive vulnerability assessments on discovered devices.
- **Vulnerability Scoring**: Calculate risk scores based on multiple factors including protocol version, signal strength, manufacturer security track records, and available services.
- **Advanced Attack Operations**: 
  - L2CAP Protocol Vulnerability Scanning
  - PIN/Pairing Security Attacks
  - Authentication Mechanism Analysis
  - Ultra-High Performance DoS Capabilities
- **Performance**: 
  - 15,000+ packets per second in DoS operations
  - Supports up to 128 concurrent attack threads
  - Capable of device takedowns in 1-3 seconds for vulnerable targets
- **Protocol Support**: Works with Bluetooth protocols up to v5.3, including targeted BT5-specific attack vectors.
- **Rich Visual Interface**: Color-coded threat indicators and detailed device information.

## Installation

1. Clone the repository
   ```
   git clone https://github.com/rxdsec634/bluedos.git
   cd bluedos
   ```

2. Install dependencies
   ```
   pip install -r requirements.txt
   ```

3. Run the toolkit (requires root/admin privileges)
   ```
   sudo python main.py
   ```

## Usage

### Main Menu
The toolkit presents a main menu with the following options:

1. **[SCAN]** - Scan for nearby Bluetooth devices
2. **[ANALYZE]** - Execute security analysis on selected devices
3. **[ATTACK]** - Launch advanced attack operations
4. **[REPORT]** - Generate detailed penetration testing report
5. **[EXIT]** - Exit the toolkit

### Attack Operations

The Advanced Attack Operations menu provides the following options:

1. **[VULN SCAN]** - Identify L2CAP protocol vulnerabilities
2. **[PIN CRACK]** - Attack pairing & security mechanisms
3. **[AUTH BYPASS]** - Target authentication vulnerabilities
4. **[ULTRA DOS]** - Launch high-power DoS attack (15K+ packets/sec)

### Sample Commands

Scan for devices:
```
sudo python main.py
```
Select option 1 to initiate a device scan.

## Dependencies

- Python 3.8+
- bleak (BLE interactions)
- rich (Terminal UI)

## Disclaimer

This tool is intended for security research and assessment purposes only. Use responsibly and only on devices and networks you own or have explicit permission to test. The authors take no responsibility for misuse of this software.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Created by telegram username @Rxdsec

## Acknowledgments

- The Bluetooth SIG for protocol documentation
- The security research community for vulnerability disclosures

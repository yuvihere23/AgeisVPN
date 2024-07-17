# OpenVPN Server Configuration

This repository contains configuration files and instructions for connecting to an OpenVPN server hosted on AWS EC2.

## Getting Started

To connect to the VPN server, follow these steps:

### Prerequisites

- Install the OpenVPN Connect app on your android device
   - [OpenVPN Connect for Android](https://play.google.com/store/apps/details?id=net.openvpn.openvpn&hl=en_IN&pli=1)
   
- Install the OpenVPN Connect Client on your device:
   - [OpenVPN Connect for Android](https://openvpn.net/client/)
         

### Steps to Connect [2 Methods]
## Method 1
1. **Download the OpenVPN Configuration**

   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/your-username/openvpn-config.git
     ```

2. **Configure OpenVPN Connect**

   - Open the OpenVPN Connect app on your Android device.
   - Tap on the "+" icon to import a new VPN profile.
   - Navigate to the downloaded `your-config.ovpn` file and select it.
  
3. **Connect to VPN**

   - Tap on the connection profile to initiate the VPN connection.
   - Enter the password when prompted.

## Method 2

1. **Configure OpenVPN Connect**

   - Open the OpenVPN Connect app on your Android device.
  
2. **Enter VPN Connection Details**

   - Enter the following details in the OpenVPN Connect app:
     - **Server Address**: `52.45.235.30`
     - **Port**: `1194` (UDP)
     - **Username**: `demouser`
     - **Password**: DemoUser@123

3. **Connect to VPN**

   - Tap on the connection profile to initiate the VPN connection.
   - Enter the password when prompted.

4. **Verify Connection**

   - Once connected, the OpenVPN Connect app will indicate a successful connection.

### Testing Credentials

For testing purposes, use the provided `demouser` credentials to connect to the VPN server.

- **Username**: `demouser`
- **Password**: DemoUser@123

## Troubleshooting

If you encounter any issues while connecting, please check:
- Network connectivity on your device.


## Additional Information

- For further assistance or questions, contact the repository owner.
- Security best practices: Ensure passwords are handled securely and shared only with trusted individuals.


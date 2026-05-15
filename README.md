# MysteryVPN-Client
EN:
# MysteryVPN Client — C++ GUI for OpenVPN

A native Windows application in C++ (WinAPI) for connecting to OpenVPN via .ovpn configs.

Minimalism, speed, and no unnecessary dependencies.

## 🧱 Requirements

- Windows 7/8/10/11
- OpenVPN (any version) — [official website](https://openvpn.net/community-downloads/)
- OpenVPN must be installed and accessible via %PATH%

> This project does not contain OpenVPN. It only runs the existing installation.

## 📦 Installation

1. Download the `MysteryVPNClient.zip` archive from the **Releases** section
2. Unzip **all contents into one folder**
- Example: `C:\MysteryVPNClient\`
- The folder should contain `VPNClient.exe` and related files
3. Run `VPNClient.exe` (administrator rights are not required)

> ⚠️ Important: The program uses relative paths. Do not move files individually.

## 🎮 Usage

| Action | What to press |
|----------|-------------|
| Select `.ovpn` config | **"Select config"** button |
| Forget current config | **"Clear"** button |
| Connect | **"Connect"** button |

When connecting, the program calls:
```cmd openvpn.exe --config "path\to\.ovpn config"



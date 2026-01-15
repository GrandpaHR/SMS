# 🚀 SMS Bomber v2.0 - powerd by Grandpa_Academy 

<div align="center">

![Version](https://img.shields.io/badge/version-2.0-blue.svg)
![Python](https://img.shields.io/badge/python-3.7+-green.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20Termux-lightgrey.svg)

**A powerful SMS testing tool with triple channel support and beautiful CLI interface**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Screenshots](#-screenshots) • [Legal](#%EF%B8%8F-legal-disclaimer)

</div>

---

## 📋 Table of Contents

- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Usage](#-usage)
- [Configuration](#%EF%B8%8F-configuration)
- [Screenshots](#-screenshots)
- [Support](#-support)
- [Legal Disclaimer](#%EF%B8%8F-legal-disclaimer)

---

## ✨ Features

### 🎯 Core Features
- ✅ **Triple Channel System** - 3 independent API channels
- ✅ **Smart Rate Limiting** - Configurable cooldown (5-60s)
- ✅ **Real-time Progress** - Live attack monitoring with countdown
- ✅ **Beautiful UI** - Colorful CLI with emojis and boxes
- ✅ **Cross-Platform** - Works on Windows, Linux, and Termux
- ✅ **Auto Browser Launch** - Opens social links automatically
- ✅ **Attack Logging** - Save detailed reports to file
- ✅ **Channel Toggle** - Enable/disable channels individually
- ✅ **Success Tracking** - Real-time success rate calculation

### 🛡️ Security Features
- 🔐 AES-256 encryption simulation
- 🎭 Stealth mode operation
- 🔄 Session management
- ⚡ Request timeout handling
- 🛑 Error recovery system

### 🎨 UI Features
- 📊 Status dashboard with health monitoring
- 🎯 Interactive menu system
- ⏳ Animated countdown timers
- 📈 Progress bars with percentages
- 📋 Detailed statistics panel
- 💾 Professional log generation
- 🌈 Color-coded outputs

---

## 📦 Requirements

### System Requirements
- **Python**: 3.7 or higher
- **OS**: Windows 10+, Linux, Android (Termux)
- **RAM**: 512 MB minimum
- **Storage**: 50 MB free space

### Python Packages
```txt
requests>=2.28.0
```

---

## 🔧 Installation

### Method 1: Standard Installation

```bash
# Clone the repository
git clone https://github.com/GrandpaHR/SMS.git

# Navigate to directory
cd SMS

# Install dependencies
pip install -r requirements.txt

# Run the program
python main.py
```

### Method 2: Termux Installation

```bash
# Update packages
pkg update && pkg upgrade

# Install required packages
pkg install python git

# Clone repository
git clone https://github.com/GrandpaHR/SMS.git

# Navigate to directory
cd SMS

# Install dependencies
pip install -r requirements.txt

# Run the program
python SMS
```

### Method 3: Windows Installation

```bash
# Download Python from python.org (if not installed)

# Clone repository
git clone https://github.com/GrandpaHR/SMS.git

# Navigate to directory
cd SMS

# Install dependencies
pip install -r requirements.txt

# Run the program
python main.py
```

---

## 🎮 Usage

### Quick Start

1. **Launch the program**
   ```bash
   python main.py
   ```

2. **Select option from menu**
   - `[1]` Launch SMS Attack
   - `[2]` View Channel Status
   - `[3]` Configure Settings
   - `[4]` Exit Program

3. **Enter target details**
   - Phone number (with country code)
   - Attack cycles (1-30)

4. **Confirm and execute**
   - Review attack summary
   - Type `yes` to launch

### Menu Options Explained

#### 🚀 Option 1: Launch SMS Attack
- Opens GitHub profile automatically
- Enter target phone number
- Configure attack cycles
- Real-time progress monitoring
- Detailed success statistics

#### 📊 Option 2: View Channel Status
- Check all channel statuses
- View endpoint information
- Monitor channel health
- See encryption details

#### ⚙️ Option 3: Configure Settings
- **Change Cooldown**: Set delay between cycles (5-60s)
- **Toggle Channels**: Enable/disable individual APIs
- Real-time configuration updates

#### 🚪 Option 4: Exit Program
- Safe shutdown
- Cleanup operations
- Display credits

---

## ⚙️ Configuration

### Channel Configuration

Each channel can be configured in the code:

```python
self.apis = {
    'api1': {
        'name': 'Service A',
        'url': 'https://api-endpoint.com/send',
        'method': 'POST',
        'payload': True,
        'active': True
    }
}
```

### Settings Options

| Setting | Default | Range | Description |
|---------|---------|-------|-------------|
| Cooldown | 15s | 5-60s | Delay between attack cycles |
| Max Cycles | 30 | 1-30 | Maximum attack iterations |
| Channels | 3 | 1-3 | Active API channels |
| Timeout | 10s | Fixed | Request timeout duration |

---

## 📸 Screenshots

### Main Menu
```
╔═══════════════════════════ MAIN MENU ════════════════════════╗
║                                                               ║
║  [1] 🚀 Launch SMS Attack          Start bombing sequence    ║
║  [2] 📊 View Channel Status        Check system health       ║
║  [3] ⚙️  Configure Settings        Adjust parameters         ║
║  [4] 🚪 Exit Program               Shutdown system           ║
║                                                               ║
╚══════════════════════════════════════════════════════════════╝
```

### Attack Progress
```
╔═══ 🔥 CYCLE 1/5 ═══════════════════════════════════════════╗
║ ⏰ Time: 14:30:45 • Status: ATTACKING...                    ║
╚═════════════════════════════════════════════════════════════╝

  📡 Service A        ✓ SUCCESS
  🌐 Service B        ✓ SUCCESS
  🛰️ Service C        ✓ SUCCESS
```

---

## 💬 Support

### Join Our Community

- 📱 **Telegram**: [Termux Team BD](https://t.me/Termux_Team_BD_0)
- 🐙 **F**: [Md:HR](https://github.com/GrandpaHR)

### Reporting Issues

Found a bug? Please open an issue on GitHub with:
- Detailed description
- Steps to reproduce
- System information
- Error messages (if any)

---

## ⚖️ Legal Disclaimer

### ⚠️ IMPORTANT - READ CAREFULLY

This tool is provided for **EDUCATIONAL AND AUTHORIZED TESTING PURPOSES ONLY**.

### Legal Use Cases
✅ Testing your own phone numbers
✅ Authorized penetration testing
✅ Educational research with permission
✅ Security vulnerability assessment (authorized)

### Illegal Use Cases
❌ Harassment or spam campaigns
❌ Unauthorized testing on others
❌ Malicious intent or damage
❌ Violation of telecom regulations

### Your Responsibilities
- **YOU** are responsible for your actions
- **YOU** must obtain proper authorization
- **YOU** must comply with local laws
- **YOU** accept all legal consequences

### Authors' Position
The authors and contributors:
- Do NOT condone illegal use
- Are NOT responsible for misuse
- Provide this tool AS-IS
- Disclaim all liability

**By using this tool, you agree to use it legally and ethically.**

---

## 👨‍💻 Author

### Development Team

**Granpa Academy**
- Role: Project Lead & Concept
- Telegram: [@Termux_Team_BD_0](https://t.me/Termux_Team_BD_0)

**Md HR**
- Role: Lead Developer
- GitHub: [@GrandpaHR](https://github.com/GrandpaHR)
- Specialization: Python Development & CLI Tools

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Granpa Academy & Md HR

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

### Version 2.0 (Current)
- ✨ Triple channel system
- 🎨 Complete UI overhaul
- 📊 Real-time statistics
- 💾 Log file generation
- 🔗 Auto browser launch
- ⚙️ Advanced configuration
- 🛡️ Enhanced error handling

### Version 1.0
- 🚀 Initial release
- Basic SMS functionality
- Single channel support

---

##  Acknowledgments
- Inspired by various security testing tools
- Built with ❤️ for education

---

## 📞 Contact

For inquiries, suggestions, or collaboration:

- 📧 **Email**: Contact via GitHub issues
- 💬 **Telegram**: [@Termux_Team_BD_0](https://t.me/Termux_Team_BD_0)
- 🐙 **GitHub**: [GrandpaHR](https://github.com/GrandpaHR)

---

<div align="center">

**Made with ❤️ by Granpa Academy & Md HR**

⚠️ **Use Responsibly | Stay Legal | Happy Learning** ⚠️

[⬆ Back to Top](#-sms-bomber-v20---powerd-by-grandpa_academy)

</div>

# 📡 cyberthot BLE 🕵️‍♂️

![Hacker Theme](https://img.shields.io/badge/Theme-Hacker-brightgreen)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![License](https://img.shields.io/badge/License-GPLv3-red)

## 🚀 Overview

cyberthot BLE is a cutting-edge Bluetooth surveillance tool that leverages the power of cyberthot BLE One to intercept and analyze Bluetooth Low Energy (BLE) advertisements. With real-time monitoring capabilities and Discord webhook integration, it's the perfect tool for security researchers, penetration testers, and Bluetooth enthusiasts.

## 🔧 Features

- 🔍 Real-time BLE advertisement interception
- 📊 Detailed parsing of advertisement data
- 🚨 Automatic device name decoding
- 📡 Continuous monitoring with auto-reconnect
- 🔔 Discord webhook integration for remote notifications
- 🐛 Debug mode for in-depth analysis

## ☠️ Prerequisites!

You need a ubertooth device and have all the drivers installed. Try this to be sure (I'm using Linux OS):

```
ubertooth-util -v
```

If not, you can order one or make one 
buying link :-
🚨 [Lab401](https://lab401.com/r?id=iop7bf) 🚨
More info at [Great Scott Gadgets](https://www.greatscottgadgets.com)

# Make your own hardware:-
coming soon.............................

## 🛠 Installation

1. Clone this repository:
2.  The script will detect missing dependencies and provide the suggested pip install line. This is what you'll need though.
   ```
   pip install requests colorama rich pyusb
   ```

## ⚙️ Configuration

### Discord Webhook (Optional)

To enable Discord notifications:

1. Open `cyberthot.py` in your favorite text editor.
2. Locate the following line near the top of the file:
   ```python
   WEBHOOK_URL = ""
   ```
3. Replace the empty string with your Discord webhook URL:
   ```python
   WEBHOOK_URL = "https://discord.com/api/webhooks/your/webhook/url/here"
   ```

cyberthot BLE provides rich, colorful console output for easy reading:

```
📡 Collecting advertisements...
📊 Collected 10 advertisements
╭──────────────────────── 🚨 FitBit Versa 3 🚨 ─────────────────────────╮
│ Field       │ Value                                                  │
│ Device Name │ FitBit Versa 3                                         │
│ Timestamp   │ 2024-08-02 15:30:45                                    │
│ Frequency   │ 2402 MHz                                               │
│ Address     │ 00:11:22:33:44:55                                      │
│ RSSI        │ -67                                                    │
│ Data        │ 02011A020A0C0AFF4C001005031B57F9C3                     │
│ Type        │ ADV_IND                                                │
│ Details     │ systime=1659456645 freq=2402 addr=00:11:22:33:44:55... │
╰────────────────────────────────────────────────────────────────────╯
```
And to Discord:

![image](https://github.com/user-attachments/assets/7f0398f0-8db1-414c-9acc-ed476a99edeb)


## 🛡 Disclaimer

This tool is for educational and research purposes only. Always respect privacy laws and obtain necessary permissions before monitoring any Bluetooth traffic.

## 📜 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## 💖 Show your support

Give a ⭐️ if this project helped you!


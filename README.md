# Yandex Account Creator

🚀 Create endless amounts of free Yandex Accounts. 🚀

🏗 Manage your free Yandex Accounts. 🏗

📌 Ver. 1.1 📌

🤖 Full Proxy Support 🤖

## WORKING: SEPTEMBER 2022

## Features

- Random inputs for Username & Password ✏️
- Save Account details after Creation in .cvs file 🧾
- Full Auto Account Creation 🤖
- Enable IMAP & POP3

## Getting Started

This script can create Yandex Free Mail Accounts with the usage of proxies.

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Support 👨‍💻

Any problems with running the script and any questions please cantact me via Twitter [@hendrik_bgr](https://twitter.com/Hendrik_bgr)

<a href="https://www.buymeacoffee.com/hendrikbgr" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

### Prerequisites

- Python 3.6+

## ⚠️ WARNING! ⚠️

#### Accounts can not be accessed via the Web UI!

#### Only use IMAP or POP3 to access you emails after the account creation!

## Before We get started

You will need to have access to 5Sim and some Premium Proxies.

Get your 5Sim Access here: [5Sim](https://5sim.net)

Get cheap Premium proxies here: [Proxy-Cheap](https://app.proxy-cheap.com/r/4l2Djs)
You will need Static Residential Proxies

Once you are registered with both services you need to place your 5Sim API key into the config.py file

After that place your proxies in proxies.txt (ip:port)

Get a copy of the Project. Open your Terminal and enter:

```
git clone https://github.com/hendrikbgr/YandexMail-Account-Creator
```

To install all needed requirements run the following command in the project directory:

```
pip install -r requirements.txt
```

After that you can proceed to start the Script.

## Running 🏃🏽‍♂️

To run this script open your Terminal in the project directory.

To start the Account Creator Script enter:

```
python creator.py
```

## Output

You will find account details in list.csv in this format.

| Email | Password | First Name | Last Name | Security Question | Proxy Used | App Password (imap) | Phone Number Used | Phone Number ID |
| ----- | -------- | ---------- | --------- | ----------------- | ---------- | ------------------- | ----------------- | --------------- |

## Authors

- **Hendrik Bgr** - _Initial work_ - [HendrikBgr](https://github.com/hendrikbgr)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Hat tip to anyone whose code was used

## To Do List 📝

- Add random username and password. ✅
- Print account details to in console ✅
- Add more information to console when running ✅
- Create requirements.txt file for easy installation ✅
- Script Crashes when captcha is wrong ✅

#### Notes

This code is for educational use only.

   # Hamster Kombat Season 2 Farming Bot 
This is a bot that can help you to run 'HMSTR Season 2' telegram bot!

[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/cucumber_scripts)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cucumber-pickle/Cucumber)


## Features

Visit : [https://t.me/hamsteR_kombat_bot/](https://t.me/hamsteR_kombat_bot/start?startapp=kentId726837621)

- Auto Sync = Claim profit per hour when idle
- Auto Buy Upgrade (with 4 method options) - `ON/OFF`
- Auto Buy Skin & Selected Highest Skin ID `Auto ON`
- Auto Complete Tasks - `ON/OFF`
- Static UserAgent - `Auto ON`
- Easily save and run your setup
- PROMO CODE & OTHER FEATURE COMING SOON!

##  Auto Upgrade metode
  1. Upgrade items with the **highest profit**
  2. Upgrade items at the **lowest price**
  3. Upgrade items with a **price less than balance**
  4. Upgrade item with the **highest payback** `RECOMENDED!`

## Prerequisites
Before installing and running this project, make sure you have the following prerequisites:
- Python 3.10+ (recomended)
- Other required dependencies

## Installation
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/cucumber-pickle/HMSTR-S2Cum.git
    ```
2. Go to the project directory:
    ```bash
    cd HMSTR-S2Cum
    ```
3. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```


### Instant Setup:
- **Loading setup via CLI argument:** If the `--setup` argument is provided, the script will load the corresponding `.json` file and run the bot directly without displaying the menu.
- **Menu display:** If no `--setup` argument is provided, the script will display the menu as usual.
- **Setup saving:** The option to save setups has been included in the menu as option `8`.

This will allow you to run the script directly with a predefined setup like this:

```bash
python main.py --setup mysetup
```

### Add configuration setting on `config.json` 

 **bool** : `true` or `false`

  ```bash
{
    "use_proxy": false,
    "DELAY_UPGRADE": false,
    "MIN_DELAY_UPGRADE": 4,
    "MAX_DELAY_UPGRADE": 6,
    "DELAY_EACH_ACCOUNT": 5,
    "MAXIMUM_PRICE": 2,
    "LOOP_COUNTDOWN": 3800
}
  ```


### Create a `proxies.txt` file
The `proxies.txt` file should be in the root directory and contain a list of proxies in the format `username:password@host:port`.

Example:

```yaml
socks5://user1:pass1@ip1:port1
user2:pass2@ip2:port2
```

## RUN THE BOT
after that run the bot by writing the command

```bash
python main.py
```


## How to get tgWebAppData (query_id / user_id)

1. Login telegram via portable or web version
2. Launch the bot
3. Press `F12` on the keyboard 
4. Open console
5. Сopy this code in Console for getting tgWebAppData (user= / query=):

```javascript
copy(Telegram.WebApp.initData)
```

6. you will get data that looks like this

```
query_id=AA....
user=%7B%22id%....
```
7. add it to `data.txt` file or create it if you dont have one


## This bot helpfull?  Please support me by buying me a coffee: 

``` 0xc4bb02b8882c4c88891b4196a9d64a20ef8d7c36 ``` - BSC (BEP 20)

``` UQBiNbT2cqf5gLwjvfstTYvsScNj-nJZlN2NSmZ97rTcvKz0 ``` - TON

``` 0xc4bb02b8882c4c88891b4196a9d64a20ef8d7c36 ``` - Optimism

``` THaLf1cdEoaA73Kk5yiKmcRwUTuouXjM17 ``` - TRX (TRC 20)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For questions or support, please contact [CUCUMBER TG CHAT](https://t.me/cucumber_scripts_chat)



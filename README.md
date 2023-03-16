# SouthXchange_trading_bot
Python Trading bot

you will need two files
```
.env

Southxchange_Bot.py
```
Email: cryptominer8245@yahoo.com to get the files of this bot

Click here to contact me on Discord: <a href="https://discord.com/users/412476381725720576">Cryptominer8245</a>


For Install you will need Python3
check your version by opening a terminial and type
```python3 --version```

Update the package list and upgrade any existing packages:
```
sudo apt-get update
sudo apt-get upgrade
```
Install Python by running the following command:
```
sudo apt-get install python3
```
Verify the installation by checking the Python version:
```
python3 --version
```

The Bot needs a few libraries

to Install the libraries:
```
pip install Southxchange
pip install requests
pip install termcolor
pip install prettytable
pip install python-dotenv
```

You will need to update your ``Private Keys`` and ``Coin Pairs`` in the .env file
Example:
```
# Southxchange Keys
# Api-Key
api_key=
# Api-Secret-Key
secret_key=
```

In The Bot ``Southxchange_Bot.py``

You can update the following lines of code to your stratigies
```
minimum_price = 0.00000185 # Set Min Sell Price
currentaskprice = market_data[2] - 0.00000001 # the Price step decrease
amount=random.uniform(0.10, 0.25)

max_price = 0.00000150 # Set Max Buy Price
currentbidprice = market_data[1] + 0.00000005 # the Price step increase
amount=random.uniform(0.10, 0.25)
```
add # to the ``order_info =`` line of code to stop the bot order from being placed

To start Bot in Terminal:
1. `screen -S Southxchange_Trading_Bot` this is the folder where the bot is located
2. start bot
```
python3 Southxchange_Bot.py
```
3. to exit screen and keep bot running hold the key `Control` and than press keys `a d` at the same time
4. to resume screen type `screen -r`
5. to stop bot press `Control c`

Trading Bot Example: The bot show error control

<img src="https://user-images.githubusercontent.com/40405385/225472200-0746bbd7-3cba-4426-811f-c3de179ea057.png" width="25%" alt="Southxchange_bot">
![image](https://user-images.githubusercontent.com/40405385/225472200-0746bbd7-3cba-4426-811f-c3de179ea057.png)


<div style="color: yellow;">

**Disclaimer:**

The trading bot provided herein is designed for informational and educational purposes only. It is not intended to be, and should not be construed as, financial, investment, or trading advice. Users of this trading bot assume full responsibility for any decisions made based on its outputs, and the creators and maintainers of the bot shall not be held liable for any losses, damages, or claims arising from the use of this tool. Trading in financial markets involves substantial risks, including the potential for loss of principal, and may not be suitable for all investors. Before using this trading bot, users should carefully consider their financial objectives, risk tolerance, and level of experience. We strongly recommend consulting with a qualified financial advisor before making any investment or trading decisions.

</div>

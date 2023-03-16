###################################################
#   SouthXchange Bot Created by Cryptominer8245   #
#       Marker Maker, WashTrade & Info Bot        #
#                Created 2-22-2023                #
###################################################
import Southxchange
import json
import time
import datetime
import random
import termcolor
import os
import requests
from prettytable import PrettyTable
from datetime import datetime
from termcolor import colored
from dotenv import load_dotenv

load_dotenv()

api_key = os.getenv("api_key")
secret_key = os.getenv("secret_key")

Southxchange.Southxchange(api_key, secret_key)


Market = Southxchange.Market()
Markets = Southxchange.Markets()
Wallets = Southxchange.Wallets()

symbol = 'DGB' # Enter Alt Coin
base = 'BTC' # Enter Base Coin Example: (BTC, USDT, LTC)
# Clear the terminal
os.system('clear')
#############################################################
# Get current date and time
now = datetime.now()
date_string = now.strftime("%B %d %Y")
time_string = now.strftime("%I:%M:%S %p")
#############################################################
print(colored(" SouthXchange Bot Loading", "light_magenta"))
##########_GET_WALLET_BALANCE_##########
def getbalances(coin):
    try:
        currencies = json.loads(Wallets.balances())
    except json.JSONDecodeError as e:
        print(colored("Error: Failed to parse JSON response", "red"))
        print(e)
        return None
    for dict in currencies:
        if dict.get('Currency') == coin:
            coin_name = dict.get('Currency')
            balance = dict.get('Available', 0)
            balance = format(balance, ".9f")
            print(colored("SouthXchange Balances", "light_magenta"))
            print("You have \033[1;32m{} {}\033[0;0m".format(balance, coin_name))
            return balance
    print(colored("Coin '{}' not found.".format(coin), "yellow"))
    return None
time.sleep(1)
#############################################################
# To get The rest of the working Code you must contact me  
# for Purchasing it - Thank you

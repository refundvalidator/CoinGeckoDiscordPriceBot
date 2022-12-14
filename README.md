# CoinGeckoDiscordPriceBot

Very simple price bot for coins listed on coingecko. 

Just edit the info.json to your own custom values depending on the coin, then run using `python3 main.py`. Bot needs no permissions.

## Requirements
-`python3`

-`pip`

Use `pip install -r requirements.txt` to install needed packages

### info.json
```json
{   
    "api":"[DISCORD-API-KEY]",
    "id":"[ID-OF-COIN]",
    "vscurrency":"[COMPARISON-CURRENCY]"
    "length":[MAX-CHARACTERS-OF-PRICE],
    "updatefreq":[UPDATE-FREQUENCY-IN-SECONDS] 
}
```

### List of Coin IDs can be found at [HERE](https://docs.google.com/spreadsheets/d/1wTTuxXt8n9q7C4NDXqQpI3wpKu1_5bGVmP9Xz0XGSyU/edit#gid=0)

<i>CoinGecko has a limit for the free API of <b>10-50 calls per minute</b>, plan accordingly when setting the updatefreq variable in info.json</i>

### Currently I am hosting two instances of this bot for the cryptos FUND and xFUND if you would like to add them to your server:

[FUND](https://discord.com/api/oauth2/authorize?client_id=1047325323055878145&permissions=0&scope=bot)

[xFUND](https://discord.com/api/oauth2/authorize?client_id=1047329418936332339&permissions=0&scope=bot)

![image](https://imgur.com/A4GpFdP.png)

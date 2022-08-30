
# FTX Grid Trading Bot

The program was designed to run the Grid Trading Strategy in [FTX exchange](https://ftx.com/#a=1815639)
 
Grid trading strategy can follow [here](https://www.gridtradingcourse.com/articles/what-is-grid-trading.php).


It requires python 3.x and the following Python packages:
* [ccxt](https://github.com/ccxt/ccxt)
* [simplejson](https://pypi.org/project/simplejson/)
```
pip3 install ccxt simplejson
```
![](https://github.com/HenrisonTao/ftx_grid_trading_bot/blob/master/sample.png)

## Getting Started
The program is suggested to run in the Linux platform; also, you need to edit some parameters before program start. Follow the behind steps. 
**you should prepare the enough USD and spot for grid trading buying and selling . Futures do not need to prepare enough spot to sell.
1. Edit some config settings in `setting.json.example` and rename it to `setting.json`.
2. Run program
```
bash ./start.sh
```

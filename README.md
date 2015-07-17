[![Latest Version](https://img.shields.io/pypi/v/pandas_talib.svg)](https://pypi.python.org/pypi/pandas_talib.svg/)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/pandas_talib.svg)](https://pypi.python.org/pypi/pandas_talib.svg/)
[![Wheel format](https://img.shields.io/pypi/wheel/pandas_talib.svg)](https://pypi.python.org/pypi/pandas_talib.svg/)
[![License](https://img.shields.io/pypi/l/pandas_talib.svg)](https://pypi.python.org/pypi/pandas_talib.svg/)
[![Development Status](https://img.shields.io/pypi/status/pandas_talib.svg)](https://pypi.python.org/pypi/pandas_talib.svg/)
[![Downloads monthly](https://img.shields.io/pypi/dm/pandas_talib.svg)](https://pypi.python.org/pypi/pandas_talib.svg/)
[![Requirements Status](https://requires.io/github/femtotrader/pandas_talib/requirements.svg?branch=master)](https://requires.io/github/femtotrader/pandas_talib/requirements/?branch=master)
[![Code Health](https://landscape.io/github/femtotrader/pandas_talib/master/landscape.svg?style=flat)](https://landscape.io/github/femtotrader/pandas_talib/master)
[![Codacy Badge](https://www.codacy.com/project/badge/1bf3606360934588ba764cca32210f52)](https://www.codacy.com/app/femto-trader/pandas_talib)
[![Build Status](https://travis-ci.org/femtotrader/pandas_talib.svg)](https://travis-ci.org/femtotrader/pandas_talib)


** Work in progress **

# pandas_talib
A Python Pandas implementation of technical indicators

Original version from:

- [Bruno Franca](https://github.com/brunogfranca)

- [panpanpandas](https://github.com/panpanpandas)

- [Peter Bakker](https://www.quantopian.com/users/51d125a71144e60865000044)

See also:

- [panpanpandas/ultrafinance](https://github.com/panpanpandas/ultrafinance)

- [llazzaro/analyzer](https://github.com/llazzaro/analyzer)

- <https://www.quantopian.com/posts/technical-analysis-indicators-without-talib-code>


Function            | Notation                                  | Progress
------------------- | ----------------------------------------- | ---------
Content Cell        | Content Cell                              |
Content Cell        | Content Cell                              |
ACCDIST             | Accumulation/Distribution                 | DONE
AD                  | Chaikin A/D Line                          | 
ADOSC               | Chaikin A/D Oscillator                    | 
ADX                 | Average Directional Movement Index        | DONE
ADXR                | Average Directional Movement Index Rating | 
APO                 | Absolute Price Oscillator                 | 
AROON               | Aroon                                     | 
AROONOSC            | Aroon Oscillator                          | 
ATR                 | Average True Range                        | DONE
AVGPRICE            | Average Price                             | 
BBANDS              | Bollinger Bands                           | DONE
BETA                | Beta                                      | 
BOP                 | Balance Of Power                          | 
CCI                 | Commodity Channel Index                   | DONE
CDL2CROWS           | Two Crows                                 | 
CDL3BLACKCROWS      | Three Black Crows                         | 
CDL3INSIDE          | Three Inside Up/Down                      | 
CDL3LINESTRIKE      | Three-Line Strike                         | 
CDL3OUTSIDE         | Three Outside Up/Down                     | 
CDL3STARSINSOUTH    | Three Stars In The South | 
CDL3WHITESOLDIERS   | Three Advancing White Soldiers | 
CDLABANDONEDBABY    | Abandoned Baby | 
CDLADVANCEBLOCK     | Advance Block | 
CDLBELTHOLD         | Belt-hold | 
CDLBREAKAWAY        | Breakaway | 
CDLCLOSINGMARUBOZU  | Closing Marubozu | 
CDLCONCEALBABYSWALL | Concealing Baby Swallow | 
CDLCOUNTERATTACK    | Counterattack | 
CDLDARKCLOUDCOVER   | Dark Cloud Cover | 
CDLDOJI             | Doji | 
CDLDOJISTAR         | Doji Star | 
CDLDRAGONFLYDOJI    | Dragonfly Doji | 
CDLENGULFING        | Engulfing Pattern | 
CDLEVENINGDOJISTAR  | Evening Doji Star | 
CDLEVENINGSTAR      | Evening Star | 
CDLGAPSIDESIDEWHITE | Up/Down-gap side-by-side white lines | 
CDLGRAVESTONEDOJI   | Gravestone Doji | 

## Install

A package is available and can be downloaded from PyPi and installed using:

	$ pip install pandas_talib

## Development

You can help to develop this library.

### Issues

You can submit issues using <https://github.com/femtotrader/pandas_talib/issues>

### Clone

You can clone repository to try to fix issues yourself using:

	$ git clone https://github.com/femtotrader/pandas_talib.git

### Run unit tests

Run all unit tests

	$ nosetests -s -v
	
Run a given test

	$ nosetests tests.test_pandas_talib:test_function -s -v

### Install development version

	$ python setup.py install
	
or

	$ sudo pip install git+git://github.com/femtotrader/pandas_talib.git

### Collaborating

- Fork repository
- Create a branch which fix a given issue
- Submit pull requests

<https://help.github.com/categories/collaborating/>
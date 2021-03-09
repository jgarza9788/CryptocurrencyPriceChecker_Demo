CryptocurrencyPriceChecker
-------------------------------------
[Asset Store Link](http://u3d.as/16VJ)  
© 2017 Justin Garza

PLEASE LEAVE A REVIEW OR RATE THE PACKAGE IF YOU FIND IT USEFUL!
Enjoy! :)

## Table of Contents
<!--TOC-->
- [CryptocurrencyPriceChecker](#cryptocurrencypricechecker)
- [Table of Contents](#table-of-contents)
- [Contact](#contact)
- [Description Features](#description-features)
- [Terms of Use](#terms-of-use)
- [Overview](#overview)
- [Setup](#setup)
- [Scripts](#scripts)
    - [Cryptocurrencies.cs](#cryptocurrenciescs)
    - [Demo0.cs](#demo0cs)
    - [Demo1.cs](#demo1cs)
    - [SimpleJSON.cs](#simplejsoncs)
    - [Other Scripts](#other-scripts)
- [FAQs](#faqs)
    - [Missing Icon for NANO (Known Issue).](#missing-icon-for-nano-known-issue)
    - [Too many requests.](#too-many-requests)

<!--TOC-->

## Contact  

Questions, suggestions, help needed?  
Contact me at:  
Email: jgarza9788@gmail.com  
Cell: 1-818-251-0647  
Contact Info: [jgarza9788 - UnityPortfolio](https://github.com/jgarza9788/UnityPortfolio)  


## Description Features

Allows to display the current price (in USD) of 100 different Crytocurrencies.

* get the current price of 100 different Crytocurrencies.
* 3 sets of icons (color, white, and black).
* Fully commented C# code.
* Easily to use
* Awesome demos!


## Terms of Use

Required:
please follow [Unity's EULA](https://unity3d.com/legal/as_terms) 

Suggestion/Optional:
please put my name in the credits, or in the special thanks section. :)  


## Overview 

This asset is not for trading, buying, or making predictions on Crytocurrencies.  
**I AM NOT RESPONSIBLE FOR YOU BUYING OR SELLING CRYPTOCURRENCIES**
 
This asset will help you do two things. 

* get the current price  
* display the name, symbols, and icon

## Setup
1. get api key from https://coinmarketcap.com/api/
    1. there is an option for a free api key
2. update Cryptocurrencies.cs line 161 and 304.
```cs        
/*EDIT THIS LINE*/
private static string API_KEY = "";
```


## Scripts 

### Cryptocurrencies.cs
contains an array of Cryptocurrencies with a few methods to get the icon(s) and current price.

### Demo0.cs
this script is used for demo0  
![Imgur](https://i.imgur.com/28S0JUCm.png)

### Demo1.cs
this script is used for demo1  
![Imgur](https://i.imgur.com/oZUGE7Bm.png)

<!-- ### MiniJSON.cs
this script has been provided by Calvin Rien (as open source software) -->
### SimpleJSON.cs
This script has been provided by Markus Göbel (Bunny83) (as open source software)

### Other Scripts
The Other scripts are in this asset, but they are not used in the Demos.

## FAQs 

### Missing Icon for NANO (Known Issue).
i know there is a missing icons for nano.

### Error CS0103
```
The name 'HttpUtility' does not exist in the current context  
```
if this error occurs please change the **API Compatibility Level\*** to **.NET Standard 2.0**
![Imgur](https://i.imgur.com/oD23JvV.png)

### Too many requests.
this is an issue with the api, and they provide a payment plan if you need to make more requests.


# TOS Craft Search

> This is a small project on [TOS Wikia, Chinese version](https://tos.fandom.com/zh), corresponding [product link](https://tos.fandom.com/zh/wiki/%E9%BE%8D%E5%88%BB%E6%90%9C%E5%B0%8B%E5%99%A8), by administrator 
[Km14~](https://tos.fandom.com/zh/wiki/%E7%95%99%E8%A8%80%E5%A2%99:Km14~)

It contains script for crawling the craft/龍刻 details from wikia, classifying based on string search and output to wikitext format for use.

# Enviorment
`Python 3.6` with following packages installed
- `bs4` 
- `math`
- `numpy`
- `pandas`
- `re`
- `urllib3`
- `requests-futures`

# Usage
`get_craft_info.ipynb`
- to crawl data from Wikia, results are stored at `crafts.csv`

`craft skill analysis.ipynb`
- to examine a set of keywords for searching

`to wikia.ipynb`
- to translate into wikitext format, data are uploaded to [Wikia](https://tos.fandom.com/zh/wiki/Template:CraftData)

`CraftSearch.js`
- javascript for the search function in [Wikia](https://tos.fandom.com/zh/wiki/MediaWiki:CraftSearch.js)

***
## Credits
The js is a minimal modifictaion from anohter [js](https://tos.fandom.com/zh/wiki/MediaWiki:PetSearch.js), by `Ken2812221` 

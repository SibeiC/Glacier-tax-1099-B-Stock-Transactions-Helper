# Glacier Tax 1099-B Stock Transactions Helper

This is based on [Glacier-tax-1099-B-Stock-Transactions-Helper](https://github.com/JiahaoShan/Glacier-tax-1099-B-Stock-Transactions-Helper) written by [JiahaoShan](https://github.com/JiahaoShan). The original Chrome extension version has been converted to a GreasyFork version for ease of use and easy installation process.

## Description

GreasyFork script for helping nonresident alien fill in the 1099-B stock transactions by importing transactions from local CSV file

## Installation

1. Install [Tampermonkey - Chrome extension](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).
2. Go to [Glacier Tax Prep Stock Transactions Helper - Greasy Fork]().
3. Press install.

## Features

* Automatically validate and fill in 1099 transaction details with imported transaction details (csv)
* CSV should follow the headers 'name,acquired,sold,proceeds,cost'
* Now it enables you to auto fill multiple 1099-B forms

## Tips

* You may use Excel or Numbers to edit and then select to export as CSV format
* You may use online OCR software to help you convert non-selectable 1099 PDF to Excel
* If you get Consolidated Form 1099 PDF from Robinhood, <a href='https://github.com/joshfraser/robinhood-to-csv' target='_blank'>you may export it to .csv file</a>.
* Format for acquired date or sold date: `MM/DD/YYYY`
* CSV Format Example
  <img src="https://lh3.googleusercontent.com/k8PNDDnTFJ2z4VOiSsPIUxDNSabxhn4nICzgoE_42nuMvlV2zt0zpe2_5_XwZCW2AHov9g834A=s1280-h800-e365-rw">
  <img src="https://lh3.googleusercontent.com/lDdUFP9tIUGoKjS2R-fd6oQtLnMqw58OkYT0n6N8TG08RMLTRpZG0jW_d2SA5ynR6jdQaSkNVw=s1280-h800-e365-rw">
  <img src="https://lh3.googleusercontent.com/Jw8WK7jymMCsVztOa3IZQq3rWpo5_BRKVhKBg044jfZH30B7X54VsKtIb1iDD-Ioa9b2KVXw=s1280-h800-e365-rw">
  <img src="https://lh3.googleusercontent.com/I2z1f8Kpf6WpZlIa0Z2iRmJcxliiSp7YmYDwjk7VE1TW6fvO38SXCYoNvySe9L-BiOtcWzGCig=s1280-h800-e365-rw">
* Live Demo
  ![Live Demo](img/Glacier-Tax-Prep-Form-1099-B-Stock-Transactions-Importer-v0.3.2.gif)

* Disclaimer: This is NOT an official app from Glacier Tax.

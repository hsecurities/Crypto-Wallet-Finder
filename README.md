# Cryptocurrency Wallet Finder - Demo Version

![Python](https://img.shields.io/badge/python-3.6+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-1.0-demo-yellow.svg)

**Author:** imshown
**Website:** [https://imshown.com](https://imshown.com)

## ⚠️ Important Notice

This is a **DEMO VERSION** of the Cryptocurrency Wallet Checker with limited functionality.

For the full version with complete features, please visit:
[https://superprofile.bio/vp/crypto-wallet-finder-pro](https://superprofile.bio/vp/crypto-wallet-finder-pro)  
For international Payments send 0.00047BTC to following address **`1DuVFM8961i8fomMm1sxjJhiCgW6YFA5AH`**  
after payment send screenshot to the following telegram `@imshown`  
[t.me/imshown](https://t.me/imshown)

## Features in Demo Version

✅ Basic wallet generation

✅ Limited cryptocurrency support (ETH only)

✅ Maximum 10 wallet checks

✅ Sample output formatting


## Limitations

❌ Limited to 10 wallet checks

❌ Only Ethereum support

❌ Reduced performance

❌ Artificial delays between checks

❌ No batch processing

❌ No advanced features


## Requirements

- Python 3.6 or higher
- Required libraries (install with `pip install -r requirements.txt`)

## Installation for pro version

---
# How to Use `crypto_wallet_finder_pro.py`

This guide provides step-by-step instructions for using the `crypto_wallet_finder_pro.py` script, a simplified version of a more comprehensive tool.

---

## Prerequisites

Before running the script, ensure you have **Python 3.6 or higher** installed on your system. You can download it from the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

---

## Install Required Libraries

The script relies on the following Python libraries: `requests`, `cryptofuzz`, and `asyncio`. Install them by running the following command in your terminal or command prompt:

```bash
pip install requests cryptofuzz asyncio
```
---

## Important Note: `pass.txt`

**Do not delete the `pass.txt` file.** This file contains the words used for password cracking and is essential for the script's functionality.

---

## Run the Script

1.  Navigate to the directory where you have extracted the `crypto_wallet_finder_pro.py` script.
2.  Open your terminal or command prompt in that directory.
3.  Run the script using the following command:

    ```bash
    python crypto_wallet_finder_pro.py
    ```

---

## Using the Script

Once launched, the script will:

* Continuously generate new Ethereum and Dogecoin wallets.
* Concurrently check the balances of these generated wallets.
* Attempt to log into these wallets using the passwords provided in your `pass.txt` file.

If a wallet login is successful, the script will display the wallet details and its corresponding password in your console output.

---

## Stopping the Script

To stop the script at any time, simply press **Ctrl + C** in your terminal or command prompt.

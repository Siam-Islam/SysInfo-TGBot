# SysInfo-TGBot

**Notice**: This script can't run on Windows since psutil can't detect sensors' temperature on Windows. You need to comment out the `get_CPU_Core_Temp()` function.

## Requirements

- python 3.6 
- psutil (5.6.3)
- pyTelegramBotAPI (3.6.6)

## Usage

1. Modify `TOKEN` and `ChatID` variable according to your own telegram bot‘s information.

2. Then run

   ```shell
   python3 run.py
   ```

Tested on a Ubuntu 18.04 server.
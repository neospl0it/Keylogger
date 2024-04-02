# Discord Keylogger

This is a simple Python script that captures keystrokes and sends them to a Discord channel using a webhook. It can be useful for monitoring keyboard activity on your own machine, though please use it responsibly and respect privacy.

## Features

- Captures keystrokes in real-time.
- Dynamically adjusts buffer size based on typing speed.
- Sends keylogs to a Discord channel via webhook.
- Easy setup and customization.

## Requirements

- Python 3.x
- `pynput` library: Install via `pip install pynput`
- `requests` library: Install via `pip install requests`

## Usage

1. Clone or download this repository to your local machine.
2. Replace `'WEBHOOK_URL'` in the script with your actual Discord webhook URL. You can create a webhook for your Discord channel by following [these instructions](https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks).
3. Customize the script as needed, such as adjusting buffer size or keycodes.
4. Run the script using Python: `python keylogger.py`.
5. Press keys on your keyboard, and the keylogs will be sent to the specified Discord channel.

## Customization

- You can customize the script by modifying the keycodes dictionary to include additional key mappings.
- Adjust the buffer size multiplier (`buffer_size_multiplier`) to change how quickly the buffer size adapts to typing speed.

## Note

- Be aware that using keyloggers may be subject to legal restrictions in your jurisdiction. Ensure you have the necessary permissions before using this script.

## Disclaimer

This script is provided for educational purposes only. The author is not responsible for any misuse or damage caused by the use of this script. Use it responsibly and ethically.


# Python Keylogger

This Keylogger is a simple monitoring tool designed to record keystrokes made by a user. Please note that the usage of keyloggers may violate privacy laws and ethical considerations. This program is meant for educational purposes only, and the developer takes no responsibility for any misuse.

## Installation

Before running the keylogger, ensure that you have the required module installed. You can install it using the following command:

```bash
pip install pynput
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/key-logger.git
   ```

2. Navigate to the project directory:

   ```bash
   cd key-logger
   ```

3. Run the keylogger:

   ```bash
   python logger.py
   ```

4. To stop the keylogger, press `Ctrl+C`.

## Configuration

The keylogger saves the recorded keystrokes in a file named `log.txt`. You can customize the file name and other settings by modifying the `keylogger.py` file.

## Permissions (for Mac users)

If you are using a Mac, you may need to grant input monitoring permissions:

1. Go to **Settings > Security & Privacy > Privacy > Input Monitoring**.
2. Tick the checkbox in front of the Terminal or the IDE you are using.

## Disclaimer

This keylogger is intended for educational purposes only. Do not use it for malicious activities. The developer is not responsible for any misuse or legal consequences resulting from the use of this software.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

# SmartEdge

SmartEdge is a Python program designed to enable quick switching between multiple desktops and manage virtual desktops on Windows. It uses the Windows API to perform desktop switching seamlessly.

## Features

- Switch between multiple virtual desktops.
- Manage virtual desktops on Windows.
- Easy to use with a simple command-line interface.

## Requirements

- Windows operating system
- Python 3.x
- Administrator privileges

## Installation

1. Ensure you have Python 3.x installed on your system.
2. Download the `SmartEdge.py` file from this repository.

## Usage

1. Open a command prompt with administrator privileges.
2. Navigate to the directory containing `SmartEdge.py`.
3. Run the program using the following command:

   ```bash
   python SmartEdge.py
   ```

4. The program will start switching between the desktops listed in the `desktops` array in the script.
5. Press `Ctrl+C` in the command prompt to stop the program.

## Customization

- Edit the `desktops` array in the `SmartEdge.py` script to include the names of your virtual desktops.
- Adjust the `DESKTOP_SWITCH_INTERVAL` variable to control how frequently the desktops switch.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
# PatchPlace

PatchPlace is a Python program that centralizes and simplifies the application of software patches on Windows systems to maintain system integrity. It automates the process of identifying and applying available `.msu` patches located in a specified directory.

## Features

- **List Patches**: Scans a directory for available `.msu` patches.
- **Apply Single Patch**: Applies a specified patch.
- **Apply All Patches**: Applies all patches found in the directory.

## Requirements

- Python 3.x
- Windows OS
- Administrative privileges to apply patches
- Patches should be in `.msu` format and stored in a specified directory

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/patchplace.git
   cd patchplace
   ```

2. Ensure Python is installed on your system. You can download it from [python.org](https://www.python.org/).

## Usage

1. Modify the `patch_directory` variable in the `main()` function of `patchplace.py` to point to the directory where your patch files are located.

2. Run the program:

   ```bash
   python patchplace.py
   ```

3. The program will list all available patches and apply each one.

## Logging

PatchPlace uses Python's logging module to provide detailed logs of its operations. By default, it logs to the console. You can modify the logging configuration to log to a file or adjust the logging level.

## Disclaimer

Ensure you have proper backups and have tested patches in a non-production environment before applying them to critical systems. The authors are not responsible for any potential system issues resulting from using this tool.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
# Drop All The Files

![logo](src/logo.png)

An IDA Pro plugin designed to make handling dropped files straightforward. Simply drop files onto IDA's window, and the plugin intelligently processes them based on their type, eliminating the need for manual configuration or analysis setup.

## Features
- **Header files (`.h`, `.hpp`, `.hh`, `.hxx`, `.c`, `.cpp`, `.cc`, `.cxx`)**: Parses the source language declarations using IDA's `ida_srclang` module.
- **TIL files (`.til`)**: Adds the TIL file to the type library.
- **SIG files (`.sig`)**: Plans to apply the IDA signature file.
- **PDB files (`.pdb`)**: Loads the PDB file with type information.
- **Python scripts (`.py`)**: Executes the script in IDA's Python environment.
- **IDC scripts (`.idc`)**: Executes the IDC script.
- **IDS/IDT files (`.ids`, `.idt`)**: Loads IDS/IDT modules.
- **DBG files (`.dbg`)**: Loads debug information from the file.
- **Binary files**: If the Shift key is pressed, maps the file as a binary with manual base address input.
- **Recent Dropped Files List**: Keeps track of recently dropped files for quick access. Use the shortcut `Alt-O` to view and select from the list.

## Installation
1. Copy the `drop_all_the_files.py` file to your IDA plugins directory.
2. Restart IDA Pro.

## Usage
1. Drag and drop supported files onto the IDA Pro window.
2. The plugin will automatically handle the file based on its type.

## Supported Platforms
- IDA Pro with Python 3 and PySide6 installed.

## License
This plugin is provided under the MIT License.

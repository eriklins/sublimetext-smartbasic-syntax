# SmartBASIC Syntax Highlighting for Sublime Text
A Sublime Text syntax definition for Laird Connectivity's SmartBASIC language.

## SmartBASIC
Laird Connectivity’s smartBASIC is an event-driven programming language that was designed to make BLE technology development quicker and simpler, vastly cutting down time to market. A simple smartBASIC application encapsulates the complete end-to-end process of reading, writing, and processing sensor data as well as advertising, connecting, security, power management, and wireless status. See https://www.lairdconnect.com/wireless-modules/bluetooth-modules for more information.

## Syntax Highlighting
Laird provides syntax highlighting files for Notepad++ (Windows) and Textpad (Mac OSX) along with their regular module firmware version releases. This Sublime Text syntax file is based on the latest Notepad++ syntax files for BL652 (FW 28.11.8.0), BL653 (FW 30.2.3.0) and BL654 (FW 29.5.7.2). Other than the original syntax files from Laird, which cover only the language scope of each module's SmartBASIC implementation, this Sublime Text syntax file is a superset of these scopes.

The drawback of this implementation is, that when working on e.g. a BL652 module, Sublime Text would also highlight SmartBASIC functions, which are only available on the higher-end BL653 or BL654 modules. The advantage is, that you only need one syntax file and no need to switch syntax files when working with different modules in parallel.

## File Recognition
SmartBASIC files are usually given names with suffix .sb or .sblib. This Sublime Text syntax definition recognizes both.

## Manual Installation
Place the smartbasic.sublime-syntax file inside the Sublime Text packages User folder (Preferences | Browse Packages...) and restart Sublime Text.

## Install with Package Control
Need to check how to contribute to Package Control...

## License
This package is licensed under the MIT License.

# ChatGPT Terminal App

This is a simple terminal app that allows you to ask to ChatGPT for a command you need on your terminal.

## Installation

To install the app, you can use `pip`:

pip install cgtp_cli


## Usage

To use the app, you can run the following command:

`cgtp-cli 'search the process running in the port 4000'`

You can also use the `-options` flag to display the available options for the command, 
and the `-desc` flag to display the description for the command:

`cgtp_cli search the process running in the port 4000 -options -desc`

You will need a key for the chat-gtp api for this cli. You can set it using the `-key` flag:

`cgtp-cli -key <your-key>`

[//]: <> (include an gif here)

## License

This app is licensed under the MIT License. See the `LICENSE` file for more information.
You can replace the name of the app, the installation instructions, the usage instructions, and the license information with your own information

## Contributing

Fork the project at: https://github.com/edwinsn/cgtp-cli

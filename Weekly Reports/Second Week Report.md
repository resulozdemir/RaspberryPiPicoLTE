# Week 2 Report

## Tasks and Progress Status

### 1. Research and Troubleshooting
- Reviewed the 'CONTRIBUTING.md' file found in the GitHub repository of the SDK, learning about how to make additions to the project, which control methods to use, and how to write commit messages.
- Examined all the code files within the pico_lte SDK to understand the logic behind the operations of the code.
- By examining the file named 'create_your_own_method.py' in the Examples folder, the writing logic of the code for applications to be developed in the future was understood.
- To resolve the modem's internet connection issue, a 'config.json' file was created and configured with the webhook.site URL, then the HTTP get example was executed. The 'register_network()' method was used to establish an internet connection, and a get request was sent. The modem was also sent the 'AT+CREG?' command to check the connection, which successfully returned the output '+CREG: 0,5' indicating a successful connection.

## Pico LTE MicroPython SDK Structure

- The `examples` folder contains examples on how to use various features of the Pico LTE module. These examples are designed to help users work with the different modules and functionalities offered by the SDK.

- The `pico_lte` folder includes `core.py` and `common.py` files, which define the basic configuration and frequently used functions of the Pico LTE module. These files are designed to provide the module's main functions and manage commonly used tools and definitions from a central location among various components of the module.

- The `apps` folder contains examples of applications that integrate with various cloud services and platforms. This includes code examples for AWS, Azure, Thingspeak, Slack, Scriptr, and Google Sheets.

- The `modules` folder contains Python modules for various functions of the Pico LTE module. Among these modules are functionalities such as GPS (`gps.py`), network operations (`network.py`), file operations (`file.py`), communication over HTTP and MQTT protocols (`http.py`, `mqtt.py`), and SSL encryption (`ssl.py`).

- The `utils` folder includes auxiliary tools and functions that facilitate the more efficient use of the module. Among these are functions that simplify communication with AT commands (`atcom.py`), debugging (`debug.py`), and status management (`status.py`).

### References
- [Sixfab Pico LTE - HTTP Request to Web Server](https://docs.sixfab.com/docs/pico-lte-http-request-to-web-server)
- [Sixfab Pico LTE Troubleshooting](https://docs.sixfab.com/docs/sixfab-pico-lte-troubleshooting)
- [Sixfab Pico LTE GitHub Contributing Page](https://github.com/sixfab/pico_lte_micropython-sdk/blob/master/CONTRIBUTING.md)
- [webhook.site](https://webhook.site/)

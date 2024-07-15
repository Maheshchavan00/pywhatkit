# pywhatkit
# WhatsApp Message Scheduler

This Python script uses the `pywhatkit` library to schedule and send WhatsApp messages automatically at a specified time.

## Features

- Schedule a WhatsApp message to be sent at a specific time.
- Easy to use with minimal setup required.

## Prerequisites

- Python 3.x
- An active internet connection
- Logged-in session on WhatsApp Web in your default browser

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/maheshchavan00/whatsapp-message-scheduler.git
    
    cd whatsapp-message-scheduler
    ```

2. Install the required library:

    ```sh
    pip install pywhatkit
    ```

## Usage

1. Open the `send_message.py` file and update the following variables with your details:

    - `phone_number`: Ensure the phone number is in the correct format (e.g., `+91` for India).
    - `message`: The message you want to send.
    - `hour`: The time in hours (24-hour format).
    - `minute`: The time in minutes.

2. Save the file and run the script:

    ```sh
    python send_message.py
    ```

## Example

To send a message "hi buddy" to the phone number `+91.....` at 15:30 (3:30 PM):

1. Update the `send_message.py` file with the appropriate details:

    - `phone_number = '+91.....'`
    - `message = 'hi buddy'`
    - `hour = `
    - `minute = 30`

2. Save the file and run the script:

    ```sh
    python send_message.py
    ```

## Troubleshooting

- Ensure your phone number is in the correct format.
- Make sure your computer is connected to the internet.
- Verify you are logged into WhatsApp Web on your default browser.
- Check your browser settings to ensure pop-ups are allowed and it is not in incognito mode.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.


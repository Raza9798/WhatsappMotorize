## Overview

**WhatsApp Motorize** is an innovative tool designed to simplify sending bulk messages via WhatsApp.

- **Single Click Messaging**: Reach out to multiple contacts effortlessly with just one click.
- **Easy Configuration**: Get started quickly with a straightforward setup.
- **Ideal for Various Uses**: Perfect for notifications, announcements, and promotions.

**WhatsApp Motorize** ensures your bulk messaging needs are met with efficiency and ease.

## Required Applications

- **Node.js**: Ensure you have Node.js installed to run the application.
- **Postman**: Use Postman interact with the application.


## Configuration

| Configuration Step          | Command                                           |
|-----------------------------|---------------------------------------------------|
| **Download or Clone the Repository** | `git clone https://github.com/Raza9798/WhatsappMotorize.git` |
| **Open the Directory**      | `cd WhatsappMotorize`                            |
| **Install Dependencies**    | `npm install`                                    |
| **Start the Application**   | `npm run start`                                  |


## Application URL TO MESSAGE

| Step          | URL                                           |
|-----------------------------|---------------------------------------------------|
| **Setup Contact file and related configration** | `localhost:3000/web.setup` |
| **Send Message**      | `localhost:3000/web.send?message=Hello Test&apiKey=I4LHwm3KmAIzaSyDxWI4LXZ0DP0D9M5671040&type=sendFromList` |


## Contact.json phone number format
The `contact.json` file should include phone numbers in the following format:
```json
[
    94123456789,    /* Sri Lanka */
    15551234567,    /* USA */
    441632960961,   /* United Kingdom */
    4915112345678,  /* Germany */
    33142345678,    /* France */
    61234567890,    /* Australia */
    81312345678,    /* Japan */
    8613800138000,  /* China */
    551199999999,   /* Brazil */
    919167890123,   /* India */
    821012345678,   /* South Korea */
    34123456789,    /* Argentina */
    48212345678,    /* Poland */
    521555123456,   /* Mexico */
    551198765432,   /* Brazil */
    27801234567,    /* South Africa */
    34612345678,    /* Spain */
    43123456789,    /* Austria */
    351212345678,   /* Portugal */
    9823456789      /* Iran */
]
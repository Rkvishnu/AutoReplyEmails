# Gmail-AUto-Reply

This is a Node.js application that automatically sends an auto-reply to unread emails in Gmail using the Gmail API. The application runs as a server and periodically checks for unread messages in the user's inbox. If an unread message is found, it sends an auto-reply and moves the original message to a labeled folder called "AutoReplied".

## Prerequisites

- Node.js (version 12 or higher)
- Gmail API credentials (JSON file)from your google project

## Installation

1. Clone the repository:

```sh
git clone https://github.com/Rkvishnu/AutoReplyEmails.git
```

2. Navigate to the project directory:

```sh
cd AutoReplyEmails
```

3. Install dependencies using npm:

```sh
npm install
```

4. create a .env file inside your route project and add the following credentials:

   - CLIENT_ID= "your client id"
   - CLIENT_SECRET= "your client secret"
   - REDIRECT_URIS= "YOU REDIRECTION URI"

## Usage

1. Start the application:

```text
npm start
```

After that go the url on browser it will redirectr you to the Authentication url
  http://localhost:5000/auth
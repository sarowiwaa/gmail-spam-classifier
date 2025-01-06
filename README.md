# Gmail Spam Classifier

## Description

The Gmail Spam Classifier is a web application that allows users to authenticate with their Gmail account and fetch the latest emails from their inbox. The emails are then analyzed for spam based on a set of predefined keywords and categorized as either **SPAM** or **NOT SPAM**.

This project uses the **Google Gmail API** to fetch the emails and performs simple keyword-based detection for spam classification.

---

## Features

- **Gmail Authentication**: Authenticate with Google using OAuth2 and grant access to read Gmail messages.
- **Fetch Latest Emails**: Retrieve up to 10 messages from the user's Gmail inbox.
- **Spam Detection**: Basic spam classification based on predefined keywords like "win", "free", "urgent", etc.
- **Responsive UI**: Works seamlessly on both desktop and mobile devices.
- **Modern UI Design**: Clean, simple, and user-friendly interface.

---

## Prerequisites

To run this project, you need the following:

1. A **Google Developer Account** to create a project and obtain a **client ID** for OAuth authentication.
2. Basic knowledge of HTML, CSS, and JavaScript.

---

## Getting Started

Follow the steps below to get the project up and running on your local machine:

### 1. Set Up a Google Developer Project

- Go to the **[Google Developer Console](https://console.developers.google.com/)**.
- Create a new project.
- Enable the **Gmail API** for the project.
- Create **OAuth 2.0 credentials** (Web application) and note down the **Client ID**.
- Add the **Client ID** in the `YOUR_CLIENT_ID` placeholder in the code.

### 2. Clone the Repository

If you haven't already, clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/gmail-spam-classifier.git
cd gmail-spam-classifier

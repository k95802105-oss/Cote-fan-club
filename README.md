# Côte de Pablo Fan Club - Setup Guide

Welcome to the Côte de Pablo Fan Club project! Follow this guide to set up the project on your local machine.

## 1. Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/k95802105-oss/cote-fan-club.git
   cd cote-fan-club
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

## 2. Gmail Configuration Instructions

To allow the application to send emails, you need to configure your Gmail accounts. Follow these steps:

1. Go to [Google Account Security](https://myaccount.google.com/security).
2. Scroll down to the "Less secure app access" section and turn it ON. If you have 2-Step Verification enabled, proceed to the next step.

## 3. How to Get App-Specific Password

1. Navigate to the [App Passwords section](https://myaccount.google.com/apppasswords).
2. Select the app you want to generate a password for (choose "Mail") and the device (choose "Other") to label it.
3. Click on **Generate** and note the provided password.

## 4. Environment Variable Setup

Create a `.env` file in the root directory of the project. Add the following configuration variables:

```plaintext
GMAIL_USER=your_email@gmail.com
GMAIL_PASS=your_app_specific_password
``` 
Make sure to replace `your_email@gmail.com` and `your_app_specific_password` with your Gmail address and the generated app-specific password respectively.

## 5. Running the Server

To start the server, use the following command:
```bash
npm start
```
Open your browser and navigate to `http://localhost:3000` to access the application.

## 6. Testing the Form

To test the form functionalities, you can manually navigate to the form page on your local server, or you can run specific test scripts if available within the project. Ensure that your server is running before testing.

---

For any issues or contributions, feel free to open an issue or pull request in the repository!
# 🔐 Two-Step Authentication with OTP via Twilio

This Python script implements a basic two-step authentication mechanism:

1. **Password Validation**
2. **One-Time Password (OTP) Verification via SMS** using [Twilio](https://www.twilio.com/)


## 📜 Features

- Limits login to a configurable number of password attempts
- Sends a randomly generated 6-digit OTP to a user's phone via SMS
- Simple and clear console-based user prompts
- Basic exception handling to manage Twilio and input errors


## 📦 Requirements

- Python 3.x
- Twilio Python SDK

Install Twilio SDK using pip:


pip install twilio

# 🔐 Python Password & OTP Verification

A simple Python script that implements password authentication followed by OTP verification via SMS using Twilio.


## 🧪 How It Works

1. *Password Prompt*  
   The user is prompted to enter a password.

2. *OTP Generation & Delivery*  
   If the password is correct, a 6-digit OTP is generated and sent to the user's phone number via the Twilio SMS API.

3. *OTP Verification*  
   The user is asked to input the OTP received on their phone.

4. *Access Control*  
   - If the entered OTP is correct, access is granted.  
   - If the OTP is incorrect, access is denied.


## 📦 Requirements

- Python 3.x
- Twilio Python library (pip install twilio)
- Twilio account and credentials




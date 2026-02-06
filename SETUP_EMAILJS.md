# EmailJS Setup Guide

Contact form ko bina backend ke kaam karne ke liye EmailJS setup karo:

## Steps:

### 1. EmailJS Account Banao
- Go to: https://www.emailjs.com/
- Sign up for FREE account

### 2. Email Service Add Karo
- Dashboard me jao
- "Add New Service" click karo
- Gmail select karo aur connect karo

### 3. Email Template Banao
- "Email Templates" me jao
- "Create New Template" click karo
- Template content:
```
From: {{from_name}}
Email: {{from_email}}
Subject: {{subject}}

Message:
{{message}}
```
- Save karo aur Template ID copy karo

### 4. Public Key Copy Karo
- Account settings me jao
- Public Key copy karo

### 5. Index.html Update Karo
- Line 283: `YOUR_PUBLIC_KEY` ko apni public key se replace karo
- Line 296: `YOUR_SERVICE_ID` ko apni service ID se replace karo
- Line 296: `YOUR_TEMPLATE_ID` ko apni template ID se replace karo

### 6. Done!
Ab git clone ke baad bhi contact form seedha kaam karega!

Messages directly apke email par aayenge: rani.kumari520527@gmail.com

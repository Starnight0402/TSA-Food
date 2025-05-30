# Training Audit App

This app allows auditors to fill out a training checklist and automatically sends a summary to the specified email address using your Microsoft account.

## Features
- YES/NO/N/A checklist form
- Score calculation and rating
- Email summary via Microsoft SMTP (Outlook)

## Setup

1. Clone the repository
2. Create a `.env` file with:
```
EMAIL_ADDRESS=your_email@outlook.com
EMAIL_PASSWORD=your_app_password
```
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Run locally:
```
python app.py
```

## Deployment
- Deploy to [Render](https://render.com) or similar
- Set environment variables `EMAIL_ADDRESS` and `EMAIL_PASSWORD` in dashboard

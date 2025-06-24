
# Phishing Email Analysis Report

## Sample Email Analyzed

```
From: Amazon Security Team <alert@amaz0n-security.com>
Subject: Unauthorized Login Attempt Detected

Dear User,

We detected an unauthorized login attempt to your Amazon account from a new device located in Russia.

If this was you, no further action is required.

If this was NOT you, please verify your identity immediately to secure your account:

https://amazon-verification-alerts.com/login

Failure to act within 12 hours will result in account suspension.

Stay safe,  
Amazon Customer Security

Attachment: account_recovery_form.zip

```

---

## Identified Phishing Traits


### 1. Spoofed Sender Email
- Email appears to be from Amazon, but the domain is `amaz0n-security.com` with a **“0” instead of an “o”** — a clear attempt at domain spoofing.

### 2. Suspicious Link
- The link `https://amazon-verification-alerts.com/login` is not an official Amazon URL.
- This is a **lookalike phishing domain** intended to steal login credentials.

### 3. Social Engineering (Fear Tactic)
- Mentions a login attempt from **Russia** to create fear.
- This is used to **scare the user** into clicking the link without thinking.

### 4. Urgent Language
- “Failure to act within 12 hours will result in account suspension.”
- Creates panic to make the victim act quickly.

### 5. Generic Greeting
- Uses “Dear User” instead of the recipient’s real name.
- Legitimate Amazon emails usually address users by name.

### 6. Dangerous Attachment
- Includes `account_recovery_form.zip`, which is highly suspicious.
- Could contain malware or a fake form to steal user data.
---

## Conclusion

This phishing email uses multiple deceptive techniques:
- A spoofed sender domain  
- Scare tactics  
- Fake links  
- Dangerous attachment  
- A strong sense of urgency  

It is designed to trick the recipient into clicking a malicious link or opening a harmful file, and should be deleted or reported immediately.

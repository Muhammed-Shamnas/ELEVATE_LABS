# 🛡️ Elevate Labs Internship - Task 2: Phishing Email Analysis

## 🎯 Objective

Analyze a suspicious email to identify phishing tactics and understand how to spot and report potential email-based attacks.

---

## 📧 Sample Email Analyzed
From: Amazon Security <support@amazon-securelogin.com>
To: you@example.com
Subject: Urgent! Account Suspended!

Dear Customer,

We noticed suspicious login attempts on your Amazon account from a new device.  
To protect your account, we have temporarily suspended it.

Please verify your identity immediately by clicking the secure link below:

🔗 http://amaz0n.secure-verify-login.com/verify

Failure to verify within 24 hours will result in permanent account suspension.

Thank you,  
Amazon Security Team

[Attached File: Amazon_Invoice.pdf.exe]
---

## 🔍 Phishing Indicators Found

| 🕵️‍♂️ Clue | 📖 Explanation |
|------------|----------------|
| Spoofed sender | The email is from amazon-securelogin.com, not an official Amazon domain. |
| Suspicious link | Link uses amaz0n instead of amazon – a common trick to fool users. |
| Urgency & fear | Claims account will be "suspended within 24 hours" to scare the user. |
| Attachment | Attached .exe file disguised as a PDF — potentially malicious software. |
| Generic greeting | Uses "Dear Customer" instead of a real name. |
| Spelling/grammar issues | Slightly awkward phrasing, lack of personalization. |

---

## 🧪 Header Analysis (Optional)

Although no real headers were analyzed in this task, tools such as the following can be used in future investigations:

- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- [Google Apps Toolbox Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)

These tools can show:
- Whether the email passed SPF, DKIM, and DMARC validation
- The actual source IP of the sender
- Signs of spoofing or forgery

---

## 🛡️ What Is Phishing?

Phishing is a type of cyber attack where an attacker pretends to be a trustworthy source (like a bank, company, or government agency) and tricks users into:
- Clicking on malicious links
- Downloading infected files
- Giving away sensitive info like passwords or credit card numbers

---

## 🧠 Key Learnings

- How to spot phishing tactics in fake emails.
- The importance of verifying links, sender addresses, and file attachments.
- Awareness of social engineering tricks used to manipulate users.
- How email threats can lead to malware infections, data theft, or financial loss.

---

## 📁 Files Included in This Repository

| File | Description |
|------|-------------|
| sample_phishing_email.txt | The fake phishing email used for analysis |
| README.md | This explanation file |

---

## ✅ Conclusion

This task improved my ability to detect phishing attacks and understand the tactics used by cybercriminals to exploit trust. Recognizing and reporting phishing emails is a critical part of defending against modern cyber threats.

---

## 👨‍💻 About Me

I’m Muhammed Shamnas K, a cybersecurity intern at Elevate Labs, pursuing my journey to become a skilled cyber analyst through hands-on learning, real-world simulations, and continuous exploration of threat detection techniques.

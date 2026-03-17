# Question 6: 6.	Discover cryptographic implementation used offline

## Description
I used 7-Zip, a file compression tool, to explore offline cryptography. When creating a compressed archive, 7-Zip allows you to set a password and enable encryption. This ensures that anyone without the correct password cannot access the files inside. This demonstrates how encryption protects sensitive data locally, similar to how it works online.

## Proof of Research
To prove that 7-Zip is a reliable tool for offline security, I looked up its official technical specifications. I found that it uses **AES-256 encryption**, which is the same high-level standard used by governments and banks to keep data safe. 

The screenshot below shows the official site confirming this feature. This research gave me the confidence that using 7-Zip isn't just "hiding" a file, but actually locking it with strong cryptography.

![WhatsApp Image 2026-03-17 at 4 26 14 PM](https://github.com/user-attachments/assets/c859a659-f8f1-49cd-9164-f21d04395c87)


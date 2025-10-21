🎣 IRCTC Refund Phishing Analysis
Welcome to this short case study on a phishing email investigation. In this task, I analyzed a suspicious email pretending to be from IRCTC and uncovered several classic phishing indicators.

🕵️ What I Did
Collected the Sample: Acquired a phishing email claiming a ₹4,240 refund from "IRCTC Helpdesk."

Checked the Sender Address: The first red flag was the sender's address: irctc-helpdesk@securesupportcloud.com. This is an immediate giveaway, as it doesn't use the official irctc.co.in domain.

Analyzed the Email Header with MXToolbox: I extracted the email's raw header and used an online tool like MXToolbox to analyze its authenticity. The tool confirmed that the email failed security checks like SPF and DKIM, proving it was sent from an unauthorized server and was not legitimately from IRCTC.

Identified Phishing Traits: The email body was full of classic scam tactics:

The Bait 💰: A false refund offer to trigger an emotional response.

Urgency: A tight deadline ("Link expires in 2 days") to rush the user into making a mistake.

The Hook: A suspicious QR code—a modern trick to hide a malicious link and direct users to a credential-stealing website.

Documented Findings: All red flags were compiled and summarized for security awareness.

🚩 Key Indicators Found
Fake Domain: The sender's domain (securesupportcloud.com) impersonates the official IRCTC brand.

Failed Email Authentication: The MXToolbox analysis showed SPF/DKIM failures, confirming the sender is spoofed.

Emotional Manipulation: The email uses greed (the refund) and urgency (the deadline) to bypass rational thinking.

Unusual Call to Action: A QR code is used to obscure the malicious destination, a common tactic for phishing.

🧠 Takeaway
This exercise shows how easily scammers exploit trust and urgency. Even a simple check with a tool like MXToolbox can definitively prove an email is fraudulent.

Always double-check sender domains, never trust QR codes in unsolicited emails, and verify any alerts directly on the company's official website.

Stay sharp—that tempting "refund" might just be the hook. 🎯

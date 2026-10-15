Version: NAFATH-V1
Track: Networking 
## Overview
NAFATH is a secure login service that allows people to use one account to access different government services. People can use the service through a mobile app or a website. Since the service uses personal information, it is important to keep this information safe. The system must check that users are who they say they are and stop people from accessing accounts without permission. This mission covers six topics: software, AI, mobile apps, networking, cybersecurity, and data protection. Each topic helps make the service safer and easier to use. Software helps manage user login, AI can help find unusual login activity, and mobile apps need to protect user information. Networking helps protect data sent over the internet. Cybersecurity helps protect accounts from attacks, while data protection helps keep personal information safe. The main goal is to understand these topics and learn how to make NAFATH safe and reliable for everyone.

## Software
OAuth 2.0 and OpenID Connect have different jobs. OAuth 2.0 allows an app to access certain information or services with the user's permission. OpenID Connect helps the app check who the user is when they sign in. For NAFATH, OpenID Connect can be used to verify a citizen's identity, while OAuth 2.0 can give permission to access a specific government service. Using the correct method helps protect user accounts and information.
Resource: How OpenID Connect Works - https://openid.net/developers/how-connect-works/

## AI
The NIST AI Risk Management Framework helps organizations find and manage risks when using AI. In NAFATH, AI could help detect unusual login attempts. Before using this system, the team should check if it makes mistakes, misses real attacks, or treats some users unfairly. They should also protect personal information and test the system before launch. Regular checks are important to make sure the AI works well and keeps users safe.
Resource: AI Risk Management Framework - https://www.nist.gov/itl/ai-risk-management-framework

## Mobile
Android asks users for permission when an app needs access to certain features or information, such as location or the camera. In NAFATH, the mobile app should ask for permission only when it needs it. For example, it should explain why location access is needed before asking for it. The app should not request unnecessary permissions. This helps protect users' privacy and gives them more control over their information.
Resource: Request app permissions - https://developer.android.com/training/permissions

## Networking
DNS over HTTPS (DoH) protects DNS requests by sending them through an encrypted connection. This makes it harder for other people on the network to see which website names a user is looking for. In NAFATH, DoH can help protect users when they connect to the service. However, it does not hide all online activity, guarantee that a website is safe, or stop every cyberattack. Other security measures are still needed to protect users and their information.
Resource: DNS over HTTPS - https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/

## Cybersecurity
Phishing-resistant multi-factor authentication (MFA) helps protect users from fake login pages that try to steal their login details. For NAFATH, using passkeys or FIDO2 security keys can provide strong protection against phishing. However, SMS codes, email codes, and normal approval notifications may still be tricked or stolen. The system should use phishing-resistant methods to help keep citizen accounts safe and reduce the risk of unauthorized access.
Resource: Implementing Phishing-Resistant MFA - https://www.cisa.gov/sites/default/files/2023-01/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf

## Data
Oman's Personal Data Protection Law was issued under Royal Decree No. 6/2022. It aims to protect people's personal information. Before processing personal data, the controller or processor must get the person's consent when required by law. People have rights over their data, including withdrawing consent and asking to correct, update, or delete their information. They must also be informed about personal data breaches as required by law. NAFATH should follow these rules when collecting and storing citizens' information.
Resource: Personal Data Protection Law - https://mtcit.gov.om/ar/3/8/75/1034

## Misconception in My Track
## Open Question

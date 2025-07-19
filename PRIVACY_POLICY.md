# RacketUp Privacy Policy

**Last Updated: 6/19/2025**

## 1. Introduction

The RacketUp ("RacketUp", "we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our website, mobile application, and any related services (the "Service"). By using the Service, you consent to the practices described in this Privacy Policy.

## 2. Information We Collect

### 2.1. Personal Information Provided by You

When you register for an account or use certain features of our Service, you may provide us with the following information:

- **Contact Information:** Full name and email address.
- **Account Credentials:** Username and password (which we securely hash using bcrypt).
- **Profile Information:** Height, weight, bio, and profile picture.
- **Verification Documents:** A government-issued photo ID is required for account verification (required for ranked matches). Note that although you upload a photo for verification purposes, the image is used solely for automated verification with our AI service (via AWS Textract) and is deleted immediately after processing.
- **Preferences:** Various settings that control how your information is displayed and how you interact with other users (e.g., messaging preferences).
- **Additional Data:** Information related to match history, scores, and messaging content, which may include on service text messages, friend requests, reports, notifications, and match details.
- **League Information:** When creating or joining leagues, we collect league names, membership information, league settings, and league profile pictures.
- **QR Code Data:** When using QR code functionality to join matches, we process the encoded match information.

### 2.2. Automatically Collected Information

When you use our Service, we may automatically collect certain information about your usage:

- **Usage Data:** Information about your interactions with the Service (e.g., pages accessed, match history, game statistics, league participation).
- **Log Data:** Details such as IP addresses, browser type, operating system, and access times.
- **Authentication Data:** JSON Web Tokens (JWTs) that facilitate secure sessions and verify your identity.

## 3. How We Use Your Information

We use the collected information for various purposes, including:

- **Account Management:** To create, maintain, and secure your account; to verify your identity during registration and for ranked matches; and to enable password resets.
- **Service Delivery:** To facilitate online matchmaking, record match outcomes, update player statistics, and support game-related communications.
- **League Management:** To create and manage leagues, process league invitations, handle league membership, and facilitate league-specific match history.
- **QR Code Functionality:** To process QR codes for match joining and verification purposes.
- **Communication:** To send verification emails, password reset links, and notifications regarding friend requests, match updates, disputes, league invites, or other account-related matters.
- **Customer Support:** To respond to your inquiries and resolve technical or security issues.
- **Improvement of Services:** To analyze usage trends and improve the functionality and performance of our Service.
- **Compliance and Security:** To detect, prevent, and address security breaches, fraud, or any unauthorized use of our Service.

## 4. Disclosure of Your Information

### 4.1. Third-Party Service Providers

We may share your information with third parties that help us operate our Service, including:

- **Cloud and Database Services:** Our data is stored in a MongoDB database.
- **Email Service Providers:** We use Flask-Mail (and related SMTP services) to send emails.
- **ID Verification Services:** AWS Textract is used for verifying uploaded identification documents. Please note that while we process your ID photo using AWS Textract, the image is not stored after verification.
- **Image Storage Services:** AWS S3 is used for storing profile pictures, league pictures, and other media content.
- **Other Third Parties:** Any additional integrations or services may have access only to the information required to perform their functions and are bound by confidentiality agreements.

### 4.2. Legal Disclosures

We may disclose your information if required to do so by law or in the good-faith belief that such action is necessary to:

- Comply with a legal obligation.
- Protect and defend our rights or property.
- Prevent or investigate possible wrongdoing in connection with the Service.
- Protect the personal safety of users of the Service or the public.

## 5. Data Storage and Security

### 5.1. Data Storage

- **Personal Data:** Your account information, match history, messages, league membership data, and related information are stored in our MongoDB database.
- **Uploaded Media:** Profile pictures, league pictures, and article images are stored on our server (in designated upload folders) or in AWS S3 storage. All media files are subject to the access and retention policies described below.
- **Temporary Data:** ID verification photos are processed using AWS Textract and are deleted immediately after verification; they are not stored on our backend.
- **QR Code Data:** QR code data is processed in real-time and is not stored separately from the match information it represents.

### 5.2. Security Measures

We take reasonable precautions to protect your information from loss, misuse, unauthorized access, disclosure, alteration, or destruction. These measures include:

- **Encryption:** Passwords are hashed using encryption, and sensitive data transmissions are protected by HTTPS.
- **Access Controls:** Access to personal data is limited to authorized personnel who require such access to operate, develop, or improve our Service.
- **Regular Audits:** We perform regular security reviews and updates to ensure the integrity and security of our systems.
- **Data Minimization:** We retain only the data necessary for the purposes outlined in this Privacy Policy.

### 5.3. Retention

We retain your personal information for as long as necessary to fulfill the purposes for which it was collected and to comply with applicable legal requirements. When no longer needed, we securely delete or anonymize your data.

## 6. Your Rights and Choices

### 6.1. Account Access and Updates

- **Viewing and Editing:** You may access, update, or correct your personal information by logging into your account and adjusting your settings.
- **Deletion:** You may request the deletion of your account and associated data by contacting us at the email address provided below. Please note that certain information may need to be retained for legal or security purposes.
- **Account Deletion Process:** When you delete your account, we use a "soft delete" approach that anonymizes your personal information while preserving the integrity of match history and league data. Specifically:
  1. Your personal information (name, email, bio, height, weight) is either anonymized or removed.
  2. Your username is changed to "Deleted Account" and your profile picture is removed.
  3. Your account is marked as deleted with a timestamp.
  4. Your friends list is emptied, but your account remains visible as "Deleted Account" in other users' friends lists.
  5. All pending friend requests involving your account are removed.
  6. Your notifications are deleted.
  7. Your match history and statistics remain in the system to maintain game integrity and other users' records.
  8. Your league memberships remain, but your username shows as "Deleted Account" in league rosters and match history.

  This approach ensures that deleting your account doesn't break the application's functionality for other users while still respecting your privacy by removing your personal information.

### 6.2. Communication Preferences

- **Opting Out:** You can opt out of receiving marketing communications by following the unsubscribe instructions in our emails. Please note that you may still receive transactional or service-related messages.

### 6.3. Data Portability and Access Requests

Subject to applicable law, you may request access to, correction of, or deletion of your personal data. To exercise these rights, please contact us at the address provided below.

## 7. Children's Privacy

Our Service is not directed to individuals under the age of 16. We do not knowingly collect personal information from children under 16. If we become aware that we have collected personal information from a child under 16, we will take steps to delete the information as soon as possible.

## 8. International Data Transfers

If you are accessing our Service from outside the United States, please be aware that your information may be transferred to and stored on servers located in the United States or other countries where our service providers operate. By using our Service, you consent to the transfer of your information to these jurisdictions.

## 9. Third-Party Links and Integrations

Our Service may contain links to third-party websites or services that are not operated by us. We are not responsible for the privacy practices of these third parties. We encourage you to review the privacy policies of any third-party sites you visit.

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. When we make material changes, we will provide notice by updating the "Last Updated" date at the top of this policy and, in some cases, by notifying you directly via email or through the Service. Your continued use of the Service after such changes will constitute your acceptance of the updated policy.

## 11. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us at:

**Email:** connectwithoba@gmail.com

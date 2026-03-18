# Privacy Policy for PackStream

**Last updated: 20 February 2026**

PackStream ("we", "our", or "us") is committed to protecting your privacy. This policy explains what information we collect, how we use it, and your rights regarding that information.

---

## 1. Who We Are

PackStream is developed and operated by Erick (an independent developer based in Melbourne, Australia). You can contact us at: **packstreamsuite@gmail.com**

---

## 2. What Information We Collect

### 2.1 Account Information
When you create an account, we collect:
- Your **email address**
- A **password** (stored securely via AWS Cognito — we never see your password in plain text)

### 2.2 Trip and Packing List Data
When you create and save packing lists, we store:
- Trip details you enter (destination city names, travel dates, trip duration, planned activities)
- The packing list items generated from your trip details
- Your list names and any customisations you make

This data is stored in our database (AWS DynamoDB, hosted in Sydney, Australia) and linked to your account.

### 2.3 Location and Weather Data
To generate weather-appropriate packing recommendations, we send your **entered city names** to the OpenWeather API ([openweathermap.org](https://openweathermap.org)). We do not access your device's GPS or physical location. Please refer to [OpenWeather's Privacy Policy](https://openweather.co.uk/privacy-policy) for how they handle this data.

### 2.4 Local Cache Data
PackStream caches your packing lists locally on your device to support offline use. This data is stored only on your device and is cleared when you log out or uninstall the app.

### 2.5 What We Do NOT Collect
We do not collect:
- Analytics or usage tracking data
- Device identifiers or advertising IDs
- Crash reports or diagnostic telemetry
- Payment information (the app is currently free)
- Any data from your contacts, camera, microphone, or other device sensors

---

## 3. How We Use Your Information

We use the information we collect solely to:
- Authenticate you and secure your account
- Store and retrieve your saved packing lists across devices
- Generate weather-based packing recommendations for your trips
- Allow you to share your packing lists (only when you explicitly choose to do so)

We do not use your data for advertising, profiling, or any purpose beyond operating the app.

---

## 4. How We Share Your Information

We do not sell, rent, or trade your personal information.

We share data only with the following third-party services necessary to operate the app:

| Service | Purpose | Data Shared | Region |
|---|---|---|---|
| AWS Cognito | User authentication | Email address | Sydney, AU (ap-southeast-2) |
| AWS DynamoDB | Storing packing lists | Trip and list data | Sydney, AU (ap-southeast-2) |
| AWS API Gateway + Lambda | App backend | Trip and list data | Sydney, AU (ap-southeast-2) |
| OpenWeather API | Weather data | City names you enter | EU (OpenWeather servers) |

All AWS services used are hosted in the **ap-southeast-2 (Sydney)** region.

---

## 5. Data Retention

- **Account data** is retained for as long as your account is active.
- **Packing list data** is retained until you delete individual lists or delete your account.
- You can delete your packing lists at any time from within the app.
- To request full account deletion, contact us at **packstreamsuite@gmail.com** and we will delete your data within 30 days.

---

## 6. Data Security

We take reasonable steps to protect your data:
- Passwords are managed by AWS Cognito and are never stored or visible to us
- All data in transit is encrypted using HTTPS/TLS
- AWS infrastructure is secured using industry-standard access controls
- Your account data is stored in Australia

No method of electronic storage or transmission is 100% secure. We cannot guarantee absolute security, but we are committed to using best practices.

---

## 7. Children's Privacy

PackStream is not directed at children under the age of 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, please contact us and we will delete it promptly.

---

## 8. Your Rights

Depending on your location, you may have rights regarding your personal data, including:
- **Access**: Request a copy of the data we hold about you
- **Correction**: Ask us to correct inaccurate data
- **Deletion**: Request deletion of your account and associated data
- **Portability**: Request your packing list data in a portable format

To exercise any of these rights, contact us at **packstreamsuite@gmail.com**.

If you are located in Australia, you may also lodge a complaint with the [Office of the Australian Information Commissioner (OAIC)](https://www.oaic.gov.au/) if you believe your privacy rights have been breached.

---

## 9. Changes to This Policy

We may update this privacy policy from time to time. When we do, we will update the "Last updated" date at the top of this page. For significant changes, we will notify you within the app. Continued use of PackStream after changes are posted constitutes your acceptance of the updated policy.

---

## 10. Contact Us

If you have any questions about this privacy policy or how we handle your data, please contact:

**Erick**
Email: **packstreamsuite@gmail.com**
Location: Melbourne, Victoria, Australia

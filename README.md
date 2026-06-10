# Privacy Policy

**Effective Date:** June 10, 2026  
**Last Updated:** June 10, 2026

Welcome to the **QR Code Scanner** ("the App"). We are committed to protecting your personal privacy. This Privacy Policy outlines how your information is collected, used, shared, and protected when you download, install, and use the App, particularly in compliance with major global privacy standards, including the **General Data Protection Regulation (GDPR)**, **California Consumer Privacy Act (CCPA)**, and the publishing requirements of the **Huawei AppGallery** and **Google Play Store**.

Please read this Privacy Policy carefully. By using the App, you consent to the terms of this Privacy Policy. If you do not agree with these terms, please do not use the App.

---

## 1. About the App
The App is built as an offline-first tool optimized for speed, reliability, and security. Features include:
*   Scanning and decoding QR codes/barcodes via the camera.
*   Generating high-quality custom QR codes and bar codes.
*   Saving a persistent history of scans locally on your device.
*   Displaying standard banner, interstitial, and rewarded ads provided by premium network SDK partners (Google AdMob and Huawei Petal Ads) to sustain free updates.

---

## 2. Information We Collect and Process
As a fundamental philosophy, the App is designed to minimize data collection. We do not operate secondary backend services or cloud storage databases, and we do not collect any personally identifiable information (PII) like names, email addresses, phone numbers, or account details.

The following categories of data are processed or utilized:

### A. Device Permissions and System Access
To perform its core functions, the App requires specific Android system permissions. You can grant or revoke these permissions at any time through your device settings:
*   **CAMERA ACCESS (`android.permission.CAMERA`):**
    *   **Purpose:** Required exclusively to activate your device's camera sensor, capture real-time physical video frames, and scan and decode QR/barcodes.
    *   **Processing:** All camera analysis, frame processing, and barcode decoding occur **locally and completely in memory on the device**. Live camera streams are never sent, cached, saved, or uploaded to any external server or network.
*   **INTERNET ACCESS (`android.permission.INTERNET`, `android.permission.ACCESS_NETWORK_STATE`):**
    *   **Purpose:** Required to allow third-party ad networks (Google AdMob and Huawei Petal Ads) to retrieve ad creatives, load ad segments, and maintain offline-ad buffering configurations, as well as to enable user-initiated navigation when clicking external decoded URLs or reading the official privacy policy webpage.

### B. Local Scan and Creation History
*   The App keeps a private, local database of your scanned and created codes to provide history features.
*   **Storage:** This data is written into the App's private database sandbox using Android's SQLite/Room architecture.
*   **User Control:** This data remains strictly physical on your handset. We do not sync it to any cloud servers. You retain absolute control over your history; you can delete individual history records or wipe the entire database at any time through the App's settings or by clearing the App's system cache.

---

## 3. Third-Party Software Development Kits (SDKs) and Ad Partners
The App integrates standard third-party advertising SDK networks. To support continuous development and maintenance without charging user fees, these ad integrations automatically compile standard network telemetry:

### A. Google AdMob (Google Ireland Limited)
Google AdMob provides contextual and targeted advertising within the App.
*   **Information Processed:** Device identifiers (e.g., Google Advertising ID - GAID, Android ID), IP address, device model, operating system version, and general ad engagement telemetry.
*   **Privacy Policy:** For more information on how Google manages tracking data, please consult [Google’s Privacy & Terms](https://policies.google.com/privacy).

### B. Huawei Petal Ads / HMS Core (Huawei Services (Hong Kong) Co., Limited)
In compliance with the Huawei AppGallery developer policies, the App utilizes Huawei HMS Core and Petal Ads services for devices running Huawei Mobile Services (HMS).
*   **Information Processed:** OAID (Open Advertising Identifier), network status, carrier details, language preferences, device brand/model, screen dimensions, and ad view interaction rates.
*   **Privacy Policy:** To understand more about Huawei's data processing on HMS devices, please reference the [Huawei Petal Ads Privacy Statement](https://ads.huawei.com/).

These third-party platforms may utilize cookies, device identifiers, or similar technologies to personalize and measure ad display, limit same-ad repetitions, or optimize layout relevance. You may manage or opt out of personalized ad tracking inside your device settings (e.g., Android Settings > Google > Ads > Opt out of Ads Personalization, or HMS Settings > Privacy > Ads and Personalization).

---

## 4. Children’s Privacy
The App complies with the **Children’s Online Privacy Protection Act (COPPA)** and similar policies.
*   We do not intentionally or knowingly target children under the age of 13.
*   No personal data is collected or stored within the App.
*   If we learn that any kid-specific identifier was mistakenly transferred from an ad network, we will coordinate to wipe that log immediately.

---

## 5. Security and Data Retention
Because the App operates offline-first, your personal data is essentially non-existent inside our databases.
*   **Local Data Security:** Local data stored in the SQLite database is protected under Android's built-in sandbox security framework, which isolates the database from other third-party software on the handset.
*   **Transmission Protection:** Although we do not transmit profile information, any outbound request (like opening a scanned URL or fetching an ad creative) is secured using standard **HTTPS** transport TLS protocols.

---

## 6. Access and User Rights (GDPR & CCPA Compliance)
Depending on your regional jurisdiction (such as the European Economic Area under GDPR or California under CCPA), you are entitled to several specific rights regarding your digital information:
1.  **Right to Access and Port Data:** Since your entire history lives within the physical database of your phone, you can access it directly by executing local features and viewing the history page.
2.  **Right to Erase / Delete Data:** You have the absolute right to purge your local data. Simply click the "Clear History" options in the App or perform a complete uninstall, which safely and irreversibly blocks the sandboxed database directory from your system memory.
3.  **Right to Opt-Out of Tracking:** You hold the option to reset or restrict your mobile advertising identifiers (GAID, OAID) on your handset settings at any time.

---

## 7. Global Consents and AppGallery Verification
To comply with the latest Huawei AppGallery publishing instructions, the App serves a hard-blocked welcome modal on its immediate first launch. This requires you to explicitly click "Agree" on the privacy rules and understand:
*   We request Camera permissions only when you launch the Scanner screen.
*   Ad networks require network state access to display ads.
*   Declining the screen will exit the App to respect your explicit data security demands.

If you have already consented, you can view the policy documentation from our website or by selecting options in the Settings page.

---

## 8. Amendments and Changes
We reserve the right to revise or update this Privacy Policy at any time. If modifications are made, the newly revised "Effective Date" at the top of this document will be updated. We encourage you to review the statement periodically to stay informed of our commitment to safeguarding device privacy.

---

## 9. Contact Us
If you have any questions, comments, or concerns regarding this Privacy Policy, please contact us at:

**Developer Support Team**  
*   **Email:** [micromindes@gmail.com](mailto:micromindes@gmail.com)  
*   **Privacy Portal:** [https://micromindes.github.io/qr-scanner-privacy/privacy.html](https://micromindes.github.io/qr-scanner-privacy/privacy.html)

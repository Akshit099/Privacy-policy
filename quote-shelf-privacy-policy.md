# Privacy Policy for Quote Shelf

**Effective Date:** February 1, 2026

At **Quote Shelf**, we value your privacy and are committed to protecting your personal data. This Privacy Policy explains how our mobile application handles information when you use our services.

## 1. Information Collection and Use
Quote Shelf is designed as an **offline-first, privacy-focused** application. We do not require you to create an account, provide an email address, or link your social media profiles to use the app.

### A. Personal Data
We use **Firebase Anonymous Authentication** to provide you with a unique, silent identifier. This allows us to handle book requests and secure our database without knowing your identity. We do not collect names, email addresses, or phone numbers.

### B. Book Requests
When you use the "Request a Book" feature, the Book Title and Author name you provide are uploaded to our Firestore database. This information is used solely to improve our global library for all users.

### C. On-Device Processing (OCR & Voice)
*   **Camera:** When you use the OCR scanner, image processing happens **entirely on your device** using Google ML Kit. We do not upload, store, or see your photos.
*   **Microphone:** When you use voice input, audio transcription is handled by the **Android Speech API**. We do not record, store, or transmit your voice data to our servers.

## 2. Permissions
To provide its core features, the app requests the following permissions:
*   **Camera:** To scan physical book pages for text extraction.
*   **Microphone:** To allow for voice-to-text note creation.
*   **Notifications:** To alert you when a book you requested has been added to the library.
*   **Storage/Media Picker:** To allow you to import quotes from images/screenshots in your gallery and to save backup files.

## 3. Data Storage and Backups
*   **Local Storage:** All your saved quotes, notes, and book covers are stored locally on your device using an encrypted Room database.
*   **Manual Backups:** If you use the "Backup" feature, the app generates a JSON file. This file is saved to a location of your choice (e.g., Google Drive or local storage). We do not have access to your backup files.

## 4. Third-Party Services
We use Firebase (a Google service) to power our global library and notifications. These services may collect certain standard information:
*   **Firebase Firestore:** Stores the public book library and anonymous book requests.
*   **Firebase Cloud Messaging (FCM):** Used to send notifications regarding book requests.
*   **Google Play Integrity:** Used via Firebase App Check to protect our database from bot attacks and ensure the app is used on a legitimate device.

## 5. Data Security
We implement industry-standard security measures, including Firebase App Check and Firestore Security Rules, to protect the integrity of our database and your anonymous requests.

## 6. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. You are advised to review this page periodically for any changes. Changes are effective immediately after they are posted on this page.

## 7. Contact Us
If you have any questions, feedback, or concerns regarding privacy or security, please feel free to contact the developer at: akshitdev.apps@gmail.com

Mobile-Based Self-Checkout System
A fully functional mobile self-checkout Android application designed for retail stores. The system allows customers to scan products, manage their shopping cart, apply discounts, and securely process payments — all directly from their smartphones.
This project is distributed as an Android APK for easy installation and testing.

Table of Contents
Overview

Features

Tech Stack

Installation

Usage


Future Improvements

Overview

This project implements a mobile-based self-checkout application that directly addresses common issues in traditional checkout systems like long queues, limited self-service kiosks, and complex discount applications.
By combining advanced barcode scanning, real-time cart management, secure digital wallets, and multiple payment methods — including M-Pesa and Google Pay — this application delivers a smooth, localized, and efficient shopping experience.

Features
📷 Barcode Scanning: Powered by Google ML Kit for instant and accurate product scanning.

🛒 Virtual Cart: Real-time cart management with add, update, and delete item functionality.

🎟 Digital Wallet: stores and allows user to apply vouchers, promo codes, and loyalty points.

💳 Multiple Payment Methods: Fully integrated with M-Pesa, Google Pay, and customer loyalty payment solutions.

📶 Offline Support: Continue shopping even without internet; syncs data automatically when online.

🔐 Persistent Login: Seamless login experience for returning users.

📃 Digital Receipts: Contactless receipt generation for easy store exit.

🌍 Localization: Specifically tailored for regions with inconsistent network access and strong mobile money adoption.

Tech Stack

Platform: Android (Java, Android Studio)

Backend: Firebase Firestore (Database, Authentication, Storage)

ML Integration: Google ML Kit (Barcode Scanning API)

Payments: M-Pesa API, Google Pay API


Installation

✅ No coding setup required — simply install the APK and start using the application.

Install from GitHub Release
Go to the Releases section of this repository.
Download the  ShoppingApp.apk file.
Transfer the APK to your Android device.
On your Android device, enable Install from Unknown Sources (Settings > Security).
Install the APK and launch the app.

Open the app and log in.

Scan products via barcode scanner.
Manage cart items in real-time.
Apply coupons, vouchers, loyalty points.
Select a payment method (M-Pesa, Google Pay,cusotmer points, vouchers, promocodes etc.)
Confirm purchase and receive digital receipt.

Future Improvements

NFC product scanning.

Multi-language support.

Biometric authentication for secure checkout.

Expand payment gateway integrations and payment options(cryptocurrency).

Leveraging user data(for tailored recommendations)




Note:
This project serves as a proof-of-concept / demo solution for mobile-based self-checkout systems. It is not yet production ready for deployment in live retail use.


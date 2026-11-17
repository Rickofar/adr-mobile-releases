# adr-mobile-releases

**Public release binaries for the ADR Business Suite mobile app.**

This repository hosts the public release artifacts (APK files) for **ADR Business Suite Mobile**. The source code is maintained separately in a private repository.

---

## 📥 Download

### Latest Version

| Platform | Download |
|----------|----------|
| 🤖 **Android (APK)** | [Download from Releases](../../releases/latest) |

> 💡 **Coming soon:** iOS App Store and Google Play Store versions.

---

## 📱 About ADR Business Suite Mobile

ADR Business Suite Mobile brings essential business operations to your Android device. Manage sales, scan barcodes, track products, handle expenses, and stay on top of your business — anywhere, anytime.

Designed to complement the full ADR Business Suite web application, the mobile app is built for business owners and staff who need to operate on the go.

**Key features:**

- 📦 Product & inventory management
- 🛒 Sales entries with barcode scanning
- 📷 Barcode scanning for products and sales
- 💰 Expenses with period-based reporting and filters
- 📊 Finance dashboard with snapshot balances, assets, and liabilities
- 👥 Customer management with unified transaction history
- 📈 Profit & Loss reporting on the web
- 🖨️ Print and CSV export with period banners
- 📊 Transaction and activity history
- 🔐 Multi-location support

---

## 🚀 Current Release

### v1.0.1 — Bug Fix Release *(17 November 2026)*

A focused maintenance release addressing several reported issues across sales, creditors, supply payments, and notifications.

**Fixes in this release:**

- **Sales form — product search** — Resolved an issue where the product list reloaded on every search keystroke. Search results are now stable and no longer trigger unnecessary reloads while typing.
- **Sales form — packaged & unpackaged products** — Fixed handling of products with packaging (sold either as a full package or by individual unit) and products without packaging, so quantities, pricing, and selection now behave correctly in all cases.
- **Creditors page — manual adjustment** — Fixed customer search in the manual adjustment flow so it returns results correctly without being limited by pagination.
- **Supply payment method update** — Fixed a bug where the payment method update screen incorrectly kept showing an "account balance insufficiency" error after a valid update.
- **Native notifications** — Fixed native notification delivery so alerts now appear reliably on device.

📄 **Full release notes:**  
https://business.adrsystems.app/releases/adr-business-suite/v1.0.1

⬇️ **Direct download:**  
[adr-business-suite.apk](../../releases/latest/download/adr-business-suite.apk)

---

### v1.0.0 — First Android Release

The first public Android release of ADR Business Suite Mobile. This version ships with:

- **Sales & transactions** — detailed line-item breakdowns, tax/discount visibility, wallet tracking, split payments, and unified history per customer.
- **Expenses** — period-based reporting (day, week, month, quarter, year, or custom) with filterable summaries, charts, and print/export output that carries the active date range.
- **Finance dashboard** — cash, bank, card, and receivables snapshots, plus current assets, total liabilities, and supplier debt in a single glanceable view.
- **Printing & export** — consistent print styling across expenses, creditors, and customer reports. Every document includes a period banner and applied filters.
- **Web & server updates** — period-aware reporting on the web, a shared `resolvePeriod` helper on the backend, and date filters flowing through all summary and chart endpoints.

📄 **Full release notes:**  
https://business.adrsystems.app/releases/adr-business-suite/v1.0.0

---

## 🛠️ Installation (Android)

1. Download the APK from the [Releases](../../releases) page.
2. Open the downloaded file on your Android device.
3. If Android displays a security prompt, follow its instructions to allow installation from the source you used to download the APK.
4. Complete the installation and launch **ADR Business Suite**.
5. Sign in using your existing ADR Business Suite account.

**Requirements:** Android 8.0 (Oreo) or later.

💡 *Already using ADR Business Suite on the web? Use your existing account credentials to sign in on mobile.*

---

## 📊 Need More Advanced Business Insights?

ADR Business Suite Mobile focuses on operational convenience. For comprehensive business intelligence, full Profit & Loss statements, period comparison, and broader analytics, use the web application.

🌐 **Web Application:** https://business.adrsystems.app

---

## 🆘 Need Help?

- 🌐 **Website:** https://business.adrsystems.app
- 📖 **Support:** https://business.adrsystems.app/support
- ✉️ **Contact:** https://business.adrsystems.app/support/contact
- 📄 **Release Notes:** https://business.adrsystems.app/releases

---

## 📌 About This Repository

This repository contains **only release binaries**. It intentionally contains:

- ✅ Published APK files (via GitHub Releases)
- ✅ This README
- ❌ **No source code** — maintained in a private repository

The purpose of this repo is to provide public, permanent download URLs for the ADR Business Suite Mobile app. Our web backend proxies downloads through our own domain at `business.adrsystems.app/download`, so end users never need to visit GitHub directly.

---

**Built with ❤️ by ADR Systems**  
*Advanced Data Resources · Complex Business. Simplified Systems*
*Business Intelligence. Business Clarity. Business Data Integrity.*

**ADR Business Suite — Simplified Business Management.**

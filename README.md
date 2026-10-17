# CC PAY — Digital Payment System for CC CUP XL

CC PAY is a web-based digital coupon payment system developed for **Canisius College Cup XL (CC CUP XL)**, a school sports and competition event organized by SMA Kolese Kanisius Jakarta. The platform digitizes food allowance distribution and transactions, replacing traditional paper-based meal coupons with a centralized digital wallet system for event participants and committee members.

The platform allows users to view their available balance, scan merchant QR codes, make digital payments, and review their transaction history. It also provides administrative tools for managing user balances and a merchant dashboard for monitoring revenue and reviewing transactions.

Built with **SvelteKit, Svelte 5, Tailwind CSS, and Vite**, the frontend integrates with a backend API for authentication, balance management, and payment processing. Google Identity Services supports the login flow, Axios handles API communication, and `qr-scanner` enables QR code scanning.

## Key Features

- **Digital Wallet:** Displays available balances and recent transaction history.
- **QR-Based Payments:** Enables users to identify merchants by scanning QR codes, with manual merchant selection as an alternative.
- **Digital Transactions:** Provides an interface for entering payment amounts and confirming transactions.
- **Balance Management:** Allows administrators to update balances for multiple users.
- **Merchant Dashboard:** Displays merchant revenue and transaction records.
- **Authentication:** Integrates Google Identity Services with backend API authentication.

## Tech Stack

- **Frontend:** SvelteKit, Svelte 5, TypeScript/JavaScript
- **Styling:** Tailwind CSS
- **Build Tool:** Vite
- **API Communication:** Axios
- **QR Scanning:** `qr-scanner`
- **Authentication:** Google Identity Services and backend API integration
- **Deployment Configuration:** Vercel adapter

CC PAY demonstrates the application of web development to real-world event operations, streamlining payment workflows and reducing reliance on physical coupons.

# StandardEarners

A modern web application for smart earnings through Safari Trip packages and investments.

## Features

- User registration & login (phone + password)
- Safari trip investment packages with daily returns
- **New starter Day Safari at 15,000 UGX**
- Users can view all purchased trips under **My Trips**
- **Automatic deposits via MarzPay (MTN & Airtel Mobile Money)**
- Deposit fee: **5%** · Minimum deposit: **10,000 UGX**
- Withdrawal system
- Referral system (15% commission)
- **Professional Admin Panel**:
  - View & search all registered users
  - Manage balances, suspend/unsuspend, reset passwords, delete users
  - Impersonate users, reply to messages
  - Approve withdrawals & recharges
  - View all rentals / purchases
  - **Edit / Add / Delete trip packages**
  - Platform stats & danger-zone tools
- LocalStorage fallback for offline use

## Automatic currency rates

KES, RWF, and CDF are converted to **UGX** using live market rates.

## Multi-country MarzPay (UG, KE, RW, CD)

Deposits work via **MarzPay** in Uganda, Kenya, Rwanda and DRC.

## Withdrawal System

Users can request Mobile Money withdrawals (MTN / Airtel).

## Database Integration

The app uses a **server-side JSON database** (zero external dependencies):

| Path | Description |
|------|-------------|
| `data/database.json` | Main database (users, products, rentals, transactions, …) |
| `data/pending-deposits.json` | MarzPay pending collections |

## Run locally

```bash
npm start
# or
node server.js
```

Then open http://localhost:3000

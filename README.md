
# Shop POS

A point-of-sale app for small shops in Pakistan: kiryana stores, general
stores, medical stores and the like. It runs on a Windows PC, works fully
**offline**, and keeps all of the shop's data on that PC. No internet, server
or monthly fee is needed to sell.

The screens and the receipt can be in **English or Urdu**.

## Download

Get the latest installer from
[Releases](https://github.com/hassanjavedawan/pos-system/releases/latest):
`ShopPOS-Setup-<version>.exe`.

1. Run the installer. It needs no admin rights and installs in a few seconds.
2. Windows may say **"Windows protected your PC"** (the installer is not
   code-signed). Click **More info**, then **Run anyway**.
3. On first start, choose the language, the shop name and the owner's PIN.

Needs Windows 10 or 11 (64-bit).

## What it does

**Selling**
- Fast billing by barcode scanner, keyboard or quick buttons
- Sell by quantity, by weight (up to 3 decimals) or by amount ("Rs 100 of sugar")
- Discounts, cash or digital payment (JazzCash / Easypaisa, with the shop's own QR)
- Receipts on 58 mm or 80 mm thermal printers, in English or Urdu, with the shop's logo

**Khata (udhaar)**
- Customer accounts, payments received, full history
- Udhaar reminders sent on WhatsApp

**Stock**
- Products with barcodes, cost and sale price, low-stock warnings
- Scan goods in from suppliers; scan and count stock
- Print barcode labels on A4 sheets for loose items
- Import products from Excel

**Money and reports**
- Daily cash closing and expenses
- Returns and refunds
- Suppliers: purchases and what the shop owes
- Daily, monthly and profit reports, export to Excel, daily summary on WhatsApp

**Safe data**
- Two kinds of users: owner and cashier. Only the owner can cancel sales,
  change prices, see profit or restore a backup.
- Automatic daily backups in `Documents\POS-Backups` (30 days kept), checked
  every time. Restore from Settings.
- Sales are never deleted, only cancelled, so the record stays complete.

## Updates

The app checks this page for a new version by itself. A new version is
downloaded in the background and installed when the app is closed. Before any
update that changes the database, the app saves a copy of the shop's data in
the backup folder.

Every update is signed. The app refuses an update that is not signed by the
publisher.

## License

The app runs free for 30 days. After that it needs a license key, entered in
**Settings > License**. Contact the developer for a key.

When a license ends, selling stops but the shop's data stays fully readable,
and backups keep working.

## Where the data is

| What | Where |
| --- | --- |
| Shop database | `%APPDATA%\pos-app` |
| Backups | `Documents\POS-Backups` (can be changed in Settings) |

Uninstalling the app does **not** delete the shop's data.



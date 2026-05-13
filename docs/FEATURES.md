# FEATURES

# MVP FEATURES

These are the ONLY features to build initially.

---

# CUSTOMER FEATURES

## 1. QR Access

* User scans QR code inside print shop
* QR opens local web application
* No login required

---

## 2. File Upload

Users can upload:

* PDF
* JPG
* PNG
* DOCX (later)

Restrictions:

* Max file size: 50MB
* One file per order initially

---

## 3. Print Options

User can select:

* Number of copies
* Black & White or Color
* Page size:

  * A4
  * A3
* Single-side or double-side

---

## 4. Token Generation

After order submission:

* System generates token
* Example:

  * A101
  * A102

Token must:

* Be unique
* Be easy to read
* Be sequential if possible

---

## 5. Order Status Tracking

Statuses:

* Pending
* Approved
* Printing
* Completed
* Rejected

User can:

* Enter token
* View current status

---

# VENDOR FEATURES

## 6. Vendor Dashboard

Dashboard must show:

* Pending orders
* Printing orders
* Completed orders

Each order card/table should show:

* Token
* Uploaded file
* Print options
* Current status
* Timestamp

---

## 7. File Preview

Vendor can:

* Open uploaded file
* Preview before printing

---

## 8. Status Management

Vendor can:

* Approve order
* Reject order
* Mark printing
* Mark completed

---

# UI FEATURES

## 9. Mobile Responsive Design

Customer UI must work properly on:

* Android phones
* iPhones
* Tablets

---

## 10. Simple UI

Requirements:

* Large buttons
* Clean layout
* Minimal steps
* Beginner-friendly usage

---

# LOCAL NETWORK FEATURES

## 11. Local Wi-Fi Usage

System should:

* Work on same Wi-Fi network
* Use local IP address
* Not require internet

Example:
http://192.168.1.5:8000

---

# FUTURE FEATURES (NOT NOW)

Do NOT build these in MVP.

## Future Ideas

* Online payments
* WhatsApp notifications
* SMS alerts
* Multi-vendor system
* Cloud hosting
* User accounts
* Login system
* AI print optimization
* Mobile app
* Printer auto-detection

---

# DEVELOPMENT PRIORITY

Build in this order:

1. Backend APIs
2. File upload
3. Token generation
4. Vendor dashboard
5. Status updates
6. Angular frontend
7. QR integration

---

# SUCCESS CONDITION

The MVP is successful if:

1. User scans QR
2. Uploads file
3. Gets token
4. Vendor sees order
5. Vendor prints document
6. Vendor updates status


---

# Trojan Sync – USC Bookstore Schedule Automation

This is a small web app I built to make my life easier at work.
It automatically takes my work schedule from Google Sheets and adds my shifts to Google Calendar so I don’t have to do it manually every week.

Basically, no more checking the spreadsheet all the time.

---

## What This App Does

* Reads the work schedule from a Google Sheets file
* Finds the shifts that belong to you
* Adds them to your Google Calendar
* Checks for new shifts every day
* Avoids adding the same shift twice

It’s meant for USC Bookstore employees, but it could work for anyone using a similar schedule format.

---

## How It Works

1. You enter:

   * The **Spreadsheet ID** (from the Google Sheets URL)
   * Your **name** exactly how it appears in the schedule
   * A **color** for your shifts in Google Calendar

2. The app connects to:

   * Google Sheets API (to read the schedule)
   * Google Calendar API (to create events)

3. It then:

   * Finds your shifts
   * Converts them into calendar events
   * Syncs them automatically every 24 hours

---

## Features

* Clean USC-themed UI (cardinal & gold colors)
* Daily automatic sync
* Manual “Sync Now” button
* Status display (last sync, shifts added, next check)
* Log showing what’s happening in the background
* Prevents duplicate events

---

## Technologies Used

* **HTML**
* **CSS**
* **JavaScript**
* **Google Sheets API**
* **Google Calendar API**
* Google OAuth (for login/permissions)

No frameworks were used

---

## How to Use It

1. Open the app (`index.html`) in your browser.
2. Open the Google Sheets schedule.
3. Copy the **Spreadsheet ID** from the URL.
4. Enter:

   * Spreadsheet ID
   * Your name (exactly like in the schedule)
   * Event color (optional)
5. Click **Connect Google Services**
6. Allow the permissions.
7. Done. Your shifts will sync automatically.

---

## Example

Google Sheets URL:

```
https://docs.google.com/spreadsheets/d/1abcDEFgHiJKLmnoPQRstuVWXYZ/edit
```

Spreadsheet ID:

```
1abcDEFgHiJKLmnoPQRstuVWXYZ
```

---

## Notes

* The schedule format needs to match the USC Bookstore layout.
* Your name must match **exactly** how it appears in the sheet.
* You need to allow Google permissions for it to work.
* Works best on Chrome.

---

## Why I Made This

I got tired of:

* Forgetting shifts
* Checking the schedule all the time
* Manually adding events to my calendar

So I built this to automate everything and also practice working with APIs.

---

## Author

**Chidubem Ezenna**
USC Student & USC Bookstore Employee

---

<img width="1720" height="162" alt="Screenshot 2026-03-09 at 00 40 41" src="https://github.com/user-attachments/assets/3937a6db-f1c7-4c86-a073-a09462ed7443" />
<img width="1920" height="991" alt="Screenshot 2026-03-09 at 00 38 42" src="https://github.com/user-attachments/assets/58e6a3bd-fdd1-4aff-ab36-984bb87d5633" />



🛫 Flight Price Drop Monitor (Google Sheets + Notification)
Track flight prices directly from a Google Sheet and get notified when fares fall below your target. Perfect for travel hackers, budget adventurers, or automation fans.

🔍 How It Works
You maintain a Google Sheet with flight routes, desired price thresholds, and current prices.

This tool reads the sheet at regular intervals.

If a fare drops below your target, it triggers a notification.

Bonus: Can optionally log alerts or updates to another sheet or API.

📋 Sheet Format
Flight No	Origin	Destination	Target Price	Current Price
AI101	DEL	JFK	45000	47000
EK203	BOM	DXB	28000	27500 ✅
✅ means notification will be triggered!

🧠 Technologies Used
Python (backend logic)

gspread or Google Sheets API

smtplib or push service (for alerts)

Optional: Scheduler (e.g. cron jobs, APScheduler)

# Fueltech Branch Reporting Official Version

Stable no-Tailwind React/Vite app for station reporting.

## Included updates

- Each daily report has a Confirm Report button.
- Cashier and Manager have separate branch PINs.
- Admin can access all stations without PIN.
- Official wording, no demo reminder text.
- Fuel price setup is daily, not per shift.
- Manager pricing carries forward to the next day until changed.
- Admin can select a date and view daily station summaries using the calendar.
- Admin has bank verification and Excel-style monitoring.
- Branch pump layouts follow the requested pump/nozzle setup.

## Branch PINs

Cashier PINs:
- Mabolo: 1101
- Arpili: 1102
- Liloan: 1103
- Pondol: 1104
- Barili: 1105
- Moalboal: 1106

Manager PINs:
- Mabolo: 2101
- Arpili: 2102
- Liloan: 2103
- Pondol: 2104
- Barili: 2105
- Moalboal: 2106

Admin: no PIN.

## Vercel settings

Framework: Vite
Root Directory: ./
Install Command: npm install
Build Command: npm run build
Output Directory: dist

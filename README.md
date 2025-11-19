# AllDrive Tow & Trailer Manager

A simple browser-based tool to manage:

- Tow vehicles
- Trailers
- Towing safety checks (tow rating calculator)
- Basic trailer diagnostics
- Maintenance logs
- Export / import of data as JSON

Built for AllDrive Auto & Marine to help customers and fleets keep their rigs safe and maintained.

## Features

- Add / edit tow vehicles with tow ratings and notes
- Add / edit trailers with GVWR, empty weight, and notes
- Tow rating calculator:
  - Select a vehicle + trailer
  - Add cargo and passenger weight
  - Get a quick "safe / marginal / unsafe" style result
- Trailer diagnostics:
  - Pick a symptom and see likely causes and checks
- Maintenance log:
  - Track work done on vehicles and trailers
  - Stored locally in the browser using localStorage
- Export / import:
  - Export all data as JSON for backup or for a mechanic
  - Import JSON to restore data

## How to Run Locally

1. Download or clone this repo:

   ```bash
   git clone https://github.com/<your-username>/alldrive-tow-trailer-manager.git
   cd alldrive-tow-trailer-manager


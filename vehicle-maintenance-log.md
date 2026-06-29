# Vehicle Maintenance Log

A vehicle maintenance and running cost tracker to log every service, monitor upcoming maintenance needs, track fuel economy, and understand the true cost of keeping your vehicle on the road.

## 📋 Overview

Your car, motorbike, or van is one of the most expensive things you own — and one of the most expensive to neglect. This template keeps a full service history in one place, alerts you when maintenance is coming due, helps you track fuel economy over time, and gives you a clear picture of annual running costs. It's also invaluable when selling a vehicle, as a complete service record adds real value.

## 📄 Sheets

| Sheet | Purpose |
|-------|---------|
| `Maintenance Log` | Full history of every service, repair, and inspection |
| `Upcoming Services` | Auto-flagged services due within 500 miles or 30 days |
| `Fuel Log` | Fill-up records with auto-calculated MPG/L/100km and trend chart |
| `Cost Summary` | Annual maintenance and fuel spend by category |
| `Vehicle Info` | Registration details, insurance, and key vehicle information |

## 🚀 Getting Started

1. Open `vehicle-maintenance-log.ots` in LibreOffice Calc.
2. Enter your vehicle details on the **Vehicle Info** sheet.
3. Log all past services you have records for in the **Maintenance Log** — even if approximate.
4. Set next-due intervals in the Maintenance Log to populate **Upcoming Services**.
5. Begin logging fuel fill-ups in the **Fuel Log** from today.
6. Check **Upcoming Services** monthly (or before long trips) for anything due.

## 📝 How to Use Each Sheet

### Maintenance Log
The complete service history. Columns include:

| Column | Description |
|--------|-------------|
| Date | Date the service was performed |
| Mileage | Odometer reading at time of service |
| Service Type | Select from dropdown (see categories below) |
| Description | Details of what was done or replaced |
| Parts Used | Components replaced (e.g., oil filter, brake pads) |
| Shop / DIY | Where the work was done or "DIY" |
| Cost | Total amount paid |
| Next Due — Miles | Mileage at which this service is next needed |
| Next Due — Date | Calendar date by which this service should next occur |
| Notes | Technician notes, invoice numbers, warranty info |

**Service Types:** Oil Change, Tyre Rotation, Tyre Replacement, Brake Service, Air Filter, Cabin Filter, Battery, Spark Plugs, Coolant Flush, Transmission Service, MOT/Inspection, Timing Belt/Chain, Windscreen, Bodywork, Other.

### Upcoming Services
- Auto-scans the Maintenance Log and flags any service where:
  - **Next Due Mileage** is within 500 miles of current odometer, OR
  - **Next Due Date** is within 30 days of today
- Enter your current odometer reading in the header cell to keep this accurate.
- **Overdue services are highlighted in red**; due soon in amber.
- No manual entry required — this sheet is entirely formula-driven.

### Fuel Log
Log every fill-up:

| Column | Description |
|--------|-------------|
| Date | Date of fill-up |
| Mileage | Odometer at fill-up |
| Miles Since Last Fill | Auto-calculated |
| Litres / Gallons | Amount of fuel added |
| Price per Litre/Gallon | Fuel price at pump |
| Total Cost | Auto-calculated |
| MPG / L/100km | Auto-calculated fuel economy for that tank |
| Fuel Type | Petrol / Diesel / Electric (charge) / LPG |
| Station | Optional — useful for identifying good-value stations |

A trend chart shows your fuel economy over time — useful for spotting engine efficiency drops.

### Cost Summary
- Totals maintenance spend by service category per year.
- Shows fuel cost separately alongside maintenance cost.
- Calculates total annual running cost (maintenance + fuel).
- Compares year-on-year costs to identify trends.
- No data entry required — pulls from Maintenance Log and Fuel Log.

### Vehicle Info
Store key vehicle reference information:

| Section | Details |
|---------|---------|
| Vehicle | Make, model, year, colour, VIN/chassis number |
| Registration | Plate number, registration date, registered keeper |
| MOT / Inspection | Expiry date (highlighted red when within 30 days) |
| Insurance | Provider, policy number, expiry date, 24hr claims line |
| Breakdown Cover | Provider and membership number |
| Finance | Lender, monthly payment, final payment date (if applicable) |
| Road Tax | Expiry date |
| Tyre Specs | Correct tyre size (front and rear) for reference |

## 💡 Tips

- **Log every fill-up** — missing even one entry breaks the MPG calculation chain. Fuel economy trends are only useful with complete data.
- **Update the current odometer** in the Upcoming Services header every time you open the file, or at least monthly.
- **A complete service history adds value** when selling — print the Maintenance Log and include it with the vehicle.
- Use the Notes column to record invoice numbers — this makes it easy to retrieve records from a garage if a warranty claim arises.
- Keep an eye on the fuel trend chart — a sudden drop in MPG can be an early sign of a maintenance issue.

## 🗂️ File Details

| Property | Value |
|----------|-------|
| File name | `vehicle-maintenance-log.ots` |
| Format | LibreOffice Calc Template (`.ots`) |
| Sheets | 5 |
| Requires | LibreOffice Calc 7.0 or later |

## 📁 Repository

Part of the [`personal-libreoffice-calc-templates`](https://github.com/yourusername/personal-libreoffice-calc-templates) collection.

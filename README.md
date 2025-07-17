# Commuter Rail PM Tracker (Power Apps)

This Power Apps canvas app tracks preventative maintenance (PM) inspections for commuter rail vehicles. It is used by mechanical teams to log inspection dates, manage OOS credits, and track inspection history.

## 🔧 Features
- Tracks 92, 184, 368, 1104, and 1472-day inspections
- Uses SharePoint as a backend
- Stores inspection history records
- Applies out-of-service (OOS) date adjustments
- Attaches PDFs of completed inspections

## 📦 Technology
- Power Apps Canvas App
- SharePoint Lists
- Power Automate (for file uploads)
- GitHub version control (via Power Platform CLI)

## 📸 Screenshots
_Add screenshots here showing your interface, dashboard, or gallery views._

## 🚀 How to Use
This is an unpacked Power App source. To repackage:

```bash
pac canvas pack --sources ./DailyInspection --msapp DailyInspection.msapp

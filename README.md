# 📦 Courier Connect – Pega Application
A Pega Constellation 24.2-based **Courier Booking and Delivery System** that automates parcel bookings, vendor selection, approvals, and delivery tracking to streamline courier management.

---
## 📂 Project Files
📦 [**Download Project Files (.zip)**](SmartDel_010101_20250904T044747_GMT.zip) 
Includes HLD documentation, portal designs, class structure, and screenshots.

## 🎬 Application Demo
📽️ *(If you have a demo video, you can add it here. Example:)*
[**Watch Courier Connect Walkthrough**](https://github.com/vinithasriprathipati/courier_connect/blob/c83d3abf0b59ba120744fc4b40e5f49eb609966e/Courier%20Connect.mp4)

A quick demo showcasing features like customer booking, admin approvals, package pickup, and delivery status updates.

---

## 📂 Project Files
📄 [**HLD & Documentation**](./CourierConnect.docx)  
📊 [**Presentation Slides**](./Courier%20Connect.pptx)  

Includes abstract, use cases, design structure, portals, reports, and system flow.

---

## 👥 Case Types & Personas
### 🗂️ Case Types
- **Courier Track**

### 👩‍💼 Personas
- **Customer** – Register/login, book courier, select vendor (Bluedart/FedEx), get instant price  
- **Admin** – Approve/reject bookings, assign pickup assistants, manage dashboard  
- **Pickup Assistant** – Verify package details, collect items, update pickup status  
- **Delivery Assistant** – Deliver packages, update completion, notify customers  

---

## 💡 Key Features
✔️ Self-service portal for booking couriers  
✔️ Automated delivery price calculation (based on weight, destination, vendor)  
✔️ Admin dashboard for approvals & assignments  
✔️ Email confirmations & real-time notifications  
✔️ Pickup assistant workflow for package verification  
✔️ Delivery assistant workflow for shipment tracking  
✔️ Reports on vendor usage, delivery trends, and booking status  
✔️ Web & mobile responsive portals  

---

## 🛠️ Tools & Technologies
- **Pega Constellation 24.2**  
- **Pega SOR (System of Record)**  
- **Web & Mobile Portals**  
- **Email Integration**  
- **Dashboards & Reports**  

---

## 🏛️ Application Structure
**Application Name:** SmartDelivery  
**Application Structure:** CourierTrack 

**Enterprise Class Layers:**  
- Org Layer → `MyOrg`  
- App Layer → `MyOrg-SmartDel`  
- Work Layer → `MyOrg-SmartDel-Work-CourierTrack`  
- Data Layer → `MyOrg-SmartDel-Data-*`  
- Integration Layer → `MyOrg-SmartDel-Int-*`  

---

## 📚 Data Model
- **Customer:** Name, Email, PhoneNo  
- **Item:** ItemName, Description, Price, Quantity, Type, ServiceNeeded, Vendor  

---

## 📊 Reports & Insights
📌 Number of bookings by **destination (National/International)**  
📌 Bookings grouped by **vendor (Bluedart/FedEx)**  
📌 **Booking status** (Pending/Accepted/Rejected)  
📌 **Daily, Weekly, Monthly** booking trends  

---

## 📢 About
**Courier Connect** simplifies courier booking and delivery through Pega’s low-code automation platform. By enabling customers, admins, pickup, and delivery assistants to work on a unified system, it reduces delays, improves transparency, and enhances customer experience with real-time tracking and automated workflows.

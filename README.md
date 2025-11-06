# 📊✨ Hotel Booking & Cancellation — Excel Analytics

A clean, interactive **Excel dashboard** analyzing hotel **bookings**, **cancellations**, **guest types**, and **seasonality** to help teams reduce churn and improve forecasting.

<p align="left">
  <a href="#-features">Features</a> •
  <a href="#-dataset-overview">Dataset</a> •
  <a href="#-dashboard-highlights">Dashboard</a> •
  <a href="#-key-insights">Insights</a> •
  <a href="#-how-to-use">How to Use</a> •
  <a href="#-project-structure">Structure</a> •
  <a href="#-future-roadmap">Roadmap</a> •
  <a href="#-contact">Contact</a>
</p>

---

## 🚀 Overview

- **Total Bookings:** `119,390`  
- **Total Cancellations:** `44,224`  
- **Est. Cancellation Rate:** `~37%`  
- Built entirely in **Microsoft Excel** using **Power Query, Pivot Tables, Pivot Charts, and Slicers**.

> Ideal for analysts and operations teams who want a ready-to-use Excel dashboard without writing code.

---

## ✅ Features

- **KPI cards** for Total Bookings & Cancellations  
- **Pie charts**: Bookings & Cancellations by **Hotel Type** (City vs Resort)  
- **Clustered bars**: **Guest Type** vs **Cancelled/Total** (Couple, Family, Single)  
- **Monthly trend** of bookings vs cancellations  
- **Room status** distribution  
- **Slicer** for **Year** (2015–2017) to filter all visuals  

---

## 📦 Dataset Overview

| Category       | Description                                             |
|----------------|---------------------------------------------------------|
| Booking Info   | Confirmed + cancelled bookings                          |
| Cancellation   | Count and rate by dimensions                            |
| Guest Type     | Couple / Family / Single                                |
| Hotel Type     | City Hotel / Resort Hotel                               |
| Date Parts     | Month, Year (used for seasonality)                      |
| Room Status    | Occupied vs Unoccupied                                  |

---

## 📊 Dashboard Highlights

### ✅ Preview  
> *(Dashboard Image Preview)*  

![Dashboard](https://github.com/Ozarakesh533/Hotel-Booking-and-Cancellation-Data-Analysis-using-Excel/issues/1#issue-3596252098)

---

## 🔍 Key Insights

- **City Hotels** drive a larger share of bookings than Resort Hotels.  
- **Couples** contribute the highest booking volume.  
- **~37% cancellation rate** suggests strong need to optimize policies & communication.  
- **May–July** show peak seasonal activity.  
- **Unoccupied rooms** indicate upsell/marketing opportunities.  

---

## 🛠 Tech Stack

- **Microsoft Excel** (Power Query, Pivot Tables/Charts, Slicers)
- Optional: **Power BI** / **Python** for future extensions

---

## ▶ How to Use

1. **Download** the repository.
2. Open `Dashboard.xlsx`.
3. Use the **Year slicer** to filter visuals.
4. Hover over visuals to explore booking & cancellation details.  
5. Replace `cleaned_data.xlsx` with your dataset if needed, then **Refresh All**.

---

## 🗂 Project Structure

hotel-booking-analytics/
├─ Dashboard.xlsx # Final interactive dashboard
├─ cleaned_data.xlsx # Model-ready table(s)
├─ raw_data.csv # Optional: Raw dataset
├─ assets/
│ └─ dashboard.png # Screenshots
└─ README.md


---

## 🧭 Future Roadmap

- [ ] Power BI interactive dashboard  
- [ ] ML-based cancellation prediction  
- [ ] Customer segmentation (RFM / clustering)  
- [ ] Revenue impact simulation  
- [ ] What-if policy impact model  

---

## 🤝 Contributing

1. Fork the repo  
2. Create a branch: `git checkout -b feature/my-update`  
3. Commit changes  
4. Push & open a PR  

---
## 📬 Contact

**Author:** Rakesh Oza  
🔗 GitHub: https://github.com/Ozarakesh533  
🔗 LinkedIn: https://www.linkedin.com/in/rakeshoza

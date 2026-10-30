# 🏥 Hospital Appointment Booking System

A simple, browser-based **Hospital Appointment Booking System** built with pure HTML, CSS, and JavaScript — no backend or libraries required.

## 📋 Features

- ➕ **Add Doctors** — Register doctors with a unique Doctor ID and name
- 📅 **Book Appointments** — Book an appointment for a patient with a specific doctor, date, and time
- ❌ **Cancel Appointments** — Cancel any existing appointment by its Appointment ID
- 🔒 **Slot Conflict Prevention** — Prevents double-booking the same doctor at the same date and time
- 📊 **Live Tables** — Doctor list and active appointment list update in real time

## 🚀 Getting Started

No installation needed. Just open the file in any modern web browser:

```
hospital/index.html
```

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & Layout |
| CSS3 | Styling |
| JavaScript (Vanilla) | Business Logic & DOM Manipulation |

## 📁 Project Structure

```
hospital/
└── index.html    # All-in-one HTML file (HTML + CSS + JS)
```

## 💡 How to Use

1. **Add a Doctor** — Enter a Doctor ID and name, then click **Add Doctor**
2. **Book an Appointment** — Enter patient name, select a doctor, pick a date and time, then click **Book**
3. **Cancel an Appointment** — Enter the Appointment ID shown in the table and click **Cancel**

## ✅ Validations

- Doctor ID must be unique
- All appointment fields (patient, doctor, date, time) are required
- Duplicate slot booking for the same doctor is blocked
- Only valid integer Appointment IDs are accepted for cancellation

## 📌 Notes

- Data is stored in-memory (JavaScript arrays) and resets on page refresh
- No external dependencies or internet connection required

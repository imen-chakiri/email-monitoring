# Sell-out Email Monitoring

This project shows how **email-based sell-out data collection** can be monitored and measured using **Power BI**.

The dashboard turns daily email activity (data sent, reminders, follow-ups) into **clear indicators** that help understand:
- who sends data regularly  
- who requires frequent follow-ups  
- how complex the communication process is  

The goal is **operational visibility**, not advanced analytics.

---

## What problem does this solve?

In many companies, sell-out data is collected **via email**.
This creates issues:
- data arrives late or inconsistently  
- many follow-ups are needed  
- email threads become complex and hard to track  

This dashboard makes the process **measurable and visible**.

---

## What the dashboard shows

For each account / contact, the report tracks:

- **Files Received**  
  Emails that actually contain sell-out data

- **Follow-ups Sent**  
  Reminder emails sent to request missing data

- **Total Conversations**  
  Overall number of email interactions

- **Reliability**  
  A simple KPI that combines:
  - data received  
  - effort required to obtain it  

Reliability is classified as:
- **High**
- **Medium**
- **Low**

This allows quick identification of:
- reliable data providers  
- accounts that require constant follow-up  

---

## How the dashboard is designed

### Data Model
- Single flat table (`Email`)
- Each row represents an email-related event  
- Designed for **monitoring**, not complex relational analysis  

### Report Layout
- One-page dashboard
- Built for **quick reading**

---

## Screenshots

The repository includes example scenarios:
- [High reliability](scenarios/high_reliability.png)
- [Medium reliability](scenarios/medium_reliability.png)
- [Low reliability](scenarios/low_reliability.png)

These help understand how the KPI behaves in different scenarios.

---

## Dataset

The dataset included in this repository is **fully synthetic**.  
No real company names, emails are used.

---

## Tools Used

- Power BI  
- Excel  

---

## Notes

This project focuses on:
- process monitoring  
- communication efficiency  
- data collection reliability  

It is designed as an **operational control tool**.

*** 
## Link 
https://app.powerbi.com/groups/me/reports/ead7fc1c-b96f-475b-ba9c-4deadbdf4fa4/f5d8e4ea0eafb2e62ab4?experience=power-bi

# Collection-Highlights-Dashboard-FY2026-27 (Interactive Dashboard creation using Power BI)
## Project Objective
The finance / account management team wants a single collection report for FY 2026-27. So that management can track invoices raised vs. amount received, monitor outstanding payments, check account manager performance, and focus recovery efforts on the right clients in the coming months.
## Dataset used
Invoice-level data for FY 2026-27 (April to October 2026)
Fields: Invoice No., Client Name, Account Manager, Invoice Date, Invoice Amount, Received Amount, Received Status, Pending Amount, Expected Collection Date
## Note
Due to data privacy and company confidentiality policies, raw datasets, customer records, and the original workbook are proprietary and cannot be shared publicly.

## Questions (KPIs)
- What is the total number of invoices and the total amount raised?
- How much has been received till date, and what is the overall collection %?
- What is the outstanding amount and how many invoices are still pending?
- Compare invoice amount vs. received amount month by month using a single chart.
- Which month had the highest invoice amount, and which month had the weakest collection?
- How is each account manager performing on collection?
- Which top 5 clients have the highest pending amount?
- How much is expected to be collected in the coming weeks (week-wise, month-wise)?

Dashboard Interaction

![Collection Dashboard FY 26-27 (Power Bi)](https://github.com/Abhijeetpatil-1998/Readme-MD-Collection-Highlights-Dashboard-FY2026-27-Interactive-Dashboard-creation-using-Power-BI-/blob/main/Collection%20Dashboard%20FY%2026-27%20(Power%20Bi).jpeg)
## Process
- Verified data for missing values, duplicate invoices and anomalies, and sorted out the same.
- Made sure data is consistent and clean with respect to data type, date format and values used.
- Built the data model and created DAX measures (Total Invoice, Received Amount, Outstanding, Collection %, Pending Invoices).
- Created visuals according to the questions asked: KPI cards, monthly column chart, account manager summary table, top 5 pending clients table and expected amount by month matrix.
- Merged all visuals into one dashboard and applied slicers (Month, Account Manager, Client) to make it dynamic.

## Project Insight
- Total of 201 invoices worth 23.01 Cr were raised, and 17.54 Cr has been received, giving an overall collection rate of 76.22%.
- 95 invoices are still outstanding with 9.61 Cr pending.
- July had the highest invoice amount (3.8 Cr) but only 2.3 Cr was received. September had the weakest collection (1.7 Cr received out of 3.2 Cr raised).
- October invoices (3.6 Cr) are still to be collected, as the month is ongoing.
- Rahil Mulani (93.43%) and Vishaka Khatrani (92.18%) have the best collection %, while Nikhil Phatak is at 64.99% with the highest pending amount (4.57 Cr).
- The top 5 clients account for 7.27 Cr of pending amount. Suryoday Small Finance Bank Ltd alone owes 4.42 Cr (~60% of the top 5 total).
- Expected collection is 8.15 Cr (4.97 Cr in October and 3.18 Cr in November), with the biggest inflow expected in Week 3 of October (4.64 Cr).

## Final Conclusion

To improve collections, a focused recovery plan should be implemented for the top pending clients, especially Suryoday Small Finance Bank, Vegapay Technology and The Jammu and Kashmir Bank, which together hold most of the outstanding amount. Account manager Nikhil Phatak's portfolio needs priority follow-up, and the best practices of Rahil Mulani and Vishaka Khatrani (over 90% collection) can be shared across the team. Weekly follow-ups against the expected collection schedule and early reminders for aging invoices (like those from July and September) will help bring the collection % above 85% by year end.

## Tools Used
Power BI Desktop (Data model, DAX, Visuals, Slicers)
Microsoft Excel (Data cleaning)




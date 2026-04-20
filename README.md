# OLA_INSIGHTS1
Project update — Ola rides dashboard (my second Power BI project)
I analyzed 103,024 Ola bookings (July 2024) and built a clean dashboard to monitor revenue, cancellations, payment mix and ratings. Highlights:
• Total booking value: 56.5M (dataset units) across the month ,consistent daily volumes with a few high peaks.
 • Volume: 103k bookings; avg trip distance =  14.19.
 • Vehicle mix: revenue is fairly evenly distributed across vehicle types Prime Sedan, eBike and Prime Plus are among top contributors (each ~7.9–8.3M).
 • Payments: cash and UPI are the dominant payment channels (dashboard shows cash ≈55% and UPI ≈40% by value).
 • Cancellations: major customer reasons — driver not moving to pickup location, driver asked to cancel, and change of plans. Major driver cancellations — personal/car issues and customer-related issues. This points to both supply-side and demand-side friction points.
 • Ratings: average customer & driver ratings hover around 4.0 across vehicle categories — stable but room for improvement.
What I learned / why this matters:
Monitoring payment mix helps product & payments teams prioritise instant settlement and reduce cash handling risks.
Cancellation reasons provide direct signals for driver-assistance features, incentive design, and improvements in rider-driver matching.
A stable rating of ~4.0 across categories indicates consistent service quality; focusing on cancellation reduction could further enhance ratings.
Tools & methods: Power BI (line charts, pie charts, KPI cards, matrix), SQL for data prep, DAX measures for KPIs and time-series aggregation.

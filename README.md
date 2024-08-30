# 🧹 Optimizing-Hotel-Performance-Insights-from-Cancellation-Analysis📊

## Overview

In the dynamic hospitality industry, City Hotel and Resort Hotel face a common challenge: soaring cancellation rates. As key revenue generators, these cancellations impact operational efficiency and room utilization. This analysis provides a comprehensive overview of the variables affecting hotel reservation cancellations and proposes strategic solutions to mitigate their impact.

## Assumptions

- The data covers the period from 2015 to 2017.
- Information is up-to-date and suitable for efficient analysis.
- The proposed strategies assume no unforeseen negative outcomes.
- The suggested solutions have not been previously implemented.
- Booking cancellations have a significant impact on hotel revenue.
- Cancellations lead to vacant rooms that could otherwise generate income.

## Research Questions

1. What variables influence hotel reservation cancellations?
2. How can we enhance the hotel reservation cancellation experience?
3. What insights guide pricing and promotional decisions?

## Hypotheses

- Higher prices correlate with an increase in cancellations.
- Longer waiting lists result in more cancellations.
- Offline travel agents are the primary source of reservations.

## Data Cleaning & Transformation

### 🗓️ Date Handling

- Converted `reservation_status_date` to a datetime format to enable precise temporal analysis.

### 🔄 Null Values Management

- **'meal'** column: Addressed 488 null values.
- **'agent'** column: Handled 16,340 null values.
- **'company'** column: Managed 112,593 null values.

These steps are crucial for ensuring data integrity and reliability in subsequent analyses.

### 🗑️ Column Removal

- Removed columns with significant null values to streamline the analysis process.

## Data Visualization Highlights

- 📊 **Canceled Reservations Distribution:** Analyzed the distribution of cancellations across various dimensions.
- 🏨 **Reservation Status by Hotel Type:** Compared the reservation status between City and Resort Hotels.
- 📈 **Average Daily Rate (ADR) Trends:** Tracked ADR trends in both City and Resort Hotels.
- 🗓️ **Monthly Reservation Status:** Investigated reservation status changes over months to identify peak cancellation periods.
- 📉 **ADR for Canceled Reservations:** Examined the ADR per month for canceled reservations to identify pricing trends.

## Insights & Recommendations

- 📉 **Pricing Strategy:** Higher prices are linked to more cancellations. Consider a more dynamic pricing strategy to mitigate this.
- 📆 **Targeted Marketing:** Peak cancellations occur in January, suggesting the need for targeted marketing campaigns during this period.
- 🌍 **Focus on Portugal:** With Portugal leading in cancellations, hotels should focus on service enhancements and customer engagement in this region.
- 💼 **Promote Direct Bookings:** Encourage direct bookings through discounts and loyalty programs to reduce dependency on third-party agents.

## Conclusion

The journey from data analysis to actionable insights is a strategic one. By understanding the patterns of cancellations, hotels can adjust their pricing, marketing, and service strategies to optimize revenue generation. Let's transform these challenges into growth opportunities! 💼📈✨

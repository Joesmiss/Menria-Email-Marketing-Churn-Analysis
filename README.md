# Email Marketing Churn & Engagement Analysis – Menria Company

## Project Overview
Menria Company relies heavily on email marketing to engage customers, promote offerings, and maintain long-term relationships. Despite steady subscriber growth, the marketing team observed **persistently high unsubscribe rates**, especially among newer subscribers.

This project represents a **real-world email marketing analytics initiative** conducted to diagnose the root causes of subscriber churn and provide **data-driven recommendations** to improve email engagement and retention.

---

## Business Problem
Menria Company was experiencing:
- High unsubscribe rates across multiple campaigns
- Significant churn within the **first six months of subscription**
- Limited visibility into how **campaign type, engagement behavior, device usage, and region** influenced churn

Without a clear understanding of these factors, ongoing email campaigns risked reducing customer lifetime value and weakening brand trust.

---

## Business Objectives
The objectives of this project were to:
1. Identify the key drivers of email unsubscribes at Menria Company
2. Compare unsubscribe behavior across campaign categories
3. Analyze engagement metrics in relation to churn
4. Uncover behavioral, device, and regional churn patterns
5. Recommend actionable strategies to reduce unsubscribe rates and improve retention

---

## Data Source
**Email Marketing Dataset – Mary Knoeferl (LinkedIn)**  
*(Used to simulate Menria Company’s email marketing operations for analytical purposes)*

The dataset consists of five relational tables:
1. **Campaign Performance** – Emails sent, opens, clicks, unsubscribes  
2. **Campaign** – Campaign metadata (name, category, send time)  
3. **Email Engagement** – User-level engagement metrics  
4. **Unsubscribes** – Unsubscribe reasons and timestamps  
5. **Users** – Signup date, device type, activity level, and region  

---

## Tools & Technologies Used
- **SQL (SQLite):** Data extraction, table joins, churn calculations
- **Python (Pandas, Matplotlib, Seaborn):** Data cleaning, exploratory analysis, visualization

---

## Analytical Approach
To solve Menria Company’s business problem, the following steps were taken:

### 1. Data Preparation & Modeling
- Joined campaign, engagement, unsubscribe, and user tables using SQL
- Created unsubscribe rate, churn duration, and engagement metrics

### 2. Campaign-Level Analysis
- Analyzed unsubscribe rates by campaign and campaign category
- Identified high-risk campaign types contributing most to churn

### 3. Churn & Behavioral Analysis
- Compared open and click behavior against unsubscribe trends
- Analyzed churn patterns by device type and geographic region
- Assessed send-time engagement patterns
- Reviewed unsubscribe reasons for qualitative context

---

## Key Insights

### 1. Critically High Unsubscribe Rates
- Average unsubscribe rate: **75.8%**
- **Promotional campaigns** generated the highest churn
- **Newsletter campaigns** recorded the lowest unsubscribe rates

---

### 2. Campaign Type Is the Primary Churn Driver
Average unsubscribe rates by campaign category:
- Promotional: **80.4**
- Announcement: **79.0**
- Re-engagement: **73.0**
- Newsletter: **72.2**

Frequent promotional messaging significantly increased subscriber churn.

---

### 3. Engagement Does Not Guarantee Retention
- No meaningful correlation between open rates and unsubscribes
- High open rates did not prevent churn
- Indicates that **content relevance and perceived value** are stronger retention drivers than visibility alone

---

### 4. Device Experience Impacts Retention
Unsubscribes by device type:
- Tablet: **530**
- Mobile: **507**
- Desktop: **479**

Suggests potential email layout or usability issues on non-desktop devices.

---

### 5. Regional & Cultural Effects
- Asia recorded the highest unsubscribe volume
- Europe and North America followed closely

Indicates possible cultural or localization mismatches in email content.

---

### 6. Early Subscriber Churn
- Average churn occurred around **6 months after signup**
- Suggests weak onboarding and insufficient early-stage engagement

---

### 7. Timing Influences Engagement, Not Churn
- Higher engagement observed during:
  - Early mornings (7–8 AM)
  - Mid-afternoons (1–3 PM)
  - Early evenings (7–8 PM)
- Send time alone did not significantly reduce churn

---

### 8. Primary Reasons for Unsubscribing
- Privacy concerns
- Content perceived as not relevant
- Preference for competing brands

---

## Recommendations

### 1. Redesign Email Content Strategy
- Introduce **structured onboarding email journeys** for new subscribers (0–6 months)
- Reduce the frequency of promotional emails
- Shift toward **value-driven and educational content**

---

### 2. Implement Advanced Segmentation
- Segment subscribers by engagement level, tenure, and campaign interaction
- Personalize email content based on user behavior rather than broad email blasts

---

### 3. Optimize Email Design Across Devices
- Ensure all emails are fully responsive across mobile, tablet, and desktop
- Improve readability and call-to-action placement

---

### 4. Build Trust & Transparency
- Clearly communicate how user data is collected and used
- Address privacy concerns directly within email communications

---

## Business Impact
If implemented, these recommendations would enable Menria Company to:
- Reduce unsubscribe rates
- Improve customer lifetime value
- Increase engagement quality
- Strengthen brand trust
- Establish a sustainable, data-driven email marketing strategy

---

## Skills Demonstrated
- Email & CRM analytics
- Churn and behavioral analysis
- SQL querying and relational data modeling
- Python-based data analysis and visualization

# Tayseer Customer Satisfaction & Channel Analysis

**Course:** SDA-DSC-112 — Data Visualization and Storytelling
**Student:** Aisha AlMajed

## Project Description

This project analyzes Tayseer's service channel usage and customer satisfaction to understand how channel usage has changed over time and how customer satisfaction differs across channels. The analysis focuses on transaction share trends and weighted CSAT across Web, Mobile App, Call Centre, and Branch.

**SDAIA Academy:** https://github.com/SDAIAAcademy

## 1. Audience, Decision Question & Scope

**Audience:** The Chief Executive Officer (CEO) of Tayseer.

**Decision Question:** How has the shift in service channel usage coincided with differences in customer satisfaction across channels?

**Chosen Scope:** Focus on transaction share trends over time and customer satisfaction across Web, Mobile App, Call Centre, and Branch.


### Metrics & Aggregation

**Transaction share:** Transactions were summed by month and channel, then divided by total monthly transactions to calculate each channel's share of transactions.

**CSAT:** Customer satisfaction was calculated as a weighted average using unique users, giving greater weight to CSAT values representing more users.

##  Story

The Mobile App's share of total transactions increased substantially over the observed period, while it also recorded the highest customer satisfaction among the four service channels. Its transaction share increased from **below 20% in 2021** to approximately **50% in 2026**, while its weighted CSAT was approximately **4.5/5**, compared with approximately **3.5/5** for Branch, which had the lowest CSAT. Based on these findings, Tayseer should continue supporting the growing use of the Mobile App while investigating opportunities to improve the customer experience in Branch services.

**Limitation:** The analysis shows an association between channel usage and customer satisfaction, but it does not establish causation. Differences in region, service category, or customer needs may also influence CSAT.

## Chart Choice & AI Check

A line chart was chosen to show changes in transaction share over time, while a bar chart was chosen to compare customer satisfaction across service channels. I checked the calculations, aggregation methods, channel values, and chart outputs against the original dataset. AI was used to assist with code and wording.

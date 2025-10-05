# Global Retail Profitability Analysis: Strategic Intervention

## 1. Project Overview
This project provides a comprehensive financial and operational analysis of a global retailer's 51,000-row transaction dataset. The core objective was to move beyond simply identifying losses and instead, pinpoint the structural root causes driving the overall critically low 4.74% average profit margin.

The deliverable is a 5-slide Executive Action Plan (PowerPoint/PDF) detailing high-impact, phased recommendations to eliminate losses and restore sustainable growth.

## 2. Key Findings & Business Impact
The analysis proved that the profitability crisis was not global, but structural, centered on a few high-risk segments:

* Critical Margin: The overall average profit margin is 4.74%, which is unsustainable.
  
* The Problem Regions (The Bleed): 70% of the margin deficit is concentrated in three regions, with Africa (−14.36%) and EMEA (−14.12%) being the primary financial drains.
  
* The Product Drag (The Root Cause): The Furniture category is the primary loss driver, consistently exhibiting deep negative margins across the failing regions (e.g., Africa Furniture at −13.58%).
  
* The Opportunity: Canada (24.75%) and West (21.95%) are highly profitable and driven by the stable Office Supplies category.

## 3. Technical Skills and Methodology
This analysis was performed primarily in Microsoft Excel, demonstrating advanced data modeling and visualization techniques.

A. Data Cleaning and Preparation 

* Outlier Detection: Used the Interquartile Range (IQR) method to identify and flag outliers in key columns, including Profit, Quantity, and Sales, ensuring the average calculations were robust against extreme values.

* Feature Engineering: Created the crucial Profit Margin (%) column using the formula Profit/Sales to enable accurate percentage-based profitability analysis at the transaction level.

B. Analytical Modeling and Visualization

* Pivot Table Mastery: Generated complex Pivot Tables to aggregate transaction data by Region and Category, summarizing results by Average to prevent misleading sums (a key project error identified and corrected).

* Conditional Formatting (Heatmap): Applied a Red-Yellow-Green color scale to the Pivot Table to visually isolate the regions and categories with negative margins, creating the central piece of evidence for the Root Cause Analysis (Slide 4).

* Actionable Charting: Created a Grouped Bar Chart using the Stoplight Effect (Red for losses, Blue for leaders) to clearly visualize the extreme "Profitability Gap" for executive review (Slide 3).

## 4. Final Recommendations (Executive Action Plan)

The analysis resulted in a phased plan presented to executive leadership (Slide 5):

Phase 1: PRICE STABILIZATION

Action: Immediately FREEZE ALL DISCOUNTS on the Furniture category in loss-making regions (Africa, EMEA).

Phase 2: SYSTEMIC COST AUDIT

Action: LAUNCH A LOGISTICS AUDIT to target and reduce the high fixed costs driving the systemic −14% regional losses in Africa and EMEA.

Phase 3: INVESTMENT FOR GROWTH

Action: REALLOCATE MARKETING SPEND to the high-margin Office Supplies and Technology categories in the Leader regions (Canada and West).

## 5. Repository Contents

File/Folder                     	Description

Global Profitability Review.pdf          	The complete 5-slide presentation deck used to communicate findings and the Action Plan.

superstore_dataset2011-2015 (version 1).xlsb	        Excel workbook containing the raw data, outlier calculations, and final Pivot Tables/Charts.

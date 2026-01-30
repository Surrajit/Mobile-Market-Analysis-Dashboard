# Mobile-Market-Analysis-Dashboard

## Problem Statement

This dashboard provides a comprehensive analysis of the global mobile and tablet market. It helps stakeholders understand the competitive landscape by identifying market leaders in product variety, regional pricing strategies, and hardware standardization trends.

The analysis reveals that while brands like Oppo lead in model volume (115 models), Apple maintains a dominant premium position with an average launch price of approximately 4.0K AED. By correlating hardware specs (RAM, Camera, Battery) with price points across multiple currencies (AED, INR, USD, etc.), this dashboard enables businesses to identify market gaps, benchmark competitor pricing, and align their product development with current hardware standards (such as the high prevalence of 16MP and 32MP front cameras).


### Steps followed 

- Step 1 : Load data into Power BI Desktop. The Excel files containing detailed technical specifications.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : It was observed that the "Launch Price" column required data cleaning to handle multiple currency symbols (AED, $, ₹, etc.) and convert them into a                standardized numerical format for analysis.
- Step 4 : Cleaned hardware specification strings, specifically identifying multi-lens configurations (e.g., "$12MP+12MP+12MP$") to enable back camera resolution             grouping.
- Step 5 : In the report view, under the view tab, a professional dark/corporate theme was selected to enhance visual clarity.
- Step 6 : Visual filters (Slicers) were added for "Company Name", "Launched Year", and "RAM (GB)".
- Step 7 : Four card visuals were added to the canvas representing total models, average price in USD, distinct processor counts, and highest RAM available.
- Step 8 : A bar chart was added representing the "Number of Models by Company," highlighting Oppo, Apple, and Honor as the top three leaders.
- Step 9 : A "Matrix Visual" was used to correlate detailed hardware performance (Avg RAM, Avg Weight) with Average Price for high-end models like the iPad Pro               and iPhone series.
- Step 10 : Rating visuals were utilized to represent common front camera resolutions, identifying 32MP and 16MP as the market standard.
- Step 11 : A Line or Area chart was used to track average launch price trends over various launch years.

- Step 12 : Calculated columns and measures were created to handle currency conversions and average hardware scores.

 # Report Snapshot (Power BI DESKTOP)

 ![Image](https://github.com/user-attachments/assets/1b7a70ba-10df-42aa-a032-7a14cdaf5e14)

 ![Image](https://github.com/user-attachments/assets/369dbeb0-7adf-4909-97df-df80a758dca9)

 ![Image](https://github.com/user-attachments/assets/31eac0dc-af69-4180-9015-d34cf8145ea9)

 ![Image](https://github.com/user-attachments/assets/78e78ac6-140a-46b3-8a03-d5a21d787512)

### Insights
A multi-page report was created on Power BI Desktop and published to Power BI Service.

Following inferences can be drawn from the dashboard;

- step 1 : Market Volume & Variety
Total Models Analyzed: 850+

Leader by Variety: Oppo leads the market with 115 distinct models.

Followers: Apple (97 models) and Honor (91 models) follow closely, indicating high product iteration in these brands.

- step 2 : Hardware Standardization
Front Camera: The most common front camera resolutions are 32MP (204 models) and 16MP (201 models).

Performance: A significant portion of premium devices has standardized at 16GB RAM for high-performance models.

Processor Diversity: Brands like Apple maintain fewer distinct processor types due to vertical integration, while brands like Samsung show higher processor diversity.

- step 3 : Pricing & Brand Positioning
Premium Segment: Apple holds the highest average launch price (~4.0K AED).

Mid-Range Competitors: OnePlus (2.4K AED avg) and Samsung (0.8K AED avg) position themselves as mid-to-high value alternatives.

Value Segment: Brands like Infinix and Realme dominate the high-spec/low-price segments.

- step 4 : Technical Specifications
Weight Trends: Analysis shows a correlation between higher battery capacity (mAh) and increased device weight (g).

Storage: The most frequent storage configuration for high-end models in the current dataset is 256GB/512GB.

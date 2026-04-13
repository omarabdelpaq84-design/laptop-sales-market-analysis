# Laptop Sales & Market Specification Analysis 💻📊

## Project Overview
This project explores the pricing dynamics of the laptop market. By analyzing technical specifications across various brands (Apple, HP, Dell, Lenovo, etc.), the project identifies which hardware configurations drive market value and helps in understanding consumer options across different price segments.

## Project Workflow
The repository is organized into four key stages:

1.  **Raw Data (`Data Before Cleaning`):** The initial dataset containing technical specs such as Screen Resolution, CPU frequency, RAM (GB), Memory (SSD/HDD), and Weights, often requiring formatting and unit conversion.
2.  **Processed Data (`Data After Cleaning`):** The cleaned dataset where units (like 'kg' and 'GB') were handled, and categorical data was standardized for better grouping and analysis.
3.  **Technical Measures (`Measures`):** Statistical breakdowns of the market, including:
    * **Brand Analysis:** Sales volume and total value for top manufacturers like Lenovo, Dell, and HP.
    * **Hardware Impact:** Average price distribution based on CPU types (Intel Core i5/i7 vs AMD) and GPU models (Nvidia vs. Intel HD).
    * **OS Market Share:** Pricing and count analysis for Windows 10, macOS, Linux, and No-OS systems.
4.  **Sales Dashboard (`DashBoard`):** A visual summary of the core findings, highlighting price leaders and the most common hardware configurations in the current market.

## Key Insights Analyzed
- **Price vs. Performance:** Evaluating the premium commanded by high-end CPUs (Intel i7/i9) and dedicated GPUs (Nvidia GTX/RTX).
- **Brand Positioning:** Comparing the average pricing of premium brands like Apple and Razer against high-volume brands like Acer and Asus.
- **Portability Factor:** Analyzing the correlation between laptop weight/inches and its market price.
- **Storage Trends:** Distribution of laptops featuring SSDs versus traditional HDDs or Hybrid drives.

## Tools Used
- **Microsoft Excel:** For data transformation (Power Query) and hardware-based segmentation.
- **Pivot Tables & Statistical Aggregation:** To calculate average prices across complex hardware categories.

## How to Explore
- Start with `Data After Cleaning.csv` to see the structured hardware specs.
- Check `Measures.csv` for the numerical logic and brand performance stats.

---
*Developed as part of a Data Science & Market Analysis portfolio.*

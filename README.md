# Myntra Product & Sales Analysis

An end-to-end data analytics project examining pricing trends, brand positioning, discount strategies, and customer ratings across thousands of fashion and lifestyle products featured on Myntra. This project leverages an extensive dataset to uncover key retail metrics, market gaps, and revenue-driving product categories.

## 📊 Project Overview

The e-commerce fashion sector thrives on dynamic pricing strategies, discount optimization, and brand equity. This project investigates these dynamics across 21,000+ fashion and consumer goods entries, analyzing how pricing structures, discount tiers, and customer ratings interact to impact market performance.

### Key Analytics Focus Areas
* **Pricing & Discount Strategies:** Evaluating the variance between `marked_price` and `discounted_price` to identify high-margin versus heavily discounted categories.
* **Brand Positioning & Equity:** Analyzing premium versus budget brands based on pricing tiers and user rating metrics.
* **Category Performance Breakdown:** Grouping the dataset by core categories (e.g., shirts, watches, sunglasses) to identify top-performing retail segments.
* **Customer Sentiment Mapping:** Investigating patterns between discount depths (`Discount percentage`) and public ratings.

## 🛠️ Tech Stack & Tools

* **Data Analysis & Processing:** Microsoft Excel (Advanced formulas, Data Cleaning pipelines, Pivot Tables)
* **Visualization Environment:** Excel Interactive Dashboard / Pivot Charts
* **Source Dataset:** `myntra.dataset .xlsx`

## 📂 Dataset Architecture & Cleaning

The foundational dataset contains 21,600+ records across multiple operational tabs (`Clean data`, `Analysis`, `Brand Pivot`, and `Dashboard`). Key variables include:

| Attribute | Description |
| :--- | :--- |
| `product_name` / `brand_name` | The descriptive name of the item and its retail brand parent company. |
| `Product _category` | Organized retail categorization (e.g., shirts, sunglasses, watches, hair-appliances). |
| `marked_price` | The original manufacturer's suggested retail price (MSRP). |
| `discounted_price` | The final listed selling price on the live e-commerce platform. |
| `Discount percentage` | Evaluated savings margin provided to the consumer. |
| `rating` / `rating_count` | Average customer star score and total volume of public reviews submitted. |
| `sizes` | Range of inventory stock availability (e.g., S, M, L, Onesize). |

### 🧼 Data Cleaning Pipeline
* **Null Value & Structural Auditing:** Handled incomplete rows in product descriptions and stripped out unneeded blank system columns (`Unnamed: 13` through `Unnamed: 16`).
* **Text Normalization:** Standardized brand nomenclature and category flags to eliminate redundancy during pivot aggregations.
* **Calculated Metrics:** Validated price difference models and calculated precise distribution margins for discount rates.

## 🚀 Analytical Workflows & Framework

1. **Descriptive Statistics & Tiers**
   * Segmented products into premium luxury segments (e.g., Tom Ford, Dyson, Polo Ralph Lauren) versus high-volume budget segments.
   * Visualized pricing skews to locate standard deviations across top luxury accessories.

2. **Pivot & Aggregate Summaries**
   * Constructed localized brand pivots monitoring average rating scores against volume visibility (`rating_count`).
   * Evaluated standard markdown percentages by specific categories to determine which segments depend most on promotional discounts to drive volume.

3. **Interactive Dashboard View**
   * Created dynamic filtering layouts across core retail categories.
   * Visualized the direct correlation between promotional depths and consumer satisfaction markers.

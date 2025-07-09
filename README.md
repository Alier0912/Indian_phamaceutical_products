# Indian Pharmaceutical Products Analysis

## Overview

*  This project analyzes a cleaned dataset of Indian pharmaceutical products to uncover trends, patterns, and insights in the pharmaceutical market.
*  The analysis covers aspects such as manufacturer pricing, brand performance, discontinued products, dosage forms, packaging, primary ingredients, and therapeutic classes.
*  The project leverages Python libraries like pandas, seaborn, matplotlib, and plotly for data manipulation and visualization.

## Project Structure

- `indian_pharmaceutical_products_clean.csv`: Cleaned dataset containing pharmaceutical product information.
- `product_analysis.ipynb`: Jupyter notebook with data cleaning, analysis, and visualization code.

## Dataset Description

The dataset includes the following columns:
- `product_id`: Unique identifier for each product
- `brand_name`: Name of the pharmaceutical brand
- `manufacturer`: Manufacturer of the product
- `price_inr`: Price in Indian Rupees
- `is_discontinued`: Whether the product is discontinued
- `dosage_form`: Dosage form (e.g., tablet, syrup)
- `pack_size`: Size of the product pack
- `pack_unit`: Unit of the pack (e.g., strip, bottle)
- `num_active_ingredients`: Number of active ingredients
- `primary_ingredient`: Main active ingredient
- `primary_strength`: Strength of the primary ingredient
- `active_ingredients`: List of all active ingredients
- `therapeutic_class`: Therapeutic class of the product
- `packaging_raw`: Raw packaging description
- `manufacturer_raw`: Raw manufacturer description

## Setup Instructions

1. **Clone the repository** and navigate to the project directory.
2. **Install dependencies** (recommended: use a virtual environment):

    ```sh
    pip install pandas numpy seaborn matplotlib plotly
    ```

3. **Open** `product_analysis.ipynb` in Jupyter Notebook or Visual Studio Code.
4. **Run the notebook** cells sequentially to reproduce the analysis and visualizations.

## Analysis Insights & Findings

### 1. Manufacturer Pricing
- The top manufacturers by total product price are identified, highlighting market leaders in terms of product value.
- Visualization: Bar chart of top 10 manufacturers by total price.

### 2. Brand Performance
- The top 10 brands by total price are visualized, showing which brands dominate the market financially.
- Visualization: Pie chart of top 10 brands by total price.

### 3. Discontinued Products
- Analysis of discontinued products reveals which manufacturers have the highest value of discontinued products.
- Visualization: Bar chart of manufacturers with most discontinued products.

### 4. Dosage Forms
- The most popular dosage forms are identified, with tablets being the most common.
- Visualization: Bar chart of dosage form frequency.

### 5. Packaging Units
- The most used packaging units are analyzed, providing insights into packaging preferences in the market.
- Visualization: Bar chart of packaging unit frequency.

### 6. Primary Ingredients
- The top 10 primary ingredients used in products are listed, indicating the most common active pharmaceutical ingredients.
- Visualization: Bar chart of primary ingredient frequency.

### 7. Therapeutic Classes
- The distribution of products across therapeutic classes is explored, showing which therapeutic areas have the most products.
- Visualization: Pie chart of therapeutic class distribution.

## Recommendations

1. **Manufacturers** should focus on the most popular dosage forms and packaging units to align with market demand.
2. **Brands** with high total prices should continue to innovate and expand their product lines, while those with discontinued products should analyze reasons for discontinuation and adapt accordingly.
3. **Product Development** should prioritize the most common therapeutic classes and primary ingredients to maximize market reach.
4. **Packaging** strategies should consider consumer preferences for pack size and unit to improve product accessibility and sales.
5. **Market Entry**: New entrants should analyze top-performing brands and manufacturers to identify successful business models and product strategies.

## Conclusion

*  The analysis provides a comprehensive overview of the Indian pharmaceutical product landscape.
*  Key findings highlight the dominance of certain manufacturers and brands,
*  the prevalence of specific dosage forms and packaging units, and the concentration of products in particular therapeutic classes.
*  By leveraging these insights, stakeholders can make informed decisions on product development, marketing, and
*  strategic planning to enhance their competitiveness in the pharmaceutical market.

---

**For further exploration**, consider deeper analysis on pricing trends over time, regional distribution, or patient outcomes associated with different therapeutic classes.

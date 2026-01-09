
# Dominick’s Finer Foods: Customer-Centric Promotion Strategy

## Project Overview

This project analyzes seven years of historical data from Dominick’s Finer Foods, a Chicago-based supermarket chain, to develop a customer-centric framework for promotional decision making. While prior studies on this dataset focused on operational efficiency such as pricing and inventory optimization, our work shifts the focus toward understanding who shops at each store, how customers respond to promotions, and which stores exhibit similar behavioral patterns. The ultimate goal is to improve promotional effectiveness, maximize return on investment (ROI), and allocate marketing resources more strategically.

## Purpose and Business Motivation

Traditional retail promotion strategies often assume that income is the primary driver of price sensitivity. This project challenges that assumption by exploring whether other demographic and behavioral features better explain promotional responsiveness. By identifying the most meaningful drivers of promotional lift and segmenting stores accordingly, the analysis provides actionable guidance for targeted, financially sound promotional strategies rather than one-size-fits-all discounting.

## Data and Analytical Scope

The analysis combines:

* Store-level demographic data derived from 1990 U.S. Census trade areas (e.g., income, education, household structure, age composition).
* Behavioral performance data including customer traffic, sales, promotion frequency, and promotional lift across product categories.

The final analytical dataset includes 45,600 store-week observations across 107 stores, providing a robust foundation for both statistical testing and machine learning–based segmentation.

## Methodology

The project follows the CRISP-DM framework and progresses through three main analytical stages:

### 1. Preliminary Descriptive Analytics and Statistical Testing

Exploratory analysis established baseline store performance and examined correlations between demographics and promotional lift. Contrary to conventional assumptions, education level emerged as a stronger predictor of promotional responsiveness than income.
Chi-square tests of independence validated this finding, showing no statistically significant relationship between simple income categories and promotion response, while highlighting meaningful differences across store zones. These results demonstrated that demographic targeting based solely on income is insufficient and motivated a more sophisticated segmentation approach.

### 2. Cluster Analysis (Store Segmentation)

K-Means clustering was applied to standardized demographic and behavioral variables to segment stores based on both who their customers are and how they respond to promotions. Multiple values of K were evaluated using silhouette scores, inertia, and business interpretability.
A four-cluster solution was selected to balance statistical validity with managerial usefulness, producing the following segments:

* **Promo Enthusiasts**: Highly responsive to promotions with strong positive lift.
* **Steady Shoppers**: High, stable traffic with minimal or negative promotional lift.
* **Family-Focused Shoppers**: Larger households with consistent behavior and modest positive lift.
* **Mature Loyalists**: Older customer bases with stable non-promotional traffic and low price sensitivity.

This segmentation directly addresses the project’s core questions by identifying shared behavioral patterns across stores.

### 3. Implementation: Decision Rules, Cost-Benefit Analysis, and Priority Scoring

The cluster insights were operationalized into a practical decision framework. Cluster-specific ROI thresholds determine whether promotions should be recommended for each store. Promotion costs were modeled using a realistic fixed cost plus a variable component tied to incremental sales.
A priority scoring system was then developed to rank stores when budgets or operational capacity are limited. The score integrates ROI, expected incremental sales, and cluster-level strategic importance, ensuring that promotional resources are allocated to the highest-value opportunities while remaining financially and operationally defensible.

## Key Findings

* Education level is a stronger predictor of promotional responsiveness than income, suggesting that informed consumers behave more strategically when engaging with promotions.
* Income alone is a weak and statistically insignificant driver of promotion response.
* Stores can be meaningfully grouped into four distinct behavioral segments with clear differences in promotion effectiveness.
* Uniform promotion strategies risk eroding margins in low-response stores while underutilizing high-potential locations.

## Recommendations

* Target **Promo Enthusiasts** with frequent, discount-driven campaigns under lower ROI thresholds due to reliable lift.
* Avoid price promotions for **Steady Shoppers**, focusing instead on loyalty programs or service enhancements.
* Use moderate, well-timed promotions for **Family-Focused Shoppers**, aligned with household needs and higher ROI requirements.
* Restrict promotions for **Mature Loyalists** to only exceptionally high-return opportunities.

## Conclusion

This project demonstrates that effective retail promotion strategy requires moving beyond income-based assumptions toward a data-driven, customer-centric approach. By combining descriptive analytics, clustering, and financial decision rules, the analysis provides a transparent and actionable framework for maximizing promotional ROI while maintaining customer equity and operational feasibility. The resulting strategy enables Dominick’s to deploy promotions more intelligently, aligning marketing investment with actual customer behavior rather than intuition alone.


## Authors

* Dedan Deus - https://www.linkedin.com/in/dedan-deus-304908177/
* Emily Bendeck Garay - https://www.linkedin.com/in/emily-bendeck/
* Esha Malhi - https://www.linkedin.com/in/esha-malhi/
* Qazi Fabia Hoq - https://www.linkedin.com/in/qazifabiahoq/ 
* Het Pandya - https://www.linkedin.com/in/pandya01/
* Noelia Cornejo - https://www.linkedin.com/in/noeliacornejo/




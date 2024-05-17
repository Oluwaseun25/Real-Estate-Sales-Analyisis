# Real Estate Sales 2001-2020 GL

## Background

The Office of Policy and Management maintains a listing of all real estate sales with a sales price of $2,000 or greater that occur between October 1 and September 30 of each year. For each sale record, the dataset includes town, property address, date of sale, property type (residential, apartment, commercial, industrial, or vacant land), sales price, and property assessment.

## Problem Statement

In our quest for informed decision-making in real estate, we are presented with a comprehensive dataset encompassing various attributes related to property assessment and sales transactions. This dataset includes information such as the assessed value, sale amount, sales ratio, property type, and more, offering a rich source of insights into the real estate landscape.

## Objectives

1. **Assessment Accuracy**: Evaluate the accuracy of property assessments by comparing assessed values with actual sale amounts and identify any discrepancies.
2. **Market Trends**: Analyze sales ratios to uncover trends in property market values, understanding how sale amounts relate to assessed values across different property types and residential classifications.
3. **Geographical Analysis**: Investigate variations in assessed values, sales amounts, and market ratios across different towns, providing a localized understanding of real estate dynamics.
4. **Property Type Impact**: Examine the impact of property type on assessment accuracy and market trends, exploring whether certain types (e.g., residential, commercial) exhibit distinct patterns.
5. **Non-Use Code Insights**: Explore the significance of non-use codes in property assessment, investigating how these codes influence assessed values and sales transactions.
6. **Assessor and OPM Remarks**: Analyze remarks provided by assessors and the Office of Policy and Management (OPM) to identify factors influencing assessment decisions and potential areas for improvement.

## Expected Outcomes

1. **Uncover insights into the accuracy of property assessments**, identifying areas where adjustments may be necessary.
2. **Gain a nuanced understanding of market trends**, allowing stakeholders to make informed decisions based on current and historical data.
3. **Provide localized insights for different towns**, assisting in regional planning and investment decisions.
4. **Understand the impact of property type on assessment outcomes**, helping to tailor strategies for different segments of the real estate market.
5. **Investigate the role of non-use codes in property assessment**, identifying patterns and potential areas for policy refinement.
6. **Utilize assessor and OPM remarks to improve communication and transparency** in the assessment process.

## Dataset Description

The dataset contains the following features:

1. **Serial Number**: A unique identifier assigned to each record in the dataset.
2. **List Year**: The year in which the property information was listed or assessed.
3. **Date Recorded**: The date when the property information was recorded or updated.
4. **Town**: The name of the town or locality where the property is located.
5. **Address**: The specific address or location details of the property.
6. **Assessed Value**: The assessed monetary value of the property, typically determined by a local assessor for taxation purposes.
7. **Sale Amount**: The amount for which the property was sold, if applicable.
8. **Sales Ratio**: The ratio of the sale amount to the assessed value, providing an indication of the property's market value.
9. **Property Type**: The general category or classification of the property (e.g., residential, commercial, industrial).
10. **Residential Type**: Further classification specifying the residential type (e.g., single-family, multi-family) if applicable.
11. **Non-Use Code**: A code indicating the non-use status of the property, which might include information about exemptions or special classifications.
12. **Assessor Remarks**: Additional remarks or comments provided by the assessor related to the property assessment.
13. **OPM Remarks**: Remarks or comments from the Office of Policy and Management (OPM) related to the property data, providing additional context or information.

## Installation

To get started with the project, you'll need to have Python installed. You can then install the necessary libraries using pip:

```sh
pip install pandas matplotlib seaborn
```

## Usage

1. **Clone the repository:**

```sh
git clone https://github.com/Oluwaseun25/Real-Estate-Sales-Analyisis.git
cd Real-Estate-Sales-Analyisis
```

2. **Run the analysis script:**

The main analysis and visualization are contained in the `Real_Estate_Sales_2001-2020_GL.py` script. You can run this script to generate the visualizations:

```sh
python Real_Estate_Sales_2001-2020_GL.py
```

## Analysis and Recommendations

### Assessment Accuracy

- **Improve the accuracy of property assessments** and ensure consistency between assessed values and actual sale amounts.
- **Identify root causes**: Investigate significant discrepancies between assessed value and sale amount (e.g., cases exceeding the 75th percentile discrepancy of $158,900).
- **Quality Assurance**: Implement measures to enhance assessment procedures, provide additional training to assessors, and conduct regular audits.
- **Continuous Monitoring**: Establish a system for ongoing monitoring and evaluation of assessment practices and discrepancies.
- **Transparency and Communication**: Foster collaboration between assessors, property owners, real estate professionals, and other stakeholders.

### Market Trends

- **Stay informed about market trends** by engaging with local assessors, real estate professionals, and industry experts.
- **Advocate for fairness** in property assessments to ensure equitable taxation and fair treatment of property owners.
- **Condos**: Conduct a comprehensive analysis of the Condo market segment to understand the lower sales ratio trend and adjust pricing strategies accordingly.
- **Residential Types**: Tailor strategies based on market insights for single-family, multi-family, and vacant land properties.

### Geographical Analysis

- **Conduct detailed market analysis** in towns with lower average assessed values but higher sale amounts to understand growth dynamics.
- **Diversify investments** by investing in a mix of towns with varying assessed values and sale amounts to spread risk and maximize returns.
- **Community Development**: Explore initiatives to stimulate property demand and address market imbalances in areas with low market ratios.

### Property Type Impact

- **Collaborate with experts** to identify and implement property type-specific valuation methodologies.
- **Leverage data analytics** to analyze sales trends and pricing dynamics for various property types.
- **Regular Reviews**: Implement regular reviews of property valuations based on updated market data.
- **Compliance and Transparency**: Collaborate with local authorities to establish guidelines for property valuation practices.

### Non-Use Code Insights

- **Ensure thorough documentation** of non-use codes associated with property transactions.
- **Regular Reviews**: Implement regular reviews and validations of property assessments involving non-use codes.

### Assessor and OPM Remarks

- **Enhance data collection processes** to capture more detailed and standardized Assessor Remarks.
- **Implement feedback mechanisms** to gather input on the effectiveness of utilizing Assessor Remarks in property assessments.
- **Optimize the assessment process** by leveraging insights from the analysis to streamline assessments and improve decision-making.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We thank the Office of Policy and Management for providing the dataset and the open-source community for the tools and libraries used in this project.
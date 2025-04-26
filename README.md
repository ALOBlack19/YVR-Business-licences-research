# 📊 Business Licences Analysis (Vancouver, 1997–2024)

## Overview
This project explores the historical and current trends of business licences in Vancouver, Canada, covering data from 1997 to 2024.  
We aim to uncover insights into business dynamics such as stability, growth, seasonal patterns, and opportunities for new business development.

Our analysis leverages **PySpark** for scalable data processing, using Spark DataFrames and SQL queries to manage and analyze millions of licence records.

If you want further explanation and details you can reach the [Analysis Report](Analysis_Report.pdf)
## Dataset
- **Sources**:  
  - [Business licences 1997 to 2012 — City of Vancouver Open Data Portal](https://opendata.vancouver.ca/explore/dataset/business-licences-1997-to-2012/information/)
  - [Business licences 2013 to 2024 — City of Vancouver Open Data Portal](https://opendata.vancouver.ca/explore/dataset/business-licences-2013-to-2024/information/)
- **Format**: CSV
- **Size**: ~1.7 million records combined.

## Project Goals
- 📈 Analyze long-term trends in business openings and closures.
- 🏙️ Identify local areas and business types with growth potential.
- 🧩 Evaluate stability and lifecycle of businesses.
- 🌱 Discover new opportunities based on saturation and seasonal behavior.

## Technologies Used
- **Apache Spark** (PySpark)
- **Spark SQL**
- **Python 3.11**
- **Pandas / Matplotlib** (for local data exploration)
- **Google Colab / Jupyter Notebooks**

## Project Structure
```
YVR-Business-licences-research/
├── data/
│   ├── processed/                  # Cleaned and transformed datasets (if applicable)
│   └── raw/                        # Raw original CSVs from the City of Vancouver
│       ├── business-licences-1997-to-2012.csv
│       └── business-licences-2013-to-2024.csv
├── images/
│   └── yoyformula.jpg              # Year-over-Year growth formula visualization
├── notebooks/
│   └── research.ipynb              # Main analysis notebook
├── .gitignore                      # Git ignore file
├── Analysis Report.pdf             # Project report
├── README.md                       # Project documentation
├── LICENSE.txt                  
├── TERM.md
└── requirements.txt                # Python dependencies

```

## Installation and Setup
1. Install **Python 3.11**  
   👉 [Download Python 3.11](https://www.python.org/downloads/release/python-3110/)

2. Clone the repository:
   ```bash
   git clone https://github.com/0Londero/YVR-Business-licences-research
   cd your-repository-name
   ```

3. Download the **Data folder** and place it into the project root:  
   📂 [Data Folder (Google Drive)](https://drive.google.com/drive/folders/1pui2OLa-2ivz_kmdrB5mKG3KT7V_i7Nf?usp=sharing)

4. Install project dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the notebooks and enjoy exploring! 🚀

## Key Analyses
- **Year-over-Year Growth**: Business openings and closures trends.
- **Most Stable Business Types**: Businesses surviving beyond 5 years.
- **Neighborhood Potential**: Areas with higher business density and growth.
- **Top Categories by Stability and Expansion**: What businesses thrive in Vancouver?
- **Seasonality**: Is there a pattern of new business licences across months?

## Results Preview
- Downtown, Fairview, and Kitsilano consistently attract the highest number of businesses.
- Retail, Health Services, and Contractor sectors dominate in business counts.
- Stability rate varies significantly among different business types.
- Specific local areas show strong potential for new ventures based on low competition and growth trends.

## Contributors
- [Otávio Londero] (Main Research and Development)
- [Amir Oliveira] (Main Research and Development)

## License and Terms of Use

This project uses data provided by the [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/) and complies with the [Open Government Licence – Vancouver](https://vancouver.ca/your-government/terms-of-use.aspx).

Source code in this repository is available under the [MIT License](./LICENSE.txt).

👉 For full usage terms and legal details, please see our [Terms of Use](./TERMS.md).
## Acknowledgements
- City of Vancouver Open Data Portal
- Cornerstone International Community College of Canada
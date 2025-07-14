# UK Company Profiling Project

## 🚀 Project Description

The **UK Company Profiling Project** is a Python-based data analysis pipeline designed to process, enrich, and visualize company data from the UK Companies House registry. Built within a Jupyter Notebook (`Company_Profiling_UK.ipynb`), this project leverages powerful libraries like `pandas`, `requests`, `thefuzz`, `matplotlib`, and `seaborn` to handle data manipulation, API integration, fuzzy matching, and visualization.

### Key Features
- **Data Ingestion**: Loads and processes a CSV dataset (`CompanyV2 (July 2025).csv`) containing detailed information about UK companies, including company names, registration details, addresses, SIC codes, and financial statuses.
- **API Integration**: Connects to the Companies House API to fetch additional company details, enhancing the dataset with real-time information (requires a valid API key).
- **Fuzzy Matching**: Uses `thefuzz` for intelligent string matching to identify similar company names or resolve inconsistencies in the dataset.
- **Data Visualization**: Employs `matplotlib` and `seaborn` to create insightful visualizations, such as histograms of company incorporation dates or bar charts of industry sectors based on SIC codes.
- **Comprehensive Analysis**: Provides a foundation for exploring company statuses (e.g., Active, Liquidation), financial metrics, and mortgage details, enabling deep dives into business trends.

### Why This Project?
This project is a treasure trove for anyone interested in UK business analytics. It’s designed to be:
- **Flexible**: Easily adaptable for specific industries, regions, or company types.
- **Scalable**: Can handle large datasets and integrate additional API endpoints for richer insights.
- **Insightful**: Turns raw data into actionable intelligence through cleaning, enrichment, and visualization.

Whether you're analyzing market competition, studying company lifecycles, or building a business intelligence tool, this project provides a solid starting point.

## 🛠️ Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  ```bash
  pip install pandas requests thefuzz[speedup] matplotlib seaborn
  ```
- A valid Companies House API key (replace `"your_companies_house_api_key"` in the notebook with your key).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/uk-company-profiling.git
   cd uk-company-profiling
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Add your Companies House API key to the notebook by updating the `API_KEY` variable.
4. Place the `CompanyV2 (July 2025).csv` dataset in the project directory (or update the file path in the notebook).

### Usage
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Company_Profiling_UK.ipynb
   ```
2. Run the cells sequentially to:
   - Install dependencies (`thefuzz` with speedup).
   - Load and preprocess the company dataset.
   - Fetch additional data via the Companies House API.
   - Perform fuzzy matching for data cleaning.
   - Generate visualizations and insights.
3. Customize the analysis by modifying the notebook cells to focus on specific industries, regions, or metrics.

### Example Output
- **Data Preview**: Displays the first few rows of the dataset, showcasing company names, addresses, SIC codes, and financial details.
- **Visualizations**: Plots like company status distribution or industry sector breakdowns.
- **Fuzzy Matching Results**: Identifies potential duplicates or similar company names for data quality assurance.

---

## 📊 Example Insights
- **Industry Trends**: Analyze the prevalence of specific SIC codes to identify dominant sectors (e.g., waste management, retail, or artistic creation).
- **Company Longevity**: Explore incorporation dates to understand the age distribution of active companies.
- **Financial Health**: Examine account categories (e.g., Total Exemption Full, Micro Entity) and mortgage statuses to gauge financial stability.

---

## 🧑‍💻 Contributing
Contributions are welcome! Whether it's adding new features, improving visualizations, or optimizing the code, here’s how you can contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to your branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please ensure your code follows PEP 8 guidelines and includes clear documentation.

---

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments
- **Companies House API**: For providing access to comprehensive UK company data.
- **Open-Source Community**: For libraries like `pandas`, `thefuzz`, `matplotlib`, and `seaborn` that power this project.
- **Data Enthusiasts**: For inspiring the pursuit of actionable insights through data.

---

Ready to dive into the world of UK business analytics? Clone this repo, fire up the notebook, and start uncovering the stories hidden in the data! 🚀

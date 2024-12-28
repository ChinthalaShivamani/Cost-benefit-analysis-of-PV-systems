# Cost-benefit-analysis-of-PV-systems
Cost benefit analysis of PV systems

Website link:https://cost-benefit-analysis.netlify.app/


# Cost-Benefit Analysis of PV Systems

## Overview
This project is a comprehensive website designed to assist users in evaluating and comparing photovoltaic (PV) system configurations. By gathering user-specific data and PV system parameters, the platform calculates the **Cost of Energy (COE)** for both grid-tied and dual-mode PV systems, enabling users to make informed decisions regarding optimal solar energy investments.

---

## Key Features

1. **User-Friendly Input Forms**:
   - Intuitive multi-step forms collect user preliminary data, such as location, energy consumption, and preferences.
   - Inputs for PV system configurations, including solar panel specifications, battery capacity, inverter details, and grid outage hours.

2. **Dynamic Cost Analysis**:
   - Calculates the COE for grid-tied and dual-mode PV systems.
   - Provides clear comparisons to help users identify the most cost-effective and sustainable PV configuration.

3. **Interactive Visualizations**:
   - Graphical representation of cost-benefit trends based on user inputs.
   - Displays the relationship between grid outage hours and COE for both configurations.

4. **Sustainability Empowerment**:
   - Encourages eco-conscious decision-making by demonstrating the financial and environmental benefits of solar energy systems.

---

## Technologies Used

- **Frontend**:
  - HTML, CSS, JavaScript for interactive and responsive user interfaces.
  - Animated transitions for seamless navigation between multi-step forms.

- **Backend**:
  - Python/Flask (or your backend framework, if different) for handling user inputs and COE calculations.
  - Algorithms for computing cost-benefit analyses based on real-world PV system data.

- **Visualization**:
  - Libraries like Chart.js or D3.js for dynamic graph generation.

- **Database**:
  - SQL or NoSQL database for storing user input and pre-configured PV system data (if applicable).

---

## Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ChinthalaShivamani/Cost-benefit-analysis-of-PV-systems.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Cost-benefit-analysis-of-PV-systems
   ```

3. **Install Dependencies**:
   If using Python/Flask:
   ```bash
   pip install -r requirements.txt
   ```
   For Node.js-based projects:
   ```bash
   npm install
   ```

4. **Run the Application**:
   For Flask:
   ```bash
   flask run
   ```
   For Node.js:
   ```bash
   npm start
   ```

5. **Access the Website**:
   Open your browser and navigate to `http://localhost:5000` (or the designated port).

---

## Usage Instructions

1. **Step 1: Preliminary Data**:
   - Enter basic information such as location, average monthly energy consumption, and grid outage details.

2. **Step 2: PV System Configuration**:
   - Specify solar panel wattage, battery capacity, inverter details, and any other relevant parameters.

3. **Step 3: Results & Comparison**:
   - View the calculated COE for grid-tied and dual-mode systems.
   - Analyze the graphical trends to make an informed decision.

---

## Folder Structure

```
Cost-benefit-analysis-of-PV-systems/
|
├── static/               # Static files (CSS, JS, images)
├── templates/            # HTML templates for frontend
├── app.py                # Main application logic (Flask)
├── requirements.txt      # Dependencies for the project
├── README.md             # Project documentation
└── ...                   # Additional files/modules
```

---

## Future Enhancements

1. **Integration with Real-Time Data**:
   - Incorporate live solar irradiance and energy pricing data for more accurate calculations.

2. **Advanced Visualizations**:
   - Enhance graphical outputs with interactive features for deeper user insights.

3. **Export Options**:
   - Allow users to download the analysis report as a PDF or CSV.

4. **Localization**:
   - Add multi-language support to expand accessibility.

---

## Contributors

- [Chinthala Shivamani](https://github.com/ChinthalaShivamani)
- [Your Teammate’s Name](GitHub Profile Link)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- Special thanks to mentors and peers for their guidance and feedback.
- Inspired by the growing need for sustainable energy solutions.


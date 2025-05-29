# 🧩 Office Realignment Optimization

This project focuses on optimizing office space allocation across regions to minimize travel hours and operational costs. It involves transitioning from Excel Solver models to structured AMPL-based optimization. 

---

## 🧠 Objectives

- Optimize assignment of employees to regional offices using linear programming.
- Minimize commuting hours and total cost while meeting operational constraints.
- Transition from spreadsheet-based modeling to scalable programmatic optimization in AMPL.

---

## 📈 Methodology

- **Phase I**: Built a basic optimization model using Excel Solver to allocate employees based on commute hours.
- **Phase II**: Used AMPL to develop a scalable, structured optimization model based on regional capacity, cost constraints, and role-based availability.
- **Data Preparation**: Created detailed region-store mappings and aggregated cost/time assumptions to support modeling.

---

## 🔧 Tools & Technologies

- Excel Solver
- AMPL (Algebraic Modeling Language)
- Jupyter Notebook
- Linear Programming
- Python (for documentation and explanation)

---

## 📂 Files

### `data/`
- `realignment_data_ampl.xlsx` – Final structured dataset used for AMPL modeling
- `Part C Workings.xlsx` – Intermediate calculations for round-trips, costs, and mileage assumptions

### `code/`
- `Office_Realignment_Project_Phase_II.ipynb` – Jupyter notebook explaining modeling logic, assumptions, and steps
- `phase1_solver_model.xlsx` – Excel Solver model used in Phase I

### `docs/`
- `Phase_2_report.docx` – Full write-up of Phase II analysis and results
- `Phase2_EssentialComponents.docx` – AMPL formulation: variables, parameters, objective, constraints
- `Phase2_executivesummary.docx` – One-page summary of business value and key insights
- `realignment_project_description.pdf` – Project background and problem definition

---

## 🧠 Key Insights

- AMPL modeling allows greater scalability and control compared to Excel-based approaches.
- Significant reductions in total commute time can be achieved with optimized office allocations.
- Proper data preparation and cost/time structuring are critical for building realistic models.

---

## 📌 Note

This project was completed as an academic assignment. All data used is synthetic and intended solely for educational purposes.

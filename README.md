# 📊 Retail Analytics Project – Qlik Sense Cloud  
### End‑to‑end Data Pipeline: Extraction, Transformation & Visualization

This repository showcases a complete analytics project developed during my Data Analytics training.  
The goal is to demonstrate how to design a structured, well‑documented data pipeline in **Qlik Sense Cloud**, applying best practices in ETL, data modeling, and dashboard development.

---

## 🧱 Project Structure

```
Qlik_CONTOSO/
│
├── 0. Configuration/        → global variables
├── 3. QVS/
│   ├── 1. Extraccion/       → extraction scripts (MySQL + Excel → QVD)
│   └── 2. Transformacion/   → transformation scripts (star schema, calendar)
├── 4. Dashboards/           → screenshots of the final app
├── 5. Variables/            → chart and back-end variables
├── 6. Elementos_Maestros/   → master measures (sales, margins, quantities)
└── 7.Documentation/         → project documentation (PDF)
```

Raw data and generated QVDs are not included in the repository because of their size.


---

## ⚙️ Tech Stack

- **Qlik Sense Cloud** – main analytics platform  
- **QVD & QVS** – optimized storage and ETL scripting  
- **MySQL + Excel** – raw data sources  
- **Visual Studio Code** – script editing and version control  
- **Dropbox** – external versioning for large files  

---

## 📥 Extraction Layer

This stage connects to the original data sources:

- **MySQL database**  
- **Excel file** with complementary information (excluded from GitHub due to size)

Initial checks ensure consistent formats, valid keys, and clean field structures.

---

## 🔄 Transformation Layer

Here the data model is built and optimized:

- Cleaning and standardizing fields  
- Merging and restructuring tables  
- Creating a **star‑schema‑inspired model**  
- Building a **master calendar**  
- Generating QVDs for efficient reloads  

The goal is to produce a scalable, maintainable model ready for analytics.

---

## 📈 Visualization Layer

The final Qlik Sense application includes:

- KPI‑driven dashboards  
- Trend and comparison charts  
- Master items and variables for modularity  
- Thematic sheets designed for decision‑making  

The layout follows UX best practices for BI dashboards.

<img src="4.%20Dashboards/Dashboard.png" width="800"/>

<img src="4.%20Dashboards/Analisis%20Clientes.png" width="800"/>

---

## 🗂 Documentation

The `7.Documentation` folder contains a PDF summarizing:

- The three‑layer architecture  
- ETL workflow  
- Data modeling decisions  
- Best practices applied throughout the project  

---


## 👤 Author

**Santiago Balbarrey**  
Data Analytics | Business Intelligence | Qlik Sense | Sports Analytics  

This project was developed as part of my analytics training, with a strong focus on building clear, documented, and scalable data pipelines.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/santiagobalbarrey/)

You can reach me on LinkedIn for feedback, collaboration, or project discussions.

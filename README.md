# DKPP Peta — Animal Health Mapping System of West Java

> **Food Security and Animal Husbandry Office (DKPP) of West Java Province**  
> Geospatial visualization and statistical analysis of animal health data based on iSIKHNAS

---

## About

This repository contains **geospatial and statistical data processing** code to support decision-making in the field of animal health and livestock management in West Java Province. Data is sourced from **iSIKHNAS** *(Sistem Informasi Kesehatan Hewan Nasional)*, a national system managed by the Ministry of Agriculture of the Republic of Indonesia.

The processed data is presented as **interactive web-based maps** accessible to relevant stakeholders.

---

## Repository Structure

```
dkpp-peta/
│
├── peta-penyakit/          # Animal disease map data and visualization
├── peta-vaksinasi/         # Vaccination map data and visualization
├── target-vaksinasi/       # Vaccination target data
├── sv-masuk/               # Veterinary certificate data for animals entering West Java
├── sv-keluar/              # Veterinary certificate data for animals leaving West Java
├── moran-index/            # Moran's Index calculation (spatial analysis)
├── ampm-index/             # AMPM Index calculation
│
├── index.html              # Main page / map dashboard
├── penyakit.html           # Animal disease distribution map
├── vaksinasi.html          # Vaccination realization map
├── target-vaksinasi.html   # Vaccination target map
├── lalu-lintas.html        # Animal movement / traffic map
├── moran-index.html        # Moran's Index visualization
└── ampm-index.html         # Visualization of animal sales location distribution in West Java
```

---

## Data Coverage

### Animal Health Maps
- Distribution of animal disease cases by regency/city in West Java
- Vaccination realization and targets for livestock
- Area-based animal health status monitoring

### Animal Movement (Traffic)
- Movement of animals entering West Java Province (Incoming Veterinary Certificate)
- Movement of animals leaving West Java Province (Outgoing Veterinary Certificate)
- Monitoring of sacrificial animal distribution

### Spatial Statistical Analysis
- **Moran's Index** — Spatial autocorrelation analysis of animal diseases
- **AMPM Index** — Index calculation based on livestock data

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| R / RStudio | Data processing, statistical analysis, and visualization |
| HTML / JavaScript | Interactive web-based map presentation |
| CSS | Map interface styling |
| iSIKHNAS | Sistem Informasi Kesehatan Hewan Nasional |

---

## Data Sources

Data in this project is sourced from:

- **iSIKHNAS** *(Sistem Informasi Kesehatan Hewan Nasional)* — Ministry of Agriculture, Republic of Indonesia
- Administrative boundary data of West Java Province
- Livestock data from DKPP West Java Province

> This data is official and intended solely for official government use. Any use of the data for other purposes requires permission from the relevant institution.

---

## Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Keswanvet/dkpp-peta.git
   cd dkpp-peta
   ```

2. **Open the map in a browser:**  
   Open `index.html` directly in a browser, or run a simple local server:
   ```bash
   python -m http.server 8080
   ```
   Then navigate to `http://localhost:8080` in your browser.

---

## Author

**Tio M**  
Dinas Ketahanan Pangan dan Peternakan Provinsi Jawa Barat

---

## Collaboration

Open to collaboration in the following areas:
- Geospatial visualization development for livestock data
- Spatial statistical analysis of animal health
- Integration of iSIKHNAS data with other platforms

---

## License

This project was developed for internal use by the Food Security and Animal Husbandry Office (DKPP) of West Java Province. 
---

<div align="center">
  <sub>Developed to support food security and animal health in West Java</sub>
</div>

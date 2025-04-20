# Reproducing Image Type Analysis from: *Looks matter! A Comparative Analysis of Image Use on Chinese and Western Municipal Websites*

This repository reproduces the data analysis and visualization from the following publication:

> **Li, Y., Karreman, J., & de Jong, M. (2024).** *Looks matter! A Comparative Analysis of Image Use on Chinese and Western Municipal Websites.* Proceedings of the 2024 IEEE International Professional Communication Conference (ProComm), 59–66. https://doi.org/10.1109/ProComm61427.2024.00018 

---

## 🧪 Research Overview

This research investigates how municipal websites in **China** and the **West** use visual imagery differently. It compares **seven types of images** across 100 Chinese and 100 Western municipal homepages.

### 🔍 Image Type Definitions

| Image Type       | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Drawing**       | Hand-drawn illustrations or clipart graphics                                |
| **Icon**          | Functional icons used in navigation or menus                                |
| **Logo**          | City or governmental brand marks                                            |
| **None of above** | No images present                                                           |
| **Photo**         | Realistic photographs (e.g., people, cityscapes)                            |
| **Poster**        | Promotional banners or political campaign posters                           |
| **QR code**       | Scannable codes linking to external resources                               |

---

## 📊 Key Findings

- **Chinese municipal websites** contain **more images overall** than Western sites.
- **Icons** and **posters** are used more frequently on Chinese websites.
- **Photos** and **no imagery** are more common on Western sites.
- A Chi-square test confirmed statistically significant differences:
  - **Chi-square = 2946.7**, **df = 6**, **p < .001**
  - **Cramér’s V = 0.39**, suggesting a **moderate to strong association**.

📈 The visual breakdown is available at: `outputs/figures/percentage_image_type.png`.

---

## 📁 Project Structure

municipal-analysis/ ├── R script/ │ └── analysis.Rmd # Main analysis script ├── data/ │ ├── 2.2.4.1 West image type.csv │ └── 2.2.4.2 Chinese image type.csv ├── outputs/ │ ├── figures/ # Visual output (.png) │ └── tables/ # Statistical tables (.csv, .txt) ├── .RData ├── .Rhistory ├── .Rprofile ├── municipal-analysis.Rproj ├── renv.lock # Reproducible package environment └── README.md # Project overview and instructions


---

## ▶️ How to Reproduce This Analysis

### 📦 Step 1: Install R and RStudio

Make sure R (≥ 4.1.0) and RStudio are installed on your machine.

### 📥 Step 2: Clone This Repository

```bash
git clone https://github.com/your-username/municipal-analysis.git
cd municipal-analysis
```
### 🔄 Step 3: Restore the Reproducible Environment
```r
install.packages("renv")
renv::restore()
```

### 🧮 Step 4: Run the Analysis
Open the RStudio project `municipal-analysis.Rproj`
Then open and run: `R script/analysis.Rmd`

All visual and statistical outputs will be saved under the `outputs/` directory.

## 🔓 License
This work is distributed under the MIT License.

You are free to use, modify, and distribute this project — with proper attribution.

© 2025 Yaxing Li | For academic and research transparency.

## 📬 Contact
Yaxing Li
PhD Researcher, University of Twente
📧 yaxing.li@utwente.nl
🌐 ORCID: 0000-0002-6750-8429

## 📬 Contact

For questions, reach out to:

**Yaxing Li**\
PhD Researcher, University of Twente\
📧 [yaxing.li@utwente.nl]()\
🌐 [https://orcid.org/0000-0002-6750-8429](https://orcid.org/0000-0002-6750-8429)

<!--EndFragment-->

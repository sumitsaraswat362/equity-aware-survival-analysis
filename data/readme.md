# Data Directory

The raw SEER datasets (`seer_2004_2015.csv` and `seer_external_2016_2018.csv`) are not included in this repository due to:
1. **GitHub File Size Limits:** The raw files exceed the 25MB individual file limit.
2. **SEER Data Use Agreement:** Redistribution of raw SEER patient-level data is restricted.

### How to Replicate this Study:
1. **Request Access:** Go to [seer.cancer.gov](https://seer.cancer.gov/) and request access to the Breast Cancer Research Data.
2. **Download Cohort:** Download the 2004–2018 Breast Cancer registry.
3. **Setup:** Place the resulting CSV files into this `data/` directory.
4. **Execute:** Run the notebook located in the `notebooks/` directory.

**Note:** Processed summary statistics and aggregated results are available in the `/results` folder.

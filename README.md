# Comparative Analysis of Hospital Quality Metrics  
## Johns Hopkins Hospital vs. Top U.S. Hospitals

## Overview

This project presents a comparative analysis of hospital performance and quality metrics between Johns Hopkins Hospital (JHH) and top-ranked U.S. hospitals. The evaluation focuses on patient satisfaction, readmission rates, mortality outcomes, and staff responsiveness—using structured health services data from publicly available sources.

The aim is to assess key quality indicators, highlight performance strengths and gaps, and provide actionable insights to inform hospital benchmarking and quality improvement efforts.

## Objectives

- Analyze publicly available hospital performance data  
- Compare key metrics across JHH and top U.S. hospitals  
- Visualize differences in satisfaction, readmission, and mortality  
- Identify opportunities for quality improvement and operational excellence

## Repository Contents

This repository includes Jupyter Notebooks that analyze and visualize the following indicators:

- Patient Communication Satisfaction (Doctor, Nurse)  
- Discharge Information & Responsiveness  
- Overall Hospital Rating  
- Readmission Rates (Heart Failure, Pneumonia)  
- Mortality Rates (Heart Failure, Pneumonia, AMI)  
- Staff Responsiveness & Satisfaction  

Each notebook provides statistical comparisons and visual interpretations between Johns Hopkins Hospital and its national peers.

## Key Quality Measures & Measure IDs

| Indicator                    | Measure Name                                     | Measure ID                |
|------------------------------|--------------------------------------------------|---------------------------|
| Nurse Communication          | HCAHPS Nurse Communication Score                 | H_COMP_1_LINEAR_SCORE     |
| Doctor Communication         | HCAHPS Doctor Communication Score                | H_COMP_2_LINEAR_SCORE     |
| Staff Responsiveness         | HCAHPS Staff Responsiveness                      | H_COMP_3_LINEAR_SCORE     |
| Discharge Information        | HCAHPS Discharge Communication                   | H_COMP_6_LINEAR_SCORE     |
| Overall Hospital Rating      | HCAHPS Overall Rating                            | H_HSP_RATING_LINEAR_SCORE |
| Heart Failure Mortality Rate | 30-day Mortality Rate for HF Patients            | MORT_30_HF                |
| Readmission Rate             | Hospital-wide 30-Day Readmission Rate            | READM-30-HOSP-WIDE        |
| ED Abandonment Rate          | Patients Who Left ED Before Being Seen           | OP-22                     |

## Key Insights

- JHH outperforms national benchmarks in nurse and doctor communication.
- Readmission rates for heart failure patients at JHH are slightly above peers, highlighting a potential target for care coordination improvements.
- Staff responsiveness and discharge communication indicators show room for process refinement and patient experience enhancement.

## Tools & Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statistical Process Control (SPC) charts

## Data Sources

- CMS Hospital Compare Data: https://data.cms.gov/provider-data  
- U.S. News & World Report Hospital Rankings: https://health.usnews.com/best-hospitals  
- Publicly reported HCAHPS, outcome, and process of care datasets

## Related Skills Demonstrated

- Healthcare quality benchmarking  
- KPI visualization and interpretation  
- Comparative health systems analytics  
- Statistical process control (SPC) in healthcare  
- Use of structured health services data for performance assessment  

## Author

Alanoud Alturki  
Health Data Analyst | Pharmacist  
MS in Health Informatics · MS in Health Data Analysis · PhD Student  
Riyadh, Saudi Arabia  
LinkedIn: https://www.linkedin.com/in/alanoud-alturki-5601b2b5

## License

This project is for educational and research purposes only.  
All data used is publicly available and should be cited appropriately if reused.


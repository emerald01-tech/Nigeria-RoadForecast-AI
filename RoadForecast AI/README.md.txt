# RoadForecast AI: Nigerian Traffic Safety Predictor

![Banner](docs/banner.png) (Optional: Add a visual)

## Repository Structure
```bash
Nigeria-Traffic-Safety/
+-- data/               # Crash datasets and reports
¦   +-- July Knowledge Showcase.pdf
+-- src/                # Source code
¦   +-- travel_safety_app.py
+-- README.md           # This documentation
+-- requirements.txt    # Python dependencies
```

## Quick Start
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the application:
   ```bash
   python src/travel_safety_app.py
   ```

## About the Data
Analysis of 43,262 crashes (2020-2024) from FRSC Nigeria, including:
- High-risk states (Lagos, Oyo, FCT)
- Weather impact (38% crashes during rain)
- Road type fatalities (Highways: 52%)

## AI Model Details
| Feature               | Specification          |
|-----------------------|------------------------|
| Algorithm             | Random Forest          |
| Accuracy              | 84% (F1-score)         |
| Input Features        | RoadType, Weather, LightCondition |
| Prediction Output     | Fatality Risk (0-100%) |

## Contact
For dataset access or collaboration:  
[honeyhive500@gmail.com] | [Your LinkedIn Profile]
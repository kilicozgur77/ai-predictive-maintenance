# AI Predictive Maintenance for Industrial Machinery

Final project for the Building AI course. Building AI course project.

## Summary
This project develops an AI-based predictive maintenance model for industrial rotating machinery (pumps, bearings, and CNC spindles). By analyzing multi-sensor vibrational and thermal time-series data, it detects anomalies and predicts machine failure before catastrophic downtime occurs. Building AI course project.

## Background
In modern mechanical manufacturing and plant engineering, unplanned equipment downtime leads to severe financial losses, safety hazards, and wasted resources.
* Unplanned Downtime: Machinery breakdown causes expensive production halts in manufacturing plants.
* Over-Maintenance: Replacing parts on fixed schedules wastes still-usable components.
* Motivation: As a mechanical engineer, my goal is to bridge classical mechanics with machine learning to optimize machine lifespan and operational efficiency.

## How is it used?
The solution operates as an automated monitoring pipeline in industrial production environments:
1. Sensors continuously measure vibration (accelerometers) and surface temperature on critical bearings and motors.
2. Feature vectors (frequency spectra, RMS, peak-to-peak amplitude) are extracted in real-time.
3. The AI model flags abnormal patterns, calculates the probability of mechanical wear, and alerts maintenance engineers via a SCADA/MES dashboard well before failure.

## Data sources and AI methods
* Data Sources: Uses standardized open-source industrial datasets (e.g., NASA Bearing Data Set and Case Western Reserve University Bearing Data) alongside real-time factory PLC sensor streams.
* AI Methods: 
  * Linear & Logistic Regression for baseline wear scoring.
  * K-Nearest Neighbors (KNN) and Random Forests for fault classification (healthy vs. degraded).
  * Neural Networks (MLP / CNN on spectrograms) to predict Remaining Useful Life (RUL).

## Challenges
* High environmental noise in industrial plant floors.
* Rarity of real failure data in well-maintained production lines (imbalanced datasets).
* Sensor calibration drift over prolonged operating cycles.

## What next?
Next steps include deploying the model directly onto edge computing devices (such as industrial Raspberry Pi / Siemens IOT gateways) for real-time inference without cloud latency, and integrating digital twin simulations.

## Acknowledgments
* Course structure and inspiration from University of Helsinki & Reaktor (Elements of AI: Building AI).
* Public vibration datasets provided by the NASA Prognostics Center of Excellence.# AI Predictive Maintenance for Industrial Machinery

Final project for the Building AI course. Building AI course project.

## Summary
This project develops an AI-based predictive maintenance model for industrial rotating machinery (pumps, bearings, and CNC spindles). By analyzing multi-sensor vibrational and thermal time-series data, it detects anomalies and predicts machine failure before catastrophic downtime occurs. Building AI course project.

## Background
In modern mechanical manufacturing and plant engineering, unplanned equipment downtime leads to severe financial losses, safety hazards, and wasted resources.
* Unplanned Downtime: Machinery breakdown causes expensive production halts in manufacturing plants.
* Over-Maintenance: Replacing parts on fixed schedules wastes still-usable components.
* Motivation: As a mechanical engineer, my goal is to bridge classical mechanics with machine learning to optimize machine lifespan and operational efficiency.

## How is it used?
The solution operates as an automated monitoring pipeline in industrial production environments:
1. Sensors continuously measure vibration (accelerometers) and surface temperature on critical bearings and motors.
2. Feature vectors (frequency spectra, RMS, peak-to-peak amplitude) are extracted in real-time.
3. The AI model flags abnormal patterns, calculates the probability of mechanical wear, and alerts maintenance engineers via a SCADA/MES dashboard well before failure.

## Data sources and AI methods
* Data Sources: Uses standardized open-source industrial datasets (e.g., NASA Bearing Data Set and Case Western Reserve University Bearing Data) alongside real-time factory PLC sensor streams.
* AI Methods: 
  * Linear & Logistic Regression for baseline wear scoring.
  * K-Nearest Neighbors (KNN) and Random Forests for fault classification (healthy vs. degraded).
  * Neural Networks (MLP / CNN on spectrograms) to predict Remaining Useful Life (RUL).

## Challenges
* High environmental noise in industrial plant floors.
* Rarity of real failure data in well-maintained production lines (imbalanced datasets).
* Sensor calibration drift over prolonged operating cycles.

## What next?
Next steps include deploying the model directly onto edge computing devices (such as industrial Raspberry Pi / Siemens IOT gateways) for real-time inference without cloud latency, and integrating digital twin simulations.

## Acknowledgments
* Course structure and inspiration from University of Helsinki & Reaktor (Elements of AI: Building AI).
* Public vibration datasets provided by the NASA Prognostics Center of Excellence.

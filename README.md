**Groundwater Pollution Detection via Anomaly Detection**

This project demonstrates how to identify potential groundwater pollution events using unsupervised anomaly detection techniques on synthetic data.

📊 **Overview**

We simulate groundwater quality parameters and inject synthetic pollution events to train an Isolation Forest model. The model is used to detect anomalous samples which may represent pollution.

📁 Files

groundwater_anomaly_detection_with_summary.xlsx`: 
**Data** sheet: Contains the simulated groundwater data with an anomaly label (0 = normal, 1 = anomaly).
**Summary** sheet: Shows total sample count, number of detected anomalies, and the percentage of anomalies.

🔍 **Features**

- Synthetic dataset with realistic environmental parameters:
  **pH**
  **TDS (Total Dissolved Solids)**
  **Nitrate**
  **Arsenic**
  Anomaly detection using `Isolation Forest`.
  Data export to Excel with summary analysis.

🧪 How It Works

1. **Data Simulation**:
   Normal groundwater conditions are generated based on typical environmental statistics.
   Anomalies are introduced with abnormal pollutant concentrations.

2. **Anomaly Detection**:
   Scaled data is fed into the Isolation Forest model.
   The model flags samples that deviate from expected behavior.

3. **Export & Analysis**:
   Results are exported to Excel.
   A summary sheet shows detection statistics.

🛠 Requirements

Python 3.8+
Libraries:
`numpy`
`pandas`
`scikit-learn`
`openpyxl`
`matplotlib`
`seaborn`

Install dependencies using:

```bash
pip install numpy pandas scikit-learn openpyxl matplotlib seaborn


Author
Tarinabo williamtarinabo@gmail.com

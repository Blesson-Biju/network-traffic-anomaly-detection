Network Traffic Anomaly Detection using Isolation Forest
📌 Project Overview

This project focuses on detecting anomalous network traffic sessions using Machine Learning and validating the results through Power BI visualization.

An Isolation Forest model was applied to identify suspicious network behavior based on traffic characteristics.

📊 Dataset Information

Total Sessions: 282

Features: 19

Suspicious Sessions Detected: 15 (~5%)

Traffic Type: HTTPS (Port 443)

Key Features Used:

bytes_in

bytes_out

session_duration

src_ip

timestamp

🤖 Machine Learning Approach

Algorithm Used: Isolation Forest

Why Isolation Forest?

Effective for anomaly detection

Does not require labeled anomaly data

Efficient on high-dimensional datasets

Model Output:

-1 → Suspicious

1 → Normal

The model identified high-volume outlier sessions that significantly deviated from baseline traffic behavior.

📈 Dashboard Insights (Power BI)

The dashboard visualizes:

Traffic distribution (Normal vs Suspicious)

Average Bytes In/Out comparison

Source IP concentration analysis

Time-based traffic patterns

Geographic distribution

Key Findings:

Suspicious sessions contribute disproportionately high traffic volume.

Anomalies are concentrated in a small number of source IPs.

Suspicious sessions exhibit extreme deviation in average data transfer.

🛠 Tools & Technologies

Python

Pandas

Scikit-learn

Isolation Forest

Power BI

Jupyter Notebook

🚀 Future Improvements

Incorporate additional network behavior features

Apply real-time anomaly detection

Compare with other anomaly detection algorithms (LOF, One-Class SVM)

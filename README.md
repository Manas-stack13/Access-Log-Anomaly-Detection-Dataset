# Access-Log-Anomaly-Detection-Dataset
A novel dataset for access log anomaly detection, combining real enterprise access logs with synthetic augmentation

## Overview
This dataset is designed for **anomaly detection in access logs**, particularly focusing on identity-based threats such as **unauthorized access, privilege escalation, and session anomalies**. It is built using a **hybrid approach**, combining **real enterprise access logs** with **synthetic anomalies** to ensure a well-balanced representation of both benign and malicious events.

## Features
- **5000 log entries** covering various enterprise access scenarios.
- Includes **session metrics, login attempts, timestamps, IP addresses, device types,** and **anomaly scores**.
- Covers a wide range of **benign and malicious behaviors**.
- Structured to support **Machine Learning (ML) and Deep Learning (DL) implementations**.

## File Format
The dataset is provided in `.xls` format.

## Data Fields
| Column Name        | Description |
|--------------------|-------------|
| `timestamp`       | Date and time of the log event. |
| `masked_user`     | Anonymized user identifier. |
| `source_ip`       | IP address of the originating event. |
| `destination_ip`  | IP address of the target system. |
| `action`          | Action performed (e.g., login, logout, delete, modify). |
| `resource`        | Accessed resource (e.g., admin panel, files). |
| `device_type`     | Type of device used (desktop, mobile, tablet). |
| `anomaly_score`   | Computed anomaly score (continuous value). |
| `target`          | Ground truth label (`benign` or `malicious`). |

## Use Cases
This dataset can be used for:
- **Training anomaly detection models** for cybersecurity.
- **Evaluating ML/DL models** in access log-based security applications.
- **Benchmarking hybrid anomaly detection approaches**.


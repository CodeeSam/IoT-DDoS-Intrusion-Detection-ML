# IoT DDoS Intrusion Detection Using Machine Learning

This repository contains an exploratory machine learning workflow for detecting Distributed Denial-of-Service (DDoS) intrusion patterns in Internet of Things (IoT) network traffic.

The project was originally developed as one of my earlier applied machine learning projects and has been cleaned for better readability, structure, and reproducibility.

## Project Overview

Internet of Things (IoT) devices are increasingly used in homes, industries, healthcare systems, and smart environments. However, many IoT devices have limited computational resources, weak security configurations, and high network exposure, making them vulnerable to cyberattacks such as Distributed Denial-of-Service (DDoS) attacks.

DDoS attacks can overload network resources by flooding systems with malicious traffic, which may disrupt device communication, reduce service availability, and compromise the reliability of IoT-based systems.

This project applies classical machine learning techniques to IoT network traffic data to explore how intrusion patterns can be identified from traffic-related features.

## Objectives

The main objectives of this project are to:

- preprocess IoT network traffic data
- inspect the dataset structure and feature distribution
- select relevant predictive features
- train machine learning models for intrusion detection
- evaluate model performance using standard classification metrics

## Repository Structure

```text
IoT-DDoS-Intrusion-Detection-ML/
├── README.md
├── iot_ddos_dataset.csv
├── ddos_intrusion_detection_iot.ipynb
├── requirements.txt
├── .gitignore
└── LICENSE

# NIDS

This is a NIDS UI that predicts whether the pcap file captured is benign or malicious by running it through the RandomForestClassifier model

This project implements a Machine Learning–based Network Intrusion Detection System (NIDS) capable of classifying network traffic as Normal or Attack using supervised learning. The system is trained on a preprocessed dataset and utilizes a RandomForest model to detect malicious network behavior with high accuracy. It includes a full pipeline for data cleaning, feature selection, model training, and flow extraction from PCAP/PCAPNG files. A user-friendly GUI built with Tkinter allows users to upload packet captures, automatically extract flow-level features, and view predictions in real time. The system is designed to help analyze suspicious traffic, support cybersecurity research, and provide an accessible ML-powered intrusion detection framework.

RUN the gui_app.py

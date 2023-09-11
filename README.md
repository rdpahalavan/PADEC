# PADEC (Packet Describer)
# Explainability of Network Intrusion Detection using Transformers: A Packet-Level Approach

Welcome to the GitHub repository containing all the files and documents related to the thesis titled "Explainability of Network Intrusion Detection using Transformers: A Packet-Level Approach".

## 📂 Repository Structure

- **Code**: Contains the Jupyter notebooks written in Python.
- **Files**: Hosts various files used in this research such as `.csv`, `.npy`, and `.pkl`.
- **Thesis**: The finalized thesis document can be found in this folder in PDF format.

## 📝 Thesis Abstract

Network Intrusion Detection Systems (NIDS) are critical in ensuring the security of connected computer systems by actively detecting and preventing unauthorized activities and malicious attacks. Machine learning (ML) and deep learning (DL) based NIDS models leverage algorithms that learn from historical network traffic data to identify patterns and anomalies to capture complex relationships. 

The primary objective of this research is to generate tags and descriptions for the packets that are difficult to classify by the NIDS. Most NIDS datasets that are publicly available have focused on flow data, offering aggregated information about network connections, and have played a crucial role in enabling researchers and network security professionals to design and develop flow-based NIDS solutions.

While flow records provide valuable information for detecting network-level anomalies and attacks, they do not consider packet-level information and payload contents. In this research, we propose a packet-level approach for NIDS that leverages the flow information with the packet header fields and payload. 

To facilitate this research, we have curated a comprehensive Packet-level dataset constructed by extracting the Packet Capture (PCAP) files from two widely used flow-level datasets, namely CIC-IDS2017 and UNSW-NB15. 

Recent advancements in Natural Language Processing (NLP) have demonstrated the effectiveness of Transformer-based models in handling sequence data with tasks such as token classification and text generation. We have adapted this technology to NIDS to extract key features and characteristics of the header and payload in the context of various attacks. Unlike traditional classification methods that assign predefined labels to network packets, this method focuses on generating tags based on the packet signature that explains the packet content and potential risks. The tags and descriptions offer network security professionals a tool to comprehend suspicious packets with an unfamiliar or potentially malicious signature, assess their nature, and help make informed decisions promptly.

## 🔗 External Resources and Packages

To further assist in this research, several Python packages have been developed and stored in separate GitHub repositories:

- **BERTSimilar**: This tool provides similar words and embeddings using BERT models. Check it out [here](https://github.com/rdpahalavan/BERTSimilar).

- **NIDS Datasets**: This repository offers a way to download the UNSW-NB15 and CIC-IDS2017 Datasets used in this research. Available [here](https://github.com/rdpahalavan/nids-datasets).

- **NIDS Transformers**: Focused on tag generation and text generation inference for network packets using transformers. Explore more [here](https://github.com/rdpahalavan/nids-transformers).

---

We hope you find this repository useful for your research or project. If you have questions or feedback, please open an issue or reach out directly.

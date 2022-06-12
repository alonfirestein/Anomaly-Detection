# Network-Attack-Anomaly-Detection

This repository represents a project from my "Methods for Detecting Cyber Attacks" University course.  
  
The main goal of this project is to detect attacks using network data from physical hosts and finding which hosts are anomalous/ outliers.


### Dataset:
Each record has 4 features that are described in the "Data fields" section.  
- record ID - The unique identifier for each connection record.  
- duration_ This feature denotes the number of seconds (rounded) of the connection. For example, a connection for 0.17s or 0.3s would be indicated with a “0” in this field.  
- src_bytes This field represents the number of data bytes transferred from the source to the destination (i.e., the number of out-going bytes from the host).  
- dst_bytes This feature represents the number of data bytes transferred from the destination to the source (i.e., the number of bytes received by the host).  
  
  

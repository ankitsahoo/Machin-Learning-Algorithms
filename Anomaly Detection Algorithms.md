### **Anomaly Detection Algorithms**

These algorithms are used to identify rare or abnormal patterns in data.

------

### **1. Isolation Forest**

- What it does

  :

  - Detects anomalies by randomly splitting data into smaller regions using decision trees.
  - Anomalies are isolated faster because they differ significantly from normal data.

- Example

  :

  - **Credit Card Fraud Detection**: Identifies unusual transaction patterns (e.g., an abnormally high purchase or one in a new location).

------

### **2. One-Class SVM**

- What it does

  :

  - Learns the boundary that separates normal data from potential anomalies.
  - It works well for data where anomalies are sparse.

- Example

  :

  - **Network Intrusion Detection**: Detects unusual network traffic that doesn’t conform to normal patterns, flagging potential attacks.

------

### **3. Autoencoders**

- What it does

  :

  - Compresses input data into a smaller representation and reconstructs it.
  - If the reconstruction error is high, the input is flagged as an anomaly.

- Example

  :

  - **Manufacturing Defect Detection**: Identifies defective products by reconstructing normal product features and flagging items with high reconstruction errors.

------

### **Key Difference**:

- **Isolation Forest**: Focuses on separating anomalies using random splits.
- **One-Class SVM**: Learns a boundary for normal data.
- **Autoencoders**: Flags anomalies based on reconstruction errors in a neural network.
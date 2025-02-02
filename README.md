# **Differential Privacy and Homomorphic Encryption for Secure Data Analysis**

## **Overview**
This project implements cutting-edge privacy-preserving techniques on a smart metering dataset collected in Tetouan, Morocco. The primary goal is to enhance data privacy using **Differential Privacy** and **Homomorphic Encryption**, enabling meaningful analysis of energy consumption trends without compromising individual privacy. This project earned the **top recognition** in the Data Privacy and Security course at the **Illinois Institute of Technology**.

---

## **Key Features**

- **Differential Privacy**:  
  Applied **Laplace** and **Gaussian mechanisms** to anonymize sensitive data, ensuring individuals' identities remain untraceable while maintaining dataset utility.  

- **Homomorphic Encryption**:  
  Enabled secure computations on encrypted data, ensuring sensitive information stays confidential during processing and analysis.  

- **Graphical User Interface (GUI)**:  
  A user-friendly **PyQt5-based GUI** allows users to:
  - Apply privacy mechanisms to selected columns.
  - Visualize the privacy-enhanced dataset effortlessly.

---

## **Dataset**

- **Source**: Smart metering dataset from Tetouan, Morocco.
- **Entries**: 52,416 records collected every 10 minutes across three distinct zones.
- **Features**:
  - **Environmental data**: Temperature, Humidity, Wind Speed.
  - **Energy consumption data**: Comprehensive electricity usage for trend analysis.

---

## **Technologies Used**

- **Programming Language**: Python  
- **Libraries**:
  - `diffprivlib`: For implementing differential privacy mechanisms.
  - `tenseal`: For secure computations using homomorphic encryption.
  - `PyQt5`: For building the user-friendly GUI.

---

## **Installation**

Follow the steps below to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ssam246/Differential_Privacy_Analysis
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python main.py
   ```

---

## **Usage**

### **Differential Privacy**
1. Load your dataset into the GUI.  
2. Select the columns to anonymize.  
3. Choose a privacy mechanism:
   - **Laplace Mechanism**: Ideal for numeric data.
   - **Gaussian Mechanism**: For more robust anonymization.  
4. Apply the selected mechanism and visualize the results in the GUI.

### **Homomorphic Encryption**
1. Encrypt selected columns of data using the GUI.  
2. Perform secure computations (e.g., aggregations) directly on the encrypted data.  
3. Decrypt the data when required and visualize the results.  

---

## **Future Work**

- **Exponential Mechanism**:  
  Introduce support for the exponential mechanism to enhance privacy protection for categorical (non-numeric) data.  

- **Additional Privacy Techniques**:  
  Explore hybrid models combining differential privacy and homomorphic encryption to improve data utility without compromising privacy guarantees.

---

## **Contributing**

We welcome contributions to improve this project!  
Follow these steps to contribute:
1. Fork the repository.  
2. Implement your improvements or fix issues.  
3. Submit a pull request with a detailed explanation of your changes.

---

## **License**

This project is licensed under the **MIT License**.  
Refer to the [LICENSE](LICENSE.md) file for more details.

---

## **Acknowledgments**

This project was developed as part of the **Data Privacy and Security course** at the **Illinois Institute of Technology**.  
Special thanks to the project team members and course instructors for their invaluable guidance and support.

**Differential Privacy and Homomorphic Encryption for Secure Data Analysis**
**Overview
**This project implements privacy-preserving techniques on a smart metering dataset collected in Tetouan, Morocco. The primary goal is to enhance data privacy using differential privacy and homomorphic encryption while allowing for meaningful analysis of energy consumption trends. This project was recognized as the top project in the Data Privacy and Security course at Illinois Institute of Technology.

**Key Features**
Differential Privacy: Applied Laplace and Gaussian mechanisms to anonymize sensitive data, preventing unauthorized identification of individuals.
Homomorphic Encryption: Enabled secure computations on encrypted data, ensuring that sensitive information remains confidential throughout the analysis process.
Graphical User Interface (GUI): Developed using PyQt5, the GUI allows users to easily apply privacy mechanisms to selected data columns and visualize the results.

**Dataset**
Source: Smart metering data from Tetouan, Morocco.
Entries: 52,416 records, collected every 10 minutes across three different zones.
Features: Includes temperature, humidity, wind speed, and energy consumption data for comprehensive analysis.

**Technologies Used**
Programming Language: Python
Libraries:
diffprivlib for differential privacy mechanisms
tenseal for homomorphic encryption
PyQt5 for building the GUI

**Installation**
To run this project locally, follow these steps:

Clone the repository:
git clone [repository URL]
cd [repository folder]

Create a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the required dependencies:
pip install -r requirements.txt

Run the application:
python main.py

**Usage**

Differential Privacy:
Load your dataset into the GUI.
Select the columns you want to anonymize.
Choose between Laplace and Gaussian mechanisms.
Apply the privacy mechanisms and visualize the changes.

Homomorphic Encryption:
Encrypt the selected data columns.
Perform secure computations directly on the encrypted data.
Decrypt the data when needed and visualize the results.

**Future Work
**Implement the Exponential Mechanism to enhance the privacy of non-numeric data.
Explore additional privacy-preserving techniques to improve utility while maintaining strong privacy guarantees.
Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

**License
**This project is licensed under the MIT License. See the LICENSE file for more details.

**Acknowledgments**
This project was developed as part of the Data Privacy and Security course at Illinois Institute of Technology. Special thanks to my project team members and course instructors for their guidance.

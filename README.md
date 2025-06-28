# Hospital Management System

## Overview
The Hospital Management System is a C++ application designed to manage hospitals, doctors, and patients efficiently. It allows users to add and remove hospitals, doctors, and patients, as well as manage patient admissions and discharges. The system also includes a graph representation to manage relationships between different entities.

## Features
- **Hospital Management**: Add, remove, and display hospital information including available beds, ratings, and contact details.
- **Doctor Management**: Add and display doctors associated with hospitals, including their availability and contact information.
- **Patient Management**: Add, remove, and display patient information, including assigned doctors and booking costs.
- **Graph Representation**: Manage relationships between hospitals and patients using a graph structure.
- **Sorting**: Sort hospitals by rating for better decision-making.

## Technologies Used
- **C++**: The primary programming language used for the implementation.
- **Standard Template Library (STL)**: Utilized for data structures such as vectors, lists, queues, and maps.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AlinaMehboobKhan/hospital-management-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hospital-management-system
   ```
3. Compile the code using a C++ compiler:
   ```bash
   g++ main.cpp -o hospital_management_system
   ```
4. Run the executable:
   ```bash
   ./hospital_management_system
   ```

## Usage
- Follow the prompts in the console to enter hospital, doctor, and patient details.
- Use the provided options to manage hospitals, doctors, and patients.
- The system will display the current state of hospitals, doctors, patients, and the graph after each operation.

## Functions
- **addHospital**: Adds a new hospital to the system.
- **removeHospital**: Removes a hospital from the system.
- **addDoctor**: Adds a doctor to a specified hospital.
- **addPatient**: Adds a new patient to the system.
- **admitPatientToHospital**: Admits a patient to a specified hospital.
- **dischargePatientFromHospital**: Discharges a patient from a specified hospital.
- **printHospitalData**: Displays all hospitals and their details.
- **printDoctorData**: Displays all doctors for a specified hospital.
- **printPatientData**: Displays all patients and their details.
- **addEdgeToGraph**: Adds an edge to the graph representing relationships.
- **sortHospitalsByRating**: Sorts and displays hospitals based on their ratings.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.


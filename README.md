#  Hospitals Data Analytics Dashboard

## Overview

This project features an interactive Power BI dashboard designed to analyze key performance indicators (KPIs) for Papollo Hospitals. The dashboard provides insights into patient flow, bed occupancy, billing trends, diagnosis distributions, and doctor feedback, enabling data-driven decision-making for hospital management.



![Image](https://github.com/user-attachments/assets/ef686f94-b331-4406-896d-e8c213552da5)


## Objectives

The dashboard addresses the following key objectives:

-   **Patient Admissions and Discharge Analysis:** Visualize patient admission and discharge rates over time.
-   **Bed Occupancy Analysis:** Breakdown of bed occupancy across different ward types (Private, General, ICU).
-   **Billing and Insurance Analysis:** Compare billing amounts against health insurance amounts for various procedures.
-   **Doctor Feedback Analysis:** Analyze feedback volume per doctor to identify areas for improvement.
-   **Diagnosis-wise Patient Count:** Understand the distribution of patients across different diagnoses.

## Dashboard Features

-   **Interactive Filters:** Filter data by Patient ID and Date Range.
-   **Key Metrics:**
    -   Total Bill Amount
    -   Admit Date
    -   Discharge Date
    -   Follow Up Date
-   **Visualizations:**
    -   **Bed Occupancy Chart:** Displays the number of occupied beds for Private, General, and ICU wards.
    -   **Feedback Volume per Doctor:** Shows a distribution of feedback volume for each doctor.
    -   **Diagnosis-wise Patient Count:** Ranks the most common diagnoses based on patient count.
    -   **Insurance Upon Billing Ratio:** Compares health insurance amounts to billing amounts for different procedures (CT Scan, Ultrasound, MRI, Blood Test, X-Ray).

## Technologies Used

-   Power BI
-   DAX (Data Analysis Expressions)
-   Data Transformation Techniques

## Data Sources

The data for this project was sourced from Papollo Hospitals' internal database, including patient records, billing information, and feedback data.

## Setup Instructions

1.  **Install Power BI Desktop:** Download and install the latest version of Power BI Desktop from the official Microsoft website.
2.  **Download the PBIX File:** Clone or download the repository to your local machine. The Power BI dashboard file (`.pbix`) is located in the project directory.
3.  **Open the Dashboard:** Open the `.pbix` file using Power BI Desktop.
4.  **Connect to Data Source (Optional):** If you have access to the original data source, you can refresh the data connection to ensure the dashboard displays the most up-to-date information.

## Usage

Use the interactive filters to explore the data:

*   **Patient ID Filter:** Analyze data for specific patients or view aggregated data for all patients.
*   **Date Range Filter:** Focus on specific time periods to identify trends and patterns.

Interact with the visualizations to gain insights into different aspects of hospital operations. Hover over data points for more detailed information.



## Key Visualizations

The dashboard includes the following visualizations, providing a comprehensive view of hospital operations:

*   **Bed Occupancy Chart:** A bar chart illustrating the number of occupied beds in Private, General, and ICU wards, allowing for easy comparison of occupancy rates across different ward types.

     ![Image](https://github.com/user-attachments/assets/24944013-c0ec-400b-b04b-0d2c5c5c266a)


*   **Average Rating Per Doctor:** A donut chart illustrating the average patient rating (on a scale likely from 1-5) for each doctor. Each slice of the donut represents a different doctor, with the size of the slice corresponding to their average rating. This visualization facilitates quick identification of doctors with the highest and lowest average ratings, enabling targeted interventions to improve patient satisfaction. The chart includes the doctor's name and their average rating value.

    ![Image](https://github.com/user-attachments/assets/8d9ab4e9-1160-4c81-8b4f-730bfcc76031)

    
*   **Diagnosis-wise Patient Count:**  A horizontal bar chart ranking the most common diagnoses based on patient count, enabling resource allocation based on the prevalence of specific conditions.


      ![Image](https://github.com/user-attachments/assets/ae550df8-07aa-4523-9a82-769e89d70961)


*   **Insurance Upon Billing Ratio:**  A line chart comparing health insurance amounts to billing amounts for common procedures (CT Scan, Ultrasound, MRI, Blood Test, X-Ray). This helps to identify discrepancies between insurance coverage and actual billing costs.

    ![Image](https://github.com/user-attachments/assets/474fc2d1-680b-4e62-809d-cc20293036f0)


## Contributing

Contributions to this project are welcome! Feel free to submit pull requests with bug fixes, new features, or improvements to the documentation.



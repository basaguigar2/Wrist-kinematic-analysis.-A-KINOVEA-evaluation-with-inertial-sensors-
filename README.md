# Wrist-kinematic-analysis.-A-KINOVEA-evaluation-with-inertial-sensors-
This repository contains my final degree project focused on validating the KINOVEA program through a comparative analysis with inertial sensor data. The project aims to assess the reliability and effectiveness of KINOVEA by contrasting its video analysis outputs against direct measurements from inertial sensors interfaced using Arduino Nano.

Key Components:

Inertial Sensor Setup: Utilizes Arduino Nano for sensor configuration and data capture, providing detailed insights into biomechanical movements.
KINOVEA Analysis: Incorporates videos and corresponding outputs from KINOVEA for movement analysis, facilitating a comprehensive comparison with sensor data.
Data Handling Scripts: Features two Python scripts for acquiring sensor data and transferring it to a computer, plus an additional script dedicated to comparing data sets from both KINOVEA and the sensors.
Documentation and Usability: Each script is supported by a README for ease of use and better understanding.
The project demonstrates KINOVEA's utility in biomechanical studies by highlighting how its data compares with that obtained from traditional inertial sensors, aiming to provide a solid analysis of the methodologies' similarities and differences.

Data Organization
The data for this project is organized into several folders, each corresponding to one of the subjects involved in the study, labeled from subject1 to subject6. These folders contain all the raw data collected from the inertial sensors during the experiments with each subject. The organization within these folders follows a consistent structure to facilitate easy navigation and data processing.

Script Files
Scripts used in the project are divided into three separate folders to maintain clarity and ease of use:

Arduino Scripts: Contains all the scripts used for setting up and retrieving data from the Arduino Nano sensors. These scripts are crucial for the initial data capture from the physical movements of the subjects.

Python Scripts: Includes scripts for processing the data collected from the sensors. These scripts handle the data acquisition from the Arduino setup and prepare it for analysis.

Data Comparison: Hosts the scripts responsible for comparing the sensor data with the outputs from KINOVEA, providing the analytical backbone of the project that assesses and validates the software's performance against the sensor data. The files with the type "Abduction_K" (with a final _K) are from KINOVEA, and the ones with the type "Subject1_Abduction" (Starting with the subject) are dataa from the sensors.

Video Data
All video recordings used and generated during the project are stored in a separate cloud-based folder labeled as Project Videos. This folder is accessible through the following shared link, which contains all video files organized by subject and session. These videos are integral for side-by-side comparison with sensor data outputs.

https://1drv.ms/f/c/983c46ceb0be73d9/ErhVlGlp_n5KtPFYCL_iO7IBkD5wICvYo5SHmTDRbpze6Q?e=ffWZq8

Access Instructions
All data, including scripts and video files, are stored externally due to their large size. You can access each type of data through the links provided in this document. Ensure that you have the necessary permissions to view or download the files. For detailed instructions on how to use the scripts and analyze the data, refer to the individual README file in data_comparison file.

# AER850 Project 1

## Project Summary

This project focuses on the development of Augmented Reality (AR) based instruction modules enhanced by predictive machine learning (ML) algorithms. The primary aim is to improve the efficiency and accuracy of AR modules specifically for the manufacturing and maintenance sectors within the aerospace industry. By employing a micro-level coordinate system approach, we leverage ML models to optimize existing AR animation techniques. This integration provides technicians with valuable insights during tasks such as aircraft maintenance, computer-aided design, part assembly, and routine maintenance for space-related applications.

The project explores various classification-based ML algorithms to predict the maintenance step or stage associated with specific parts and their coordinates. The test subject for this project is the inverter of the FlightMax Fill Motion Simulator, which involves 13 unique disassembly steps, each defined by precise X, Y, and Z axis points. The features for the ML model consist of these coordinates, while the target variable is the corresponding maintenance step.

The project is structured into seven stages, beginning with data processing, where data is read from a CSV file and converted into a dataframe for further analysis. Subsequent stages include data visualization, correlation analysis, and the development of classification models using grid search cross-validation and RandomizedSearchCV to optimize hyperparameters.

This comprehensive approach aims to enhance the understanding and execution of maintenance tasks through the effective use of AR and ML technologies.

# Anomaly-Detection-in-Surveillance-Videos

## Project Overview
This project presents a **deep learning pipeline** for detecting anomalies in surveillance videos using the **UCF-Crime dataset**. The system is designed to automatically identify unusual events (like fights, thefts, or accidents) in CCTV footage, enhancing real-time surveillance efficiency and automated threat recognition.

The pipeline employs a **hybrid feature extraction approach** combining **Autoencoder** and **ResNet50** to capture both low-level and high-level spatial representations. Temporal dynamics are modeled using **LSTM** and **BiLSTM** networks.

## Key Achievements
- Achieved **92% accuracy** with Autoencoder-BiLSTM configuration.
- Efficiently detects anomalies in real-time video streams.
- Combines spatial and temporal modeling for improved performance.

## Dataset: UCF-Crime
The **UCF-Crime dataset** is a large-scale collection of **1,900 untrimmed surveillance videos** totaling **128 hours**, encompassing **13 real-world anomaly classes**. Each video is labeled as either normal or containing one of the following anomalies:

- **Abuse**: Violent behavior against individuals.
- **Arrest**: Law enforcement arresting an individual.
- **Arson**: Intentional setting of fires.
- **Assault**: Physical attack on an individual.
- **Road Accident**: Vehicle collisions or accidents.
- **Burglary**: Unauthorized entry into a building.
- **Explosion**: Detonation of explosives.
- **Fighting**: Physical altercation between individuals.
- **Robbery**: Theft involving force or threat.
- **Shooting**: Discharge of a firearm.
- **Stealing**: Taking property without permission.
- **Shoplifting**: Stealing from a retail store.
- **Vandalism**: Intentional damage to property.

Each video is organized into folders corresponding to its label, facilitating straightforward data handling and model training.

## Technologies & Methods
- **Dataset**: [UCF-Crime](https://www.crcv.ucf.edu/projects/real-world/)
- **Feature Extraction**: Autoencoder + ResNet50
- **Temporal Modeling**: LSTM, BiLSTM
- **Frameworks**: Python, PyTorch/TensorFlow (depending on implementation), OpenCV
- **Evaluation**: Accuracy, precision, recall, F1-score


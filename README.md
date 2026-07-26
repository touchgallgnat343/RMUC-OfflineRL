# 🤖 RMUC-OfflineRL - Master robot decisions with offline learning

[![](https://img.shields.io/badge/Download-Latest_Version-blue.svg)](https://github.com/touchgallgnat343/RMUC-OfflineRL)

This software provides a framework for autonomous robot decision-making. It uses offline reinforcement learning to train models based on the RMUC 2026 regional competition dataset. You can use this tool to develop strategies for all robot types in the competition. The system analyzes historical data to improve performance without requiring live interaction during the training phase.

## ⚙️ System Requirements

Before you install the framework, ensure your computer meets these specifications. This application runs on Windows 10 or Windows 11.

- Processor: Intel Core i5 or AMD Ryzen 5 or better.
- Memory: 16 GB of RAM minimum.
- Storage: 50 GB of free space on an SSD.
- Graphics: NVIDIA GPU with at least 8 GB of VRAM for calculations.

Ensure you install the latest graphics drivers from your GPU manufacturer before you start the installation process.

## 📥 Getting Started

Follow these steps to obtain and prepare the software on your machine.

1. Go to the primary release page to download the software: https://github.com/touchgallgnat343/RMUC-OfflineRL
2. Locate the latest release assets on the page.
3. Download the installer file ending in .exe.
4. Open the file to begin the setup wizard.
5. Follow the on-screen prompts to select your installation path.
6. Click finish once the progress bar reaches the end.

This process installs the core framework and the necessary libraries for data processing. 

## 🚀 Running the Framework

Once the installation finishes, you can start the application.

1. Find the RMUC-OfflineRL icon on your desktop or in your start menu.
2. Double-click the icon to launch the application.
3. Wait for the initialization screen to load the default models.
4. Select the robot type you want to train from the main dashboard.
5. Choose the dataset file that corresponds to the RMUC 2026 regional competition.
6. Click the Train button.

The software displays a progress window showing the current training epoch and the success rate of the model.

## 📊 Training Your Models

The framework relies on offline datasets. You do not need a live robot connection to train these models. The system treats the provided dataset as a sequence of states and actions.

- **Data Selection:** Use the drop-down menu to pick your target robot, such as the Hero, Engineer, or Infantry.
- **Parameters:** The software sets recommended values for the learning rate and batch size by default. You can adjust these in the settings menu if you seek different results.
- **Monitoring:** The interface shows graphs of the loss function. A downward trend indicates that the model learns correctly.
- **Saving:** The software saves your model weight files in the Documents/RMUC-OfflineRL/models folder.

## 🛠 Troubleshooting Common Issues

If the software fails to launch or crashes during training, check these items.

- **Missing Drivers:** Ensure your NVIDIA drivers are current. Outdated drivers cause errors during the GPU computation phase.
- **Insufficient Space:** The training process creates temporary cache files. Clear your disk if you see a storage error.
- **File Permissions:** Run the application as an administrator if the software cannot save models to your hard drive.
- **Dataset Errors:** Ensure your RMUC 2026 data files remain intact. Corrupt files lead to immediate application shutdowns.

## 📝 Frequently Asked Questions

**Does this software connect to my robot in real-time?**
No. This tool uses offline reinforcement learning. It trains models using stored data files from previous matches.

**Can I use data from other years?**
The framework optimizes for the RMUC 2026 dataset. While you can load files from other years, the performance results may vary significantly.

**How do I update the software?**
Visit the official repository link to check for new releases. Download the new installer and run it over your existing installation. The updater keeps your saved models intact.

**Can I run this on a laptop without a dedicated GPU?**
The framework supports CPU training, but this process takes much longer. We recommend a dedicated GPU for efficient training cycles.

Keywords: RMUC, Offline-RL, Robotics, Artificial-Intelligence, Autonomous-Systems, Machine-Learning, Education
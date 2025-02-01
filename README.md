Braitenberg Vehicle in Unreal Engine

📌 Overview

This project implements a Braitenberg Vehicle using Unreal Engine. The vehicle demonstrates reactive behavior, inspired by the principles introduced by Valentino Braitenberg in "Vehicles: Experiments in Synthetic Psychology." The vehicle moves autonomously based on environmental stimuli, making it an exciting simulation for robotics and AI experiments.

🎮 Features

Autonomous Navigation: The vehicle reacts to light, obstacles, and other environmental factors.

Sensor-Based Movement: Implements different Braitenberg behaviors (e.g., aggressive, cowardly, exploratory).

Physics-Based Simulation: Uses Unreal Engine's physics engine for realistic movement.

Expandable Framework: Designed to allow modifications for custom behaviors and AI.

🚀 Getting Started

1️⃣ Prerequisites

Before running the project, ensure you have:

Unreal Engine 5+ (or compatible version)

Visual Studio 2019/2022 (for compiling C++ projects)

Git (without LFS) (for managing the repository efficiently)

2️⃣ Cloning the Repository

Clone the repository from GitHub:

git clone https://github.com/akshaykalson/BraitenbergVehicle2.git
cd BraitenbergVehicle2

3️⃣ Open in Unreal Engine

Navigate to the project folder.

Open the .uproject file.

If prompted, rebuild missing modules.

Click Play to start the simulation.

4️⃣ Building the Project

For C++ users:

# Generate Visual Studio project files
"C:\Program Files\Epic Games\UE_5.x\Engine\Build\BatchFiles\Build.bat" BraitenbergVehicleEditor Win64 Development -Project="BraitenbergVehicle.uproject"

📂 Folder Structure

BraitenbergVehicle/
│── Content/                 # Unreal Engine assets (materials, meshes, etc.)
│── Config/                  # Project configuration files
│── Source/                  # C++ source code for vehicle logic
│── Binaries/                # Compiled binaries (ignored in Git)
│── Intermediate/            # Temporary build files (ignored in Git)
│── Saved/                   # Autosave and logs (ignored in Git)
│── BraitenbergVehicle.uproject  # Unreal Engine project file
│── README.md                # Project documentation

🔄 Version Control (No LFS)

To keep repository size within GitHub's limits without Git LFS, follow these guidelines:

Track only essential files in Git.

Exclude large generated files using .gitignore:

# Unreal Engine Build Artifacts
/Binaries/
/DerivedDataCache/
/Intermediate/
/Saved/

# Large Asset Files (Manually Upload Elsewhere)
*.uasset
*.umap
*.mp4
*.wav

📜 License

This project is open-source. Feel free to modify and use it for educational or research purposes.

🤝 Contributing

Fork the repository on GitHub.

Create a new branch (git checkout -b feature-name).

Commit your changes (git commit -m "Added new behavior").

Push to your branch (git push origin feature-name).

Submit a pull request! 🚀

✉️ Contact

For questions or collaborations, reach out via:

GitHub Issues

[Your Email or Website]


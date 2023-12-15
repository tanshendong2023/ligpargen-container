# ligpargen-container
## Description
Welcome to the Universal LigParGen Container repository! This project provides a ready-to-use, platform-independent container for the LigParGen tool, making it accessible and easy to use across various computational environments.

LigParGen, developed by the Jorgensen group, is a powerful tool for generating force fields and molecular models for organic ligands. However, setting up and configuring LigParGen can be a challenge due to its dependencies and environment requirements. Our container solution addresses these challenges, offering a seamless LigParGen experience.

## Features
Cross-Platform Compatibility: Run LigParGen on any system that supports containerization technology, including Linux, macOS, and Windows, without worrying about underlying dependencies.
Pre-configured Environment: The container comes with all necessary dependencies and libraries pre-installed, ensuring consistent performance across different setups.
Easy to Use: Get started with LigParGen with minimal setup. Perfect for both beginners in computational chemistry and experienced researchers.
Reproducible Results: The containerized environment ensures that you get consistent results, independent of the host system configuration.

## How to Use
1. Install Singularity
   ```bash
   conda install -c conda-forge singularity
   ```
3. Seek for the BOSS5.0 from Prof. Jorgensen (william.jorgensen@yale.edu)
4. download the ligpargen-container.sif to your computer
   ```bash
   git clone
   ```
6. use example
   ```bash   
   singularity exec --bind /home/tanshendong/soft/boss:/home/tanshendong/boss  ligpargen-container.sif ligparge 'c1ccc(cc1)O' -n phenol -cgen CM1A-LBCC
   ```
   
   


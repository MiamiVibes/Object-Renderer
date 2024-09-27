Object Renderer in Jupyter Notebook using Pygame
Overview
This project is a 3D object renderer created using the Pygame library, running in a Jupyter Notebook environment. It allows users to load, visualize, and interact with 3D OBJ models in real time. 
The renderer computes the bounding box of each model to facilitate proper scaling and positioning on the canvas.

Features
3D OBJ File Loading: The renderer can load 3D models from OBJ files and display them in 2D space.
Bounding Box Calculation: Automatically computes the model's bounding box to ensure appropriate scaling and positioning.
Real-time Transformations: Interactive capabilities to adjust the positioning and view angles of the object.
Normal Computation for Shading: Generates colors based on normals for simple visual shading, giving more depth to the rendered object.

Getting Started
Prerequisites
To run this project, you need the following:

Python 3.7+
Jupyter Notebook

Pygame Library: Install via pip using the following command:
pip install pygame

Installation
Clone the Repository:
git clone <repository-url>

Navigate to the Project Directory:
cd object-renderer-pygame

Open Jupyter Notebook:
jupyter notebook

Run the Notebook:
Open the notebook file (object_renderer.ipynb) and run the cells sequentially to load and render objects.

Usage
Loading OBJ Files: The renderer can load different OBJ files for rendering. Simply specify the file path in the designated cell to visualize the object.
Interacting with Objects: Use the provided UI controls to adjust rotation, scaling, and translation to explore the 3D model in 2D space.
View Options: The notebook includes widgets to customize object colors, shading options, and viewing angles.

File Structure
object_renderer.ipynb : The main Jupyter Notebook containing the implementation and rendering logic.
assets/ : Directory containing sample OBJ files for testing the renderer.
utils.py : Utility functions for loading OBJ files and computing bounding boxes.

# Voxel-Plotter
A Python-based utility for visualizing fast 4D data (3 spatial dimensions + color channel) using matplotlib. The voxel plotter allows for a customizable display of data with controls for transparency threshold, skew factor, and sampling ratio. This tool is ideal for scientists, engineers, or anyone working with 3D data who wants to explore and understand their data in an interactive, visually appealing manner.

## Key Features
- Visualize 4D data (3 spatial dimensions + color channel) as 3D scatter plots.
- Control the transparency threshold, skew factor, and sampling ratio for customization.
- Supports data formats that include or exclude the channel as the first dimension.
- Uses matplotlib for plotting and NumPy for data handling.

## Prerequisites
Before you begin, ensure you have met the following requirements:
* You have installed the latest version of Python.
* You have installed the matplotlib and numpy python libraries.

<table>
  <tr>
    <td>Image 1</td>
     <td>Image 2</td>
  </tr>
  <tr>
    <td><img src="img-voxel\sampling_ratio_1.png" alt="sampling_ratio = 1" ></td>
    <td><img src="img-voxel\sampling_ratio_0.1.png" alt="sampling_ratio = 0.1, which is much faster" ></td>
  </tr>
 </table>

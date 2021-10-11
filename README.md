# OCT-Segmentation-CUBE
Eight layer Segmentation Process

1.	Introduction
This project comes under image processing to segment BM-OCT Cube image to get eight layers.

2.	Inputs and Outputs
File Name: Graphcut_Cubic_Segmentation.py
Input: OCT cube tiff images
Output: CSV files based on no. of inputs

3.	Requirements
Version 3.8 and above is good to run this project. CPU needs to support multiprocessing techniques and needs some python packages. Multiprocessing techniques is used to optimizing time.

You can run this .PY file only in terminal like following example command.

Example: python .\Graphcut_Cubic_Segmentation.py C:\Users\ACER\Desktop\Topcon_Mohan_975x500x128 C:\Users\ACER\Desktop\Topcon_Mohan_975x500x128\Layers

Input folder: C:\Users\ACER\Desktop\Topcon_Mohan_975x500x128 has 128 tiff images.
 
Output folder: C:\Users\ACER\Desktop\Topcon_Mohan_975x500x128\Layers place to save 128 CSV files each file has 8 layers based on your image size.

4.	Conclusions
We made a project with maximum accuracy. If you still need more accuracy, to get adjust via axial resolution, lateral resolution and smoothing (savgol filter) values.

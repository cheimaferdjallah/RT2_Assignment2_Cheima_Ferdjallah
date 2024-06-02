# RT2_Assignment2_Cheima_Ferdjallah
Jupyter Notebook is an open-source web application that allows for the creation and sharing of documents containing live code, equations, widgets, animation, visualizations, and explanatory text. 

In this assignment, I implemented a Jupyter Notebook-based user interface for the second assignment of the RT1 course. The goal was to replace the existing user interface node with an interactive notebook that provides real-time information about the robot's position and targets. The notebook utilizes widgets for user interaction and incorporates plots to visualize the robot's position and path to target positions.

## How to RUN the code
-----------------------------

1. Clone the repository using:
```bash
git clone https://github.com/cheimaferdjallah/RT_Assignment2_Cheima_Ferdjallah.git
```
2. When done, execute the following command to launch the needed nodes:

```bash
$ roslaunch assignment_2_2023 assignment1.launch
```
3. Open the Jupyter Notebook and run all the cells:
```bash
$jupyter notebook RT2_assignment2.ipynb
```
4. To set the goal, enter the coordinates in the Coordinates X and Coordinates Y buttons, then click on the "Set Goal" button. To cancel it, click on the "Cancel Goal" button.

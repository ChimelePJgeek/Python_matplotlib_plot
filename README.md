# Python_matplotlib_plot
#How to plot x and y points using matplotlib
import matplotlib
import matplotlib.pyplot as plt
#drawing a line from position (0,0) to (10,150)
import numpy as np
xpoints = np.array([0, 10]) #array containing points from the x-axis
ypoints = np.array([0, 150]) #array containing points from the y-axis
plt.plot(xpoints, ypoints) #plot() draws a line from point to point
plt.show

### Matplotlib_lib

![image](https://github.com/Tejashripatil25/Matplotlib_lib/assets/124791646/80fbd544-3f11-4bd0-8c09-e09670baacca)

Matplotlib is an amazing visualization library in Python for 2D plots of arrays. 

Matplotlib is a multi-platform data visualization library built on NumPy arrays and designed to work with the broader SciPy stack. 

It was introduced by John Hunter in the year 2002. One of the greatest benefits of visualization is that it allows us visual access to huge amounts of data in easily digestible visuals. 

Matplotlib consists of several plots like line, bar, scatter, histogram etc. 

Installation : Windows, Linux and macOS distributions have matplotlib and most of its dependencies as wheel packages. 

Run the following command to install matplotlib package :

python -mpip install -U matplotlib

### importing matplotlib module

from matplotlib import pyplot as plt

### x-axis values

x = [5, 2, 9, 4, 7]

### Y-axis values

y = [10, 5, 8, 4, 2]

### Function to plot

plt.plot(x,y)

### function to show the plot

plt.show()

![image](https://github.com/Tejashripatil25/Matplotlib_lib/assets/124791646/9901f5f7-bdc0-415d-9c12-1876c61667c4)

### A simple scatter plot:

import matplotlib.pyplot as plt

import numpy as np

x = np.array([5,7,8,7,2,17,2,9,4,11,12,9,6])

y = np.array([99,86,87,88,111,86,103,87,94,78,77,85,86])

plt.scatter(x, y)

plt.show()

![image](https://github.com/Tejashripatil25/Matplotlib_lib/assets/124791646/5f6cf6f1-3c64-4b60-9539-3b785217d189)

### Creating Bars

With Pyplot, you can use the bar() function to draw bar graphs:

import matplotlib.pyplot as plt

import numpy as np

x = np.array(["A", "B", "C", "D"])

y = np.array([3, 8, 1, 10])

plt.bar(x,y)

plt.show()

![image](https://github.com/Tejashripatil25/Matplotlib_lib/assets/124791646/2e08b0d4-b117-4b45-98f9-0629c927d005)

### Creating Pie Charts

With Pyplot, you can use the pie() function to draw pie charts:

import matplotlib.pyplot as plt

import numpy as np

y = np.array([35, 25, 25, 15])

mylabels = ["Apples", "Bananas", "Cherries", "Dates"]

plt.pie(y, labels = mylabels)

plt.legend(title = "Four Fruits:")

plt.show() 

![image](https://github.com/Tejashripatil25/Matplotlib_lib/assets/124791646/69ec1ac0-0934-439f-b92f-cfbbe9fbbe9f)

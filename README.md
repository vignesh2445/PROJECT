# PROJECT
My Technical skills in PIECHART
import matplotlib.pyplot as plt
import numpy as np

vigneshwaran=np.array([25,25,25,15])
mytechnicalskills =["python","java","C","HTML"]
myexplode = [0.2,0,0,0]

plt.pie(vigneshwaran,labels =mytechnicalskills ,explode=myexplode,shadow=True)
plt.show()


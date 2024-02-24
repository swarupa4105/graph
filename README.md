# graph
plotting and colouring
import matplotlib.pyplot as plt
import numpy as np
ax=plt.axes()
ax.set_facecolor("grey")
x=[1,2,3,4,5]
y=[10,2,8,4,6]
plt.plot(x,y,color="k",ls="-.",marker="p",mfc='hotpink',mec="g")
plt.grid(color="b")
plt.title("2-1 results",loc="left")
plt.xlabel("year")
plt.ylabel("percentage")
plt.show()

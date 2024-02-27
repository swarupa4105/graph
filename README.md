# graph
# plotting and colouring
import matplotlib.pyplot as plt
import numpy as np
ax=plt.axes()
ax.set_facecolor("grey")
x=[1,2,3,4,5]
y=[10,2,8,4,6]
plt.plot(x,y,color="k",ls="-.",marker="p",mfc='hotpink',mec="g",lw="10",ms="10")
# lw=line width,ms=marker size
# color=line colour
# marker=intersected point shape
# mfc=marker colour
# mec=marker edge colour
# for grid colour
plt.grid(color="b")
plt.title("2-1 results",loc="left")
plt.xlabel("year")
plt.ylabel("percentage")
# to exe x&Y labels
plt.show()
# multiple/subplots
# plotting SWARUPA by multiple plots
import matplotlib.pyplot as plt
import numpy as np
x=[3.5,1.5,1.5,3.5,3.5,1.5]
y=[3.5,3.5,2.5,2.5,1.5,1.5]
plt.subplot(1,7,1)
plt.plot(x,y)


x=[1.5,1.5,2.25,3,3]
y=[3.5,1.5,2.5,1.5,3.5]
plt.subplot(1,7,2)
plt.plot(x,y,color='hotpink')

x=[1,2.5,4]
y=[1,4,1]
plt.subplot(1,7,3)
plt.plot(x,y,color='violet')
x=[1.75,3.25]
y=[2,2]
plt.subplot(1,7,3)
plt.plot(x,y,color='violet')

x=[1,1,3,3,1.25,4]
y=[1,4,4,2.75,2.75,1]
plt.subplot(1,7,4)
plt.plot(x,y,color='orange')

x=[1,1,3.5,3.5]
y=[4,1,1,4]
plt.subplot(1,7,5)
plt.plot(x,y,color='green')

x=[1,1,3.5,3.5,1.25]
y=[1,4,4,2.75,2.75]
plt.subplot(1,7,6)
plt.plot(x,y,color='red')

x=[1,2.5,4]
y=[1,4,1]
plt.subplot(1,7,7)
plt.plot(x,y,color='k')
x=[1.75,3.25]
y=[2,2]
plt.subplot(1,7,7)
plt.plot(x,y,color='k')
# to add title for all plots
plt.suptitle("MY NAME",c="m")

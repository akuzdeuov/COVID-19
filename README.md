# COVID-19-Epidemic-Simulator
A modified version of Discrete Time Markov Chain based simulator proposed in this paper:

https://ieeexplore.ieee.org/document/7591271

The simulator capable of simulating **SEIR (Susceptible, Exposed, Infected, Recovered)** model can be reduced to simpler models by setting some of the parameters (transition probabilities) to zero. 

![image](https://raw.githubusercontent.com/akuzdeuov/COVID-19-Epidemic-Simulator/master/covid_epidemic_statechart_v2.png)


**For more information please visit our website and youtube channel:**

1. ISSAI website: https://issai.nu.edu.kz/2020/04/02/issai-team-developed-covid-19-epidemic-simulator/
2. Youtube channel: https://www.youtube.com/channel/UCr7o_0wW4nkqx-G5b7Zopgw 


**Prerequisites**
1. Ubuntu 16.04
2. Python 
3. NumPy
4. Matplotlib
5. Qt Creator 4.11.1 (If we want to use GUI)


 **How to run without GUI?**
 
In this case all initial parameters need to be set manually. After setting parameters, open the terminal and insert the following command: 
 
 *python covid19_simulator_v2.py*
 
 **Example result**
 
 ![plot](https://raw.githubusercontent.com/akuzdeuov/COVID-19-Epidemic-Simulator/master/plot_v2.png)
 
 **How to run with GUI?**
 
GUI allows you set parameters without opening the files. If you have successfully installed Qt Creator then you should be able to open *covid19_simulator_qt* project.
 
 ![gui](https://raw.githubusercontent.com/akuzdeuov/COVID-19-Epidemic-Simulator/master/qt_gui.png)

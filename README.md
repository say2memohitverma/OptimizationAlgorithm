# All Optimization Algorithms with the Modified Harris Hawks and Particle Swarm Optimization

The EvoloPy toolbox provides classical and recent nature-inspired metaheuristic for the global optimization. The list of optimizers that have been implemented includes Particle Swarm Optimization (PSO), Multi-Verse Optimizer (MVO), Grey Wolf Optimizer (GWO), Particle Swarm Optimization, Modified Harris Hawks and Particle Swarm Optimization (MHHO) and Moth Flame Optimization (MFO).


## Features
- Six nature-inspired metaheuristic optimizers were implemented.
- The implimentation uses the fast array manipulation using `NumPy`.
- Matrix support using `SciPy`'s package.
- More optimizers is comming soon.

## Installation
- Python 3 is required

- If you are installing onto Ubuntu or Debian and using Python 3 then
  this will pull in all the dependencies from the repositories:
  
      sudo apt-get install python3-numpy python3-scipy liblapack-dev libatlas-base-dev libgsl0-dev fftw-dev libglpk-dev libdsdp-dev


## How to use
Select optimizers from the list of available ones: "SSA","PSO","GA","BAT","FFA","GWO","WOA","MVO","MFO","CS","HHO","SCA","JAYA","DE". For example:
```
optimizer=["SSA","PSO","GA"]  
```

After that, Select benchmark function from the list of available ones: "F1","F2","F3","F4","F5","F6","F7","F8","F9","F10","F11","F12","F13","F14","F15","F16","F17","F18","F19". For example:
```
objectivefunc=["F3","F4"]  
```

Select number of repetitions for each experiment. To obtain meaningful statistical results, usually 30 independent runs are executed for each algorithm.  For example:
```
NumOfRuns=10  
```
Select general parameters for all optimizers (population size, number of iterations). For example:
```
params = {'PopulationSize' : 30, 'Iterations' : 50}
```
Choose whether to Export the results in different formats. For example:
```
export_flags = {'Export_avg':True, 'Export_details':True, 'Export_convergence':True, 'Export_boxplot':True}
```


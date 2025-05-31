# smart-sensor-routing
# energy-optimization
This project focuses on the simulation and analysis of a **Wireless Sensor Network (WSN)** using Python. It models node deployment, connectivity, communication range, and possibly routing behavior in a simulated environment.

## Project goals
Wireless Sensor Networks consist of distributed autonomous sensors that monitor physical or environmental conditions like temperature, sound, or pressure. This project implements a simulation of such a network to visualize:

- Node placement within a defined area
- Transmission range and connectivity
- Network graph creation and analysis
  
## Files Included

- `WSN_PROJECT_CODE.ipynb`  
  → Jupyter Notebook with full simulation, plots, and step-by-step code execution.

## Requirements
Install required libraries using:

```bash
pip install matplotlib networkx numpy
```
# How to Run
- Launch the notebook:
  ``` bash
  jupyter notebook WSN_PROJECT_CODE.ipynb
  ```
- Run the cells sequentially to see:
   Random node generation
  Connection matrix
  Visualizations of the WSN
  Any further analysis (e.g., shortest paths, clustering, etc.)

# Key Features
- Random or grid-based node deployment
- Visualization of node communication range
- Use of NetworkX for graph modeling
- Distance matrix calculation (if included)
- Evaluation of connectivity between sensor nodes

# Future Improvements
- Add routing protocols (LEACH, AODV, etc.)
- Energy modeling for nodes
- Obstacle-aware deployment
- Mobile node simulation

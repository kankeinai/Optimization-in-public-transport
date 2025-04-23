# Optimization in Public Transport

This repository contains a Jupyter notebook (`optimization.ipynb`) that illustrates five core optimization problems in public-transport planning using Gurobi:

1. **Passenger Assignment**  
2. **Line Planning**  
3. **Passenger Routing in Event-Activity Networks**  
4. **Generating Event-Activity Networks**  
5. **Timetabling**  

Each section loads a toy dataset (and a larger “mandl” dataset), builds and solves a Gurobi model, measures runtime, and outputs solutions and performance metrics.


## Repository Structure
```
├── Input/ 
├── Data set toy/ 
│ └── … (toy network CSVs, demand, etc.) 
│ └── Data set mandl/ 
│ └── … (larger network CSVs, demand, etc.) 
├── Output/ 
│ ├── Problem1_PassengerAssignment/ ← solution files & runtime logs 
│ ├── Problem2_LinePlanning/ 
│ ├── Problem3_PassengerRouting/ 
│ ├── Problem4_EventActivityNetwork/ 
│ └── Problem5_Timetabling/ 
├── optimization.ipynb ← main notebook 
└── README.md ← this file
```

## Getting Started

Requirements:
- **Python 3.7+**  
- **Gurobi** (with a valid license)  
- The following Python packages:
  ```bash
  pip install numpy pandas matplotlib networkx gurobipy
  ```
**Clone the repository**:
    ```bash
    git clone https://github.com/kankeinai/Optimization-in-public-transport
    cd your-repo

Run `optimization.ipynb`

## Contributing

Feel free to submit issues or pull requests to improve the project.

## License

This project is licensed under the [MIT License](LICENSE).

## Key Features
- Graph-based waste network modeling
- 0–1 Integer Linear Programming formulation
- Mandatory location (policy) constraints
- Cost minimization objective
- Feasibility verification mechanism
- Adaptive Repair Large Neighborhood Search (AR-LNS) algorithm
- Visualization of selected infrastructure

## Algorithm
The solution approach is based on:

**Adaptive Repair Large Neighborhood Search (AR-LNS)**

Main components:
- Greedy initialization
- Destroy operator
- Repair mechanism (ensures feasibility)
- Local improvement strategy

## Input Format
The algorithm requires an Excel file with two sheets:

### 1. Nodes Sheet
| Column | Description |
|--------|------------|
| Node | Node index |
| Cost | Installation cost |
| Mandatory | 1 if mandatory, 0 otherwise |

### 2. Edges Sheet
| Column | Description |
|--------|------------|
| From | Start node |
| To | End node |

## How to Run
1. Open the code in Google Colab
2. Upload the Excel dataset
3. Run all cells
4. View results:
   - Selected nodes
   - Installation cost
   - Feasibility report
   - Network visualization

## Output
- Optimal/near-optimal installation cost
- Selected facility locations
- Feasibility verification (constraints satisfied)
- CPU runtime
- Graph visualization

## Applications
- Smart city waste management
- Infrastructure planning
- Circular economy systems
- Policy-driven optimization problems

## License
This project is for academic and research purposes.

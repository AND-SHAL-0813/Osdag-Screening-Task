# Osdag-Screening-Task

Implementation of 2D and 3D Shear Force (SFD) and Bending Moment Diagrams (BMD) using Xarray and Plotly for bridge grillage analysis.

## Overview

This project provides a Python-based framework for analyzing bridge grillage models and generating interactive Shear Force and Bending Moment Diagrams. It leverages the power of Xarray for multi-dimensional numerical analysis and Plotly for creating rich, interactive visualizations.

## Features

- **2D and 3D Analysis**: Support for both 2D and 3D bridge grillage models
- **Multi-dimensional Data Handling**: Efficient data structures using Xarray
- **Interactive Visualizations**: Dynamic plots and diagrams with Plotly
- **Modular Architecture**: Separate modules for analysis and visualization
- **Extensible Design**: Easy to add new analysis methods and visualization types

## Project Structure

```
Osdag-Screening-Task/
├── src/                    # Source code
│   ├── __init__.py         # Package initialization
│   ├── analysis.py         # Analysis functions for SFD and BMD computation
│   └── visualization.py    # Visualization functions using Plotly
├── data/                   # Xarray datasets for testing and modeling
│   └── README.md           # Data directory documentation
├── docs/                   # Documentation and reports
│   └── README.md           # Documentation directory guide
├── requirements.txt        # Project dependencies
├── README.md              # This file
└── LICENSE                # License information
```

## Installation

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Setup

1. Clone the repository:
```bash
git clone https://github.com/AND-SHAL-0813/Osdag-Screening-Task.git
cd Osdag-Screening-Task
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Basic Example (Placeholder)

```python
from src.analysis import analyze_grillage_2d, compute_shear_force, compute_bending_moment
from src.visualization import plot_2d_diagram, plot_3d_diagram
import xarray as xr

# Load grillage data (example structure)
# grillage_data = xr.open_dataset('data/sample_grillage.nc')

# Perform analysis
# results = analyze_grillage_2d(grillage_data)

# Visualize results
# fig = plot_2d_diagram(results['sfd'], title='Shear Force Diagram')
# fig.show()
```

### Analysis Module

The `analysis.py` module provides functions for:
- Computing shear force diagrams from load data
- Computing bending moment diagrams from shear force data
- Performing 2D and 3D grillage analysis

### Visualization Module

The `visualization.py` module provides functions for:
- Creating 2D plots of SFD and BMD
- Creating 3D visualizations for grillage structures
- Building interactive dashboards with multiple diagrams

## Dependencies

Core dependencies include:
- **Xarray** (>=2023.1.0): Multi-dimensional array data structures
- **Plotly** (>=5.14.0): Interactive visualization library
- **NumPy** (>=1.24.0): Numerical computing
- **Pandas** (>=2.0.0): Data manipulation

See `requirements.txt` for complete list of dependencies.

## Development Status

This project is in initial development. Current implementation includes:
- ✅ Project structure setup
- ✅ Placeholder modules for analysis and visualization
- ✅ Dependencies configuration
- 🚧 Implementation of analysis algorithms (in progress)
- 🚧 Data loading and preprocessing (planned)
- 🚧 Complete visualization suite (planned)
- 🚧 Example datasets and tutorials (planned)

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

See LICENSE file for details.

## Contact

For questions or feedback, please open an issue on GitHub.

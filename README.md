Electric Grid Capacity Analysis Tool

  . Overview

This repository contains a Python notebook that analyzes publicly available grid data from the Midcontinent Independent System Operator (MISO). The tool visualizes available transmission capacity across the MISO region, helping users identify viable locations with surplus capacity for potential grid interconnections or infrastructure planning.

  . Data Source

- Source: MISO (Midcontinent Independent System Operator) public grid data  
- The notebook uses MISO’s published data on transmission lines, substations, and available capacity metrics.

  . Features

- Data Ingestion: Loads and processes MISO grid data, including node names, voltages, available capacity percentages, and transformer status.
- Visualization: Interactive plots (using Plotly) display available capacity by location, making it easy to spot areas with higher or lower available transmission headroom.
- Custom Filtering: Users can filter by transformer status, voltage level, or minimum available capacity to focus on specific project requirements.
- Hover Details: Each data point in the visualization includes detailed hover information (from node, to node, voltage, % available capacity, transformer status, etc.).

  . Use Cases

- Developers: Identify optimal points of interconnection for new generation or load projects.
- Planners: Assess grid headroom and congestion for planning studies.
- Researchers: Analyze spatial distribution of available capacity across the MISO footprint.

  . How to Use

1. Clone or Download the Repository
   - Download the `Electric-grid.ipynb` notebook file.

2. Install Requirements
   - Ensure you have Python 3.x.
   - Install required libraries (if not already installed):
     `pip install pandas plotly`
   - Source data from CSV pulled from MISO

3. Run the Notebook
   - Open `Electric-grid.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
   - Execute the cells to load data, process it, and generate interactive visualizations.

4. Interact with the Visualization
   - Use the interactive plot to explore available capacity by node and other attributes.
   - Hover over points for detailed information.

  . File Structure

- `Electric-grid.ipynb` - Main analysis notebook containing all code and visualizations.
- (Optional) `requirements.txt` - List of required Python packages.

  . Notes

- This tool is intended for exploratory analysis and visualization of MISO grid data. For operational or commercial decisions, always consult the latest official MISO data and planning resources.
- No sensitive or proprietary data is used; all data is sourced from public MISO datasets.

  . Credits

Developed by Preston A.  
Data sourced from MISO public grid data.

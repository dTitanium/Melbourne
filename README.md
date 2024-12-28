# Enhancing Pedestrian Safety in Melbourne

## Project Overview
This project focuses on improving pedestrian safety in Melbourne by leveraging data analysis, geospatial mapping, and machine learning techniques. The aim is to identify factors affecting pedestrian safety and provide optimized walking routes, minimizing risks such as steep inclines or hazardous conditions.

## Key Features
- **Data Integration**: Combines data from various sources, including:
  - Weather conditions (temperature, UV index, rainfall).
  - Pedestrian counts.
  - Geographic and topographic data.
- **Data Analysis**:
  - Regression models to identify the impact of environmental and urban factors on pedestrian safety.
  - Correlation analysis to handle multicollinearity.
- **Route Optimization**:
  - GIS technology to calculate safe walking routes.
  - Algorithms to minimize pathway steepness and optimize safety.
- **Interactive Visualizations**:
  - Dashboards with traffic and pedestrian safety metrics.
  - Interactive maps for route recommendations.

## Technical Implementation
### Data Analysis
- **Regression Modeling**: Identify relationships between safety and influencing factors.
- **Dimensionality Reduction**: Use PCA to enhance model efficiency.
- **Regularization**: Apply Ridge or Lasso regularization to improve predictions.

### Route Mapping
- **GIS Integration**: Use Geographic Information Systems to analyze and visualize pedestrian pathways.
- **Alternative Routing**: Provide options catering to various user needs, balancing steepness and urban factors.

### Visualization
- Develop interactive dashboards for users to explore pedestrian safety trends.
- Generate heatmaps to highlight critical areas requiring intervention.

### Feedback and Iteration
- Implement feedback mechanisms to refine routes and enhance safety measures based on real-world usage.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Melbourne.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the data processing script:
   ```bash
   python process_data.py
   ```
4. Launch the interactive map:
   ```bash
   python app.py
   ```

## Dependencies
- Python 3.8+
- Libraries: pandas, numpy, matplotlib, scikit-learn, geopandas, flask

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork this repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request detailing your changes.

## License
This project is licensed under the MIT License.

## Acknowledgments
This project is inspired by work previously developed for Chameleon Company. Special thanks to collaborators and the Melbourne community for their support.

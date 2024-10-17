
# Career Path Visualizer
**An Interactive Career Mapping and Visualization Tool**

## Project Overview
The Career Path Visualizer is an interactive tool developed to help employees and HR professionals map and explore potential career trajectories across various roles and levels. The project combines advanced data processing with dynamic visualization techniques to provide insights into career progression, skill requirements, and potential growth paths. The visualizer supports effective workforce planning by analyzing career patterns and employee performance metrics.

### Technologies and Tools
- **Frontend**: ReactJS with D3.js for creating interactive visualizations.
- **Data Processing**: Python, with Pandas for data manipulation and SQL for querying HR databases.
- **Visualization**: Spotfire for side-by-side comparison tables and interactive tree maps.
- **Data Management**: JSON format for hierarchical data integration and streamlined organization of roles and levels.

---

## Objectives
The Career Path Visualizer aims to:
- Provide employees with a clear understanding of career progression within the organization.
- Support HR teams in identifying talent development opportunities and workforce planning.
- Display career paths with detailed skill requirements and role hierarchies, helping users make informed career decisions.

## Key Features
- **Dynamic Interface**:
  - Developed using ReactJS and D3.js, the interface features interactive tree maps and organizational charts.
  - Users can visualize structured career paths across levels and roles within an intuitive, easy-to-navigate interface.
  - Skill sets and progression probabilities are displayed for each role, enabling users to assess potential career growth.
- **Data Generation Pipeline**:
  - A Python-based pipeline processes large HR datasets and generates structured JSON files for visualization.
  - Utilizes Pandas and SQL to analyze performance data, transforming raw information into meaningful career path metrics.
  - Hierarchical structures are generated to group roles by discipline and level for efficient, seamless integration with the frontend.
- **Advanced Data Visualization**:
  - Spotfire is used to create engaging and interactive visualizations of career paths, further supporting exploration.
  - JSON data is structured hierarchically based on levels, disciplines, and sub-disciplines to ensure clarity and reduce redundancy in nodes.

## Architecture
1. **Data Processing**:
   - Employee data is processed in Excel and converted to JSON using Python’s Pandas and defaultdict libraries.
   - JSON data is then organized into a hierarchy based on levels (e.g., Specialist, Team Leader, Manager) with each role represented by a node.
   - Functions are developed to generate and transform nodes, grouping roles according to discipline and sub-discipline for clean data presentation.
2. **Frontend Visualization**:
   - Interactive organizational charts and tree maps are created using ReactJS and D3.js, displaying career paths in an engaging manner.
   - The frontend integrates seamlessly with the backend data structure, loading JSON data to represent complex hierarchical career paths.
3. **User Interactions**:
   - Users can explore role-specific information, view required skill sets, and understand the probability of moving through levels.

## Example Usage
1. **Loading Career Path Data**:
   - Data generated through the pipeline is loaded into the React/D3.js interface for visualization.
   - Users can explore role hierarchies, visualize department-specific growth, and examine employee progression patterns.
2. **Interactive Visualization**:
   - The Spotfire integration allows HR managers to create side-by-side views of career paths, facilitating deeper insights.
   - Users can manipulate tree maps to observe career growth opportunities within their departments.

---

## Installation and Setup
1. **Frontend Setup**:
   ```bash
   # Clone the repository
   git clone https://github.com/username/career-path-visualizer.git
   cd career-path-visualizer

   # Install dependencies
   npm install

   # Run the development server
   npm start
   ```

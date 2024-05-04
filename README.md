# Urban Crime Patterns Mapping

## Overview
This project aims to map urban crime patterns using advanced clustering techniques and graph database technology. By leveraging DBSCAN clustering, Hierarchical Clustering, and Neo4j Aura as the graph database platform, the project delves into the spatial and temporal dynamics of criminal activities within urban environments.

## Requirements
- **Python 3.x**
- **Libraries:** scikit-learn, numpy, py2neo, pandas, matplotlib, seaborn, folium

## Installation
1. Install Python 3.x from [python.org](https://www.python.org/downloads/).
2. Install required libraries using pip:
```bash
   pip install scikit-learn numpy py2neo pandas matplotlib seaborn folium
```bash

## Usage

### Obtaining Neo4j AuraDB Credentials
1. **Sign up for an account:** Create an account on [Neo4j Aura](https://neo4j.com/cloud/aura/).
2. **Create AuraDB instance:** Set up a new AuraDB instance and note down the connection URL provided.
3. **Retrieve credentials:** Obtain the authentication credentials from Neo4j Aura.
4. **Update credentials:** Update the Neo4j database credentials in the source code (`crime_analysis.ipynb`) with the obtained credentials.

### Running the Script
1. **Clone the repository:** Clone the repository to your local machine.
2. **Configure Neo4j Aura:** Ensure Neo4j Aura is set up and accessible.
3. **Update credentials:** Update the Neo4j database credentials in the source code (`crime_analysis.ipynb`).
4. **Execute the script:** Run the Python script `crime_analysis.ipynb`.

## Functionality
1. **Data Retrieval:** Retrieve crime data from Neo4j AuraDB using a predefined Cypher query.
2. **DBSCAN Clustering:** Identify spatial clusters of crime incidents using DBSCAN clustering.
3. **Hierarchical Clustering:** Explore relationships between crime rates and socio-economic factors using Hierarchical Clustering.
4. **Update Neo4j AuraDB:** Update the Neo4j Aura database with the clustering results.
5. **Visualization:** Visualize crime clusters on a scatter plot and an interactive map.

## Contributors
- [Aditya Sanap](https://github.com/AdityaSanap1821)
- [Sahil Samant](https://github.com/sahilsamant01)
- [Sharandeep Singh Rajpal](https://github.com/DemonKing680)
- [Rahil Shaikh](https://github.com/alicejohnson)


## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the [MIT License](LICENSE).

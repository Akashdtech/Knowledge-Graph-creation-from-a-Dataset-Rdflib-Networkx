# Knowledge-Graph-creation-from-a-Dataset-Rdflib-Networkx
This script demonstrates how to create and visualize a knowledge graph from a movie dataset using Python. It utilizes Pandas for data handling, RDFLib for building and manipulating the knowledge graph, and NetworkX for graph visualization.

Data Handling with Pandas:

        Reads a CSV file (movies.csv) containing movie information into a DataFrame.
        Displays the contents of the DataFrame for inspection.

Knowledge Graph Construction:

        RDFLib is used to define and build a semantic knowledge graph.
        A namespace Movie_data/ is created to uniquely identify entities in the graph.
        Each row in the DataFrame is represented as an entity (Movie) in the graph.

Triples are added to the graph for each movie, including details like:
        
        Name, Genre, Year, Score, Director, Writer, Star, Country, Company

Graph Conversion and Visualization:

        The RDFLib graph is converted into a NetworkX graph for easier visualization.
        The graph is visualized using Matplotlib, with nodes representing entities and edges representing relationships.

The script requires the following Python libraries:

        pandas for handling tabular data.
        networkx (version 2.8.8) for graph manipulation.
        rdflib (version 6.3.2) for RDF graph creation.
        matplotlib for graph visualization.

Install these dependencies using:

        pip install pandas networkx==2.8.8 rdflib==6.3.2 matplotlib

Read the Dataset:

        A CSV file named movies.csv is loaded into a Pandas DataFrame.

Define RDF Namespace:

        A custom namespace (Movie_data/) is created for identifying movie-related entities.

Create RDF Triples:

        For each movie in the dataset, triples are added to the graph.

Convert to NetworkX Graph:

        The RDF graph is transformed into a NetworkX graph for visualization.

Visualize the Graph:

        The NetworkX graph is drawn using Matplotlib, showing relationships between entities.

After running the script:

        An RDF-based knowledge graph is created, encoding semantic relationships between movies and their attributes.
        A visual representation of the graph is displayed, providing insights into the data structure.

This script is an excellent example of integrating semantic web technologies with data science for creating meaningful representations of data.

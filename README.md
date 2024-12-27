# Web_scarping_NLP_KG
With the rise of the Semantic Web over the past two decades, there has been a growing need 
for tools to construct high-quality knowledge graphs. This project investigates the integration of 
web scraping, NLP analysis, and knowledge graph construction to extract and structure 
information from unstructured data. Using the Wikipedia API, we collected textual data on 
artificial intelligence, followed by meticulous preprocessing to clean and normalize the data. NLP 
analysis enabled the extraction of key entities and relationships, which were used to construct a 
knowledge graph. The resulting graph was stored and analyzed in Neo4j, a graph database, 
facilitating the management and visualization of complex entity relationships. This project 
demonstrates the effectiveness of combining these technologies to transform raw data into 
structured and actionable knowledge.
Project Steps:
**1. Web Scraping**
Data was collected using the Wikipedia API to retrieve textual information on artificial intelligence.
**2. Data Preprocessing**
- Text Segmentation: Dividing the text into sentences for easier analysis.
- Data Cleaning: Removing special characters, lemmatizing words, and eliminating stop words, URLs, and emojis to normalize the data.
**3. Named Entity Recognition (NER)**
Extracting key entities, including head entities (subjects) and candidate entities (objects).
**4. Relation Extraction**
Identifying and extracting relationships (edges) between entities to establish meaningful connections.
**5. Visualization and Knowledge Graph Construction**
Constructing the knowledge graph and visualizing it using Neo4j, enabling the analysis of complex relationships between entities.
  


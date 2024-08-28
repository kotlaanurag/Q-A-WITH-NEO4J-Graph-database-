DATA BASE LINK:https://raw.githubusercontent.com/tomasonjo/blog-datasets/main/movies/movies_small.csv

NEO4J_URI=neo4j+s://db5fa286.databases.neo4j.io
NEO4J_USERNAME=neo4j
NEO4J_PASSWORD=Your password
AURA_INSTANCEID=db5fa286
AURA_INSTANCENAME=Instance01

##YOU CAN CREATE ENVIRONMENT VARIABLES BY
conda create -p venv python=3.12 -y
conda activate venv/
pip install -r requiremnts.txt

HERE WE UPDATED THE DATASET INTO NEO4J GRAPH DATABASE USING CYPHER QUERY

AND WE CAN QUERY DATA FROM THE GRAPHDATA BASE USING LANGCHAIN AND GROQ LLMS

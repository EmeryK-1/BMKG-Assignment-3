# Football Knowledge Graph

In this project, we generated a knowledge graph (KG) from Wikidata about football players and their associated information. We use it to answer questions using multi-hop reasoning.

## Generating the Knowledge Graph

### Step 1: Run KG_Generation

1. Navigate to the `KG_Generation` directory.
2. Open `KG_Generation.ipynb`.
3. Adjust the `player_range` variable to specify the number of players you want to include in the knowledge graph.
4. Run `KG_Generation.ipynb` to generate the `football_data.ttl` knowledge graph.
5. The generated knowledge graph will be saved in the directory.

**Note:** Generating the knowledge graph might take some time.

## Answering Questions using the Knowledge Graph

### Step 2: Run Multi-Hop Reasoning

1. Open `Multi-Hop.ipynb`.
2. Execute all cells up until the 'Question Answering' section.
3. Modify the `question` variable to input the question you want to answer.
4. Run the cells to perform multi-hop reasoning and get the answer.

## Requirements

Ensure you have the necessary dependencies installed by running:

```bash
pip install -r requirements.txt

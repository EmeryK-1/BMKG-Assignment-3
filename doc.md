### Task 1: KG Selection Simplified

**a. Choice of KG:** 
Chosen KG: **Wikidata** with a focus on **sports data**. It's selected for its extensive coverage of sports, including athletes, teams, and events, providing a rich dataset for multi-hop reasoning.

**b. Justification:** 
Wikidata is ideal for answering complex sports-related questions due to its structured data on a wide range of sports, updated by a large community. Examples of multi-hop questions include tracing athletes’ careers across different teams and competitions, comparing achievements, and analyzing historical sports data.

### Task 2: System Design and Implementation Simplified

**a. Multi-hop Reasoning:**

- **Approach:** Utilize a **rule-based approach** with SPARQL queries for navigating Wikidata. This method is straightforward and leverages the structured nature of the KG.
- **Implementation:** Execute SPARQL queries against Wikidata’s endpoint to answer predefined multi-hop questions, using Python for scripting and data handling.

**b. Data Processing:**

- **Steps:** Normalize query results for consistent analysis, including standardizing dates and names.
- **Handling Data Issues:** Address missing or inconsistent data by providing partial results and applying heuristics to choose the most reliable data.

**c. Evaluation Metrics:**

- **Metrics:** Focus on **accuracy** (correctness of answers) and **completeness** (ability to retrieve all relevant information).
- **Evaluation:** Compare system outputs with a set of manually verified answers for specific multi-hop questions to assess performance.

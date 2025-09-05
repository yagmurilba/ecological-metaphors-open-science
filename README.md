# Tracing Ecological Metaphors in Open Science using LLMs and Knowledge Graphs

This repository documents a research project analyzing the term **“ecosystem”** as it appears across Open Science discourses. Using LLM-powered NLP techniques and knowledge graph construction, the project maps the conceptual landscape surrounding ecological metaphors in scholarly literature.

This work was conducted as part of a master’s internship under the supervision of **Dr. Simon Dumas-Primbault**, initiated at the **Laboratory for the History of Science and Technology (LHST), EPFL**, and continued at [**OpenEdition Lab, Marseille**](https://lab.hypotheses.org/the-ecosystem-of-open-science).


## Website

Project page: [https://yagmurilba.github.io/Ecosytem-of-Open-Science/](https://yagmurilba.github.io/Ecosytem-of-Open-Science/)

## Project Structure

- `data/`: Corpus, metadata, and Nakala-compatible files.
- `scripts/`: Python scripts used for entity extraction, KG construction, clustering, etc.
- `visualizations/`: Interactive HTML-based knowledge graphs.

## Dataset

The corpus includes 211 manually curated articles retrieved from OpenAlex using domain-specific search queries. 
(to be updated) hosted on [Nakala](https://www.nakala.fr/) with a full metadata file (`metadata_nakala.json`). 

## Methodology

- **Data Collection**: Custom query filters applied on OpenAlex, followed by semi-manual validation.
- **Entity & Relation Extraction**: Performed using GPT-3.5 via prompt-engineering techniques.
- **Knowledge Graph Construction**: Semantic triples structured and visualized using `vis.js`.
- **Taxonomy Development**: Hierarchical classification into Level 1 and Level 2 themes.
- **Multilayer Network Integration**: Combining semantic relations with citation networks for enriched analysis.

## Visualizations

Find interactive HTML visualizations in the `visualizations/` folder:

- `1_kg_scrolldown.html`: Full scrollable knowledge graph
- `2_kg_with_border.html`: With centrality and border
- `3_multilayer_network.html`: Citation-semantic hybrid
- `4_entities_level1.html`: Single-level taxonomy view
- `5_entities_l1_l2.html`: Two-level taxonomy view

## License

This project is licensed under the **MIT License**.

## Contact

**Nil Yagmur Ilba**  
Master’s Student in Digital Humanities  
École Polytechnique Fédérale de Lausanne (EPFL)  
Email: nil.ilba@epfl.ch
# Tracing Ecological Metaphors in Open Science using LLMs and Knowledge Graphs

This repository documents a research project analyzing the term **“ecosystem”** as it appears across Open Science discourses. Using LLM-powered NLP techniques and knowledge graph construction, the project maps the conceptual landscape surrounding ecological metaphors in scholarly literature.

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

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for full terms.

## Citation

If you use this work, please cite the preprint (forthcoming) or contact the author for citation information.

## Contact

Nil Yagmur Ilba  
EPFL Digital Humanities  
Email: yagmurilba@gmail.com
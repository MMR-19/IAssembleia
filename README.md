# IAssembleia

For this project I followed the DeepLearning.AI short course on ["Building Your Own Database Agent"](https://www.deeplearning.ai/short-courses/building-your-own-database-agent/).

Main topics: Azure OpenAI Service, LangChain, RAG

---

## ✨ Features

- JSON data processing
- Real-time chat with CSV database/files

---

## 📃 Data Processing and Analysis

1. **Source**: [Portuguese Parliament Initiatives](https://www.parlamento.pt/Cidadania/Paginas/DAIniciativas.aspx). A JSON file with all initiatives, acts, polls and votes for the 16th Legislature.

2. **Data structure**: Extracted the original schema manually from the JSON file. See more at [schema.json](data/raw/schema.json).

3. Used the [data_exploration](data_exploration.ipynb) notebook to explore the dataset and save the relevant info to CSV files. See all files at [data/processed](data/processed).

4. Final data structure:
- **Hierarchy**: initiatives > acts > polls > votes.
- **Fields**: check the [image](data/processed/fields.png) at [data/processed](data/processed) for info on final processed fields.

---

## License

[![License: CC BY-NC 4.0](https://img.shields.io/badge/license-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

You may use, share, and adapt this project for non-commercial purposes with proper attribution. Commercial use is not permitted.
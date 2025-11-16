# 🔎 RSCB Protein Analyzer

## 👩‍🔬 Описание проекта
Этот проект представляет собой автоматизированный пайплайн для сбора и анализа статистики по существующим структурам белка. На примере белка Cas9 (UniProt ID: Q99ZW2) демонстрируется процесс получения информации о структурах из базы данных PDB RCSB Protein Data Bank (PDB) с последующей обработкой и визуализацией данных.

## 📝 Задачи
- **Извлечение последовательностей**: извлечение данных о последовательностях белков и изоформах через UniProt API, экспорт в FASTA.
- **Поиск гомологичных структур**: поиск структур с высокой идентичностью  целевой последовательности (≥90%).
- **Извлечение и анализ метаданных**: о структурах, ранжирование последовательностей.
- **Интерактивная визуализация**.

## ☢️ Технологический стек
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Biopython](https://img.shields.io/badge/Biopython-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![UniProt](https://img.shields.io/badge/UniProt-0073E6?style=for-the-badge&logo=uniprot&logoColor=white)
![RCSB PDB](https://img.shields.io/badge/RCSB_PDB-4B8BBE?style=for-the-badge&logo=databricks&logoColor=white)

## 🧬 [Ноутбук проекта](https://github.com/alexarlenn/rscb-protein-analyzer/blob/main/pdb_rscb_get_information.ipynb)

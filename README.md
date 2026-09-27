Model-Driven Development: A Tertiary Review
Journal: Sosym

Authors: 
Raoni Sales de Oliveira¹
e-mail: raoni_si@hotmail.com

Rita Suzana Pitangueira Maciel¹
e-mail: rita.suzana@ufba.br

Ana Patrícia Fontes Magalhães Mascarenhas²
e-mail: anapatriciamagalhaes@gmail.com

Affiliation: Universidade Federal da Bahia¹, Universidade do Estado da Bahia².

This repository includes the following resources:

1.  Raw reference files (`.bib`)
Os arquivos contidos na pasta `raw_bib/` contêm os metadados bibliográficos completos exportados diretamente de cada base de dados em **[Insira a Data da Busca]**.
* **Campos incluídos:** `author`, `title`, `journal`, `year`, `abstract`, `keywords`, `doi`.
* **Como utilizar:** Podem ser importados diretamente para gerenciadores de referências como Zotero, Mendeley, EndNote ou softwares de triagem como o Rayyan.


2. Ontologia com todos os trechos que pudessem identificar autores removidos (Ontology.pdf)
3. Metamodelo criado manualmente pelo especialista de domínio (SpecialistDiagram.pdf)

4. Este repositório contém os dados brutos (*raw files*), os critérios de triagem e a matriz de extração de dados utilizados na revisão terciária descrita acima.


O repositório está organizado de forma a garantir a total reprodutibilidade do fluxo PRISMA adotado.

```text
├── data/
│   ├── raw_bib/                     # Exportações brutas das bases de dados
│   │   ├── pubmed_raw.bib           # Busca bruta do PubMed
│   │   ├── scopus_raw.bib           # Busca bruta do Scopus
│   │   └── wos_raw.bib              # Busca bruta da Web of Science
│   └── processing_excel/            # Triagem, gerenciamento e extração de dados
│       ├── 1_all_merged_duplicates.xlsx   # Todos os registros unificados + controle de duplicatas
│       ├── 2_screening_phase.xlsx         # Registros avaliados por Título/Resumo (Inclusos/Exclusos)
│       └── 3_data_extraction_matrix.xlsx  # Matriz final de extração das revisões incluídas
```

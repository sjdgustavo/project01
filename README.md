# 🧮 project01 - Pipeline de Dados

Esse é um projeto de exemplo da minha Faculdade de Pós Graduação em Engenharia de Dados. 
Um pipeline modular de **ingestão**, **enriquecimento** e **refinamento** de dados utilizando **Python**, **SQL** e **DuckDB**.  

---

## 📦 Estrutura do Projeto
```bash
project01/
├── landing/                        # Área de entrada de arquivos brutos
│   ├── z0019_1.csv
│   └── z0019_2.csv
├── scripts/                        # Lógica principal do pipeline
│   ├── 01_ingestao.ipynb           # Leitura e normalização de dados
│   ├── 02_enriquecimento.ipynb     # Junções, cálculos e padronizações
│   ├── 03_refinamento.ipynb        # Consolidação e geração de outputs finais
│   └── dados_duckdb.db             # Banco (ignorado no Git)
├── .gitignore
└── README.md
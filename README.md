# Python Insights - Analisando Cancelamento de Clientes

Projeto de análise de dados focado em entender motivos de cancelamento de clientes.

Conteúdo do repositório
- [inicial.ipynb](inicial.ipynb) — notebook principal com análise e visualizações.

Pré-requisitos
- Python 3.8+

Instalação (local)
1. Criar um ambiente virtual:

   `python -m venv .venv`

2. Ativar o ambiente (Windows):

   `.venv\Scripts\activate`

3. Instalar dependências:

   `pip install -r requirements.txt`

Executar
- Abrir o notebook `inicial.ipynb` (opções):

   - Via Jupyter: inicie o servidor e abra o notebook:

      `jupyter notebook`

   - Via VS Code: abra a pasta do projeto no VS Code e clique em `inicial.ipynb` (VS Code abre notebooks sem precisar iniciar Jupyter).

   - Converter para script: se preferir rodar como script Python:

      `jupyter nbconvert --to script inicial.ipynb`
      `python inicial.py`

- Observação: verifique se `cancelamentos.csv` é grande antes de versioná-lo no GitHub; considere usar um storage externo se for pesado.


# 📊 Dashboard de Salários em Dados - Projeto da Imersão Dados com Python da Alura

Este projeto é um dashboard interativo para análise de salários na área de tecnologia e dados, desenvolvido como projeto prático da **Imersão Dados com Python da Alura**. A aplicação web foi construída com Streamlit e permite a exploração de um conjunto de dados real sobre remuneração, oferecendo insights visuais através de filtros e gráficos dinâmicos.

**➡️ Acesse o dashboard online aqui:** [https://imersao-dados-python-alura-2025-rogerrrr.streamlit.app/](https://imersao-dados-python-alura-2025-rogerrrr.streamlit.app/)

---

## ✨ Funcionalidades Principais

O dashboard oferece uma análise completa com as seguintes funcionalidades:

* **Métricas Gerais (KPIs):** Visualização rápida do salário médio, salário máximo, total de registros filtrados e o cargo mais frequente.
* **Filtros Interativos:** Permite ao usuário segmentar os dados por:
    * Ano
    * Nível de Senioridade
    * Tipo de Contrato
    * Tamanho da Empresa
* **Gráficos Dinâmicos:**
    * **Top 10 Cargos:** Gráfico de barras com os maiores salários médios.
    * **Distribuição Salarial:** Histograma que mostra a frequência das faixas salariais.
    * **Proporção de Trabalho Remoto:** Gráfico de pizza (donut) que ilustra a preferência por modelos de trabalho (remoto, híbrido, presencial).
    * **Salário de Cientista de Dados por País:** Mapa coroplético com a média salarial para *Data Scientists* ao redor do mundo.
* **Tabela de Dados Detalhada:** Apresenta o dataframe com os dados filtrados para uma análise mais granular.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias e bibliotecas:

* **Python:** Linguagem principal para a análise e manipulação dos dados.
* **Streamlit:** Framework utilizado para construir e implantar a aplicação web interativa.
* **Pandas:** Biblioteca para carregamento, manipulação e filtragem dos dados.
* **Plotly Express:** Biblioteca para a criação dos gráficos dinâmicos e visualmente atraentes.

---

## 🚀 Como Executar o Projeto Localmente

Para executar este projeto em sua máquina local, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
    cd SEU-REPOSITORIO
    ```

2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    (É uma boa prática criar um arquivo `requirements.txt` com as bibliotecas `streamlit`, `pandas` e `plotly`)
    ```bash
    pip install streamlit pandas plotly
    ```

4.  **Execute a aplicação Streamlit:**
    (Assumindo que seu arquivo Python se chama `app.py`)
    ```bash
    streamlit run app.py
    ```

---

## 📄 Dados

O conjunto de dados utilizado neste projeto foi fornecido durante a Imersão Dados com Python da Alura pela Kaggle e contém informações anonimizadas sobre salários na área de dados, abrangendo diferentes cargos, senioridades, países e outros fatores relevantes.

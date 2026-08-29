# 📊 Panorama Salarial Global em Data Science (2020-2023)

Bem-vindo ao repositório oficial do projeto de Análise Exploratória de Dados (EDA) desenvolvido no canal **Insight em Dados**.

Este projeto tem como objetivo destrinchar o mercado global de tecnologia, fornecendo inteligência de negócios e *insights* validados matematicamente sobre remuneração, nível de senioridade e volumetria de vagas. É um material desenhado tanto para auditagem do código apresentado em vídeo quanto para servir de fundação na construção de portfólios analíticos robustos, especialmente para profissionais que buscam oportunidades de nível Júnior (*Entry-level*) em Análise de Dados e Business Intelligence.

---

## 🛠️ Stack Tecnológico

O pipeline de dados foi integralmente desenvolvido em ambiente **Jupyter Notebook**, empregando o seguinte ecossistema de bibliotecas no Python:

*   **Manipulação Algébrica e Limpeza:** `pandas`, `numpy`
*   **Visualização Vetorial e Estatística:** `matplotlib`, `seaborn` 
    * *(Nota de Acessibilidade: Gráficos parametrizados com a paleta 'viridis' e estilo 'ggplot' para garantir legibilidade corporativa e contraste adequado para espectadores com daltonismo).*

---

## 🧠 Estrutura da Análise e Principais Insights

O *notebook* está dividido em blocos lógicos focados em regra de negócio e rigor estatístico:

1.  **Data Cleaning & Feature Selection:** Tratamento de viés através da remoção de instâncias duplicadas e otimização da dimensionalidade do *schema*.
2.  **Feature Mapping:** Transformação de metadados obscuros em uma taxonomia corporativa fluida.
3.  **Análise Univariada (Volumetria):** Identificação da "Tríade dos Dados", comprovando a altíssima liquidez de mercado para *Data Engineers*, *Data Scientists* e *Data Analysts*.
4.  **Análise Bivariada (Boxplot):** Avaliação da progressão salarial e dispersão por nível de senioridade, mapeando a elasticidade do mercado através de *outliers*.
5.  **Modelagem Longitudinal (Série Temporal):** Comprovação do *boom* de mercado de 2022, utilizando a mediana como agregador estatístico robusto contra distorções.
6.  **Análise de Assimetria (Histograma com KDE):** Estudo da macroestrutura probabilística e do fenômeno de cauda longa (Assimetria à Direita).
7.  **Impacto do Porte Corporativo:** Refutação empírica de paradigmas clássicos, demonstrando o agressivo poder de compensação financeira das empresas de médio porte (*scale-ups*).

---

## 🚀 Como Executar o Projeto Localmente

Para garantir a replicabilidade deste relatório na sua máquina local, todo o código e os dados tratados foram empacotados.

1. Acesse a aba **[Releases](../../releases)** deste repositório.
2. Faça o download do arquivo compactado contendo o `Data_Science_Salaries_2023.ipynb` e a base de dados `ds_salaries.csv`.
3. Extraia os arquivos em um mesmo diretório e inicie o seu servidor Jupyter.

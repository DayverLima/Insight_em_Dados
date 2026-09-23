# 🇮🇳 Panorama dos Destinos Turísticos na Índia: Uma Análise de Dados

Bem-vindo ao repositório oficial do projeto de Análise Exploratória de Dados (EDA) sobre o turismo na Índia, desenvolvido no canal **Insight em Dados**.

Este projeto tem como objetivo destrinchar as características das principais atrações turísticas indianas, fornecendo inteligência de negócio e *insights* sobre custos, tempo de visitação e avaliações do público. É um material desenhado tanto para acompanhamento passo a passo do código apresentado em vídeo quanto para servir de fundação na construção de portfólios analíticos, especialmente para profissionais que buscam aprimorar suas habilidades práticas em manipulação e visualização de dados com Python.

---

## 🛠️ Stack Tecnológico

O pipeline de dados foi integralmente desenvolvido em ambiente **Jupyter Notebook**, empregando o seguinte ecossistema de bibliotecas no Python:

*   **Manipulação Algébrica e Limpeza:** `pandas`, `numpy`
*   **Visualização Vetorial e Estatística:** `matplotlib`, `seaborn` 
    * *(Nota: Gráficos parametrizados para garantir legibilidade, contraste e uma apresentação visual limpa para facilitar a extração rápida de insights).*

---

## 🧠 Estrutura da Análise e Principais Insights

O *notebook* está dividido em blocos lógicos focados em limpeza estrutural e exploração visual:

1.  **Data Cleaning & Estruturação:** Importação e tratamento inicial da base original (`Top Indian Places to Visit.csv`), lidando com valores ausentes e adequação dos tipos de dados usando Pandas.
2.  **Análise de Distribuição e Avaliações:** Mapeamento geral de como o público avalia os destinos turísticos indianos, buscando entender a média de qualidade das atrações.
3.  **Investigação de Outliers (Boxplot):** Avaliação de anomalias nas notas recebidas. Neste bloco (Bloco 5), isolamos e identificamos estatisticamente o parque *Imagicaa* como um forte *outlier* negativo em termos de avaliação.
4.  **Correlação Custo vs. Tempo (Gráfico de Dispersão):** Estudo bivariado (Bloco 6) para mapear se atrações que exigem mais tempo de visitação também possuem um custo mais elevado, oferecendo um guia claro de custo-benefício para os turistas.
5.  **Engenharia de Atributos e Categorização:** Segmentação dos destinos para entender quais tipos de atrações (históricas, naturais, entretenimento) dominam o cenário turístico da Índia.

---

## 🚀 Como Executar o Projeto Localmente

Para garantir a replicabilidade deste relatório na sua máquina local, todo o código e os dados tratados foram empacotados.

1. Acesse a aba **[Releases](../../releases)** deste repositório.
2. Faça o download do arquivo compactado contendo o *notebook* da análise e a base de dados `Top Indian Places to Visit.csv`.
3. Extraia os arquivos em um mesmo diretório e inicie o seu servidor Jupyter.
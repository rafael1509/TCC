# Análise da Influência do Tema da Redação do ENEM 2022 sobre Indivíduos de Cor/Raça Indígena

## Descrição do Projeto

[cite_start]Este projeto, desenvolvido como Trabalho de Conclusão de Curso para a Escola de Matemática Aplicada da Fundação Getulio Vargas (FGV EMAP) [cite: 5][cite_start], investiga se o tema da redação do Exame Nacional do Ensino Médio (ENEM) de 2022 — "Desafios para a valorização de comunidades e povos tradicionais no Brasil" — influenciou o desempenho de candidatos autodeclarados indígenas[cite: 37, 39].

[cite_start]A análise busca compreender como a escolha de temas de redação pode impactar a equidade do exame entre diferentes grupos sociais [cite: 39][cite_start], controlando por diversas variáveis socioeconômicas para isolar o efeito da temática[cite: 41, 42].

## Fonte dos Dados

[cite_start]Os dados utilizados neste estudo são os Microdados do ENEM, disponibilizados publicamente pelo Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP)[cite: 48]. [cite_start]Para esta análise, foram consideradas as edições de 2021, 2022 e 2023[cite: 53].

- **Link para os dados:** [Microdados do Enem - INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)

## Metodologia

A metodologia adotada para esta análise pode ser resumida nas seguintes etapas:

1.  [cite_start]**Tratamento dos Dados:** A análise foca em alunos que estavam cursando o último ano do ensino médio, a fim de garantir maior homogeneidade da amostra[cite: 56].

2.  **Pareamento (Matching):** Para garantir uma comparação justa entre os grupos, foi utilizada a técnica de *matching* exato. [cite_start]Para cada aluno indígena, foi identificado um aluno não indígena com perfil socioeconômico e demográfico similar (faixa etária, tipo de escola, renda, escolaridade dos pais, etc.), reduzindo, assim, possíveis vieses na análise[cite: 58, 59, 60].

3.  [cite_start]**Análise Exploratória:** Foram analisadas as distribuições das notas e as correlações entre as variáveis para entender as relações existentes, especialmente após a aplicação do *matching*[cite: 144, 145]. [cite_start]Um dos achados preliminares é que, em 2022, a diferença de desempenho entre indígenas e não-indígenas diminuiu após o pareamento, o que não foi observado com a mesma intensidade nos outros anos[cite: 116].

4.  [cite_start]**Modelagem Estatística:** O próximo passo da análise consiste na aplicação de modelos de regressão linear para estimar o impacto da autoidentificação como indígena na nota da redação, controlando pelas demais variáveis[cite: 239, 240]. [cite_start]O objetivo é verificar se o coeficiente associado a ser indígena no ano de 2022 é estatisticamente significativo[cite: 231].

## Estrutura do Repositório

-   `/codigo`: Contém os scripts em R/Python utilizados para o tratamento, análise e modelagem dos dados.
-   `/relatorio`: Contém o arquivo `projeto_tcc.pdf` com o relatório parcial do projeto.
-   `README.md`: Este arquivo.

## Como Replicar a Análise

1.  Faça o download dos microdados do ENEM para os anos de 2021, 2022 e 2023 no [site do INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem).
2.  Clone este repositório: `git clone https://www.youtube.com/shorts/apr341idq8U`
3.  Instale as dependências listadas no arquivo `requirements.txt` (ou similar).
4.  Execute os scripts na pasta `/codigo` na ordem indicada para reproduzir os resultados.

## Status do Projeto

Este é um projeto em andamento. [cite_start]As próximas etapas incluem a finalização da modelagem de regressão, a realização de diagnósticos do modelo [cite: 247] [cite_start]e a elaboração das conclusões finais do estudo[cite: 236].

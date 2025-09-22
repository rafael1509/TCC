# Análise da Influência do Tema da Redação do ENEM 2022 sobre Indivíduos de Cor/Raça Indígena

## Descrição do Projeto

Este projeto, desenvolvido como Trabalho de Conclusão de Curso para a Escola de Matemática Aplicada da Fundação Getulio Vargas (FGV EMAP), investiga se o tema da redação do Exame Nacional do Ensino Médio (ENEM) de 2022 — "Desafios para a valorização de comunidades e povos tradicionais no Brasil" — influenciou o desempenho de candidatos autodeclarados indígenas.

A análise busca compreender como a escolha de temas de redação pode impactar a equidade do exame entre diferentes grupos sociais, controlando por diversas variáveis socioeconômicas para isolar o efeito da temática.

## Fonte dos Dados

Os dados utilizados neste estudo são os Microdados do ENEM, disponibilizados publicamente pelo Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP). Para esta análise, foram consideradas as edições de 2021, 2022 e 2023.

- **Link para os dados:** [Microdados do Enem - INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)

## Metodologia

A metodologia adotada para esta análise pode ser resumida nas seguintes etapas:

1.  **Tratamento dos Dados:** A análise foca em alunos que estavam cursando o último ano do ensino médio, a fim de garantir maior homogeneidade da amostra.

2.  **Pareamento (Matching):** Para garantir uma comparação justa entre os grupos, foi utilizada a técnica de *matching* exato. Para cada aluno indígena, foi identificado um aluno não indígena com perfil socioeconômico e demográfico similar (faixa etária, tipo de escola, renda, escolaridade dos pais, etc.), reduzindo, assim, possíveis vieses na análise.

3.  **Análise Exploratória:** Foram analisadas as distribuições das notas e as correlações entre as variáveis para entender as relações existentes, especialmente após a aplicação do *matching*. Um dos achados preliminares é que, em 2022, a diferença de desempenho entre indígenas e não-indígenas diminuiu após o pareamento, o que não foi observado com a mesma intensidade nos outros anos.

4.  **Modelagem Estatística:** O próximo passo da análise consiste na aplicação de modelos de regressão linear para estimar o impacto da autoidentificação como indígena na nota da redação, controlando pelas demais variáveis. O objetivo é verificar se o coeficiente associado a ser indígena no ano de 2022 é estatisticamente significativo.

## Status do Projeto

Este é um projeto em andamento. As próximas etapas incluem a finalização da modelagem de regressão, a realização de diagnósticos do modelo e a elaboração das conclusões finais do estudo.

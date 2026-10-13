# Clusterização de jogadores do Audax Rio de Janeiro EC

Trabalho da disciplina ME921A (UNICAMP): agrupamento de jogadores de futebol
a partir de dados de desempenho físico medidos por GPS (Catapult Sports) em 53
jogos de 2024.

**Métodos:** agrupamento baseado em modelo (algoritmo EM) com mistura de
distribuições t de Student multivariadas, escolha do número de grupos por BIC,
identificação de outliers pelo método dos vizinhos mais próximos e PCA para
visualização.

**Pacotes em R:** readr, GGally, mclust, covRobust.

## Conteúdo

- `Atividade_2_ME921A.pdf`: relatório completo (introdução, métodos, resultados e discussão).

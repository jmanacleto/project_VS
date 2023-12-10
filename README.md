# project_VS

Este código em Python realiza a leitura de um arquivo CSV contendo dados do Auxílio Emergencial. Após a leitura, são realizadas manipulações nos dados, incluindo a correção do formato numérico e o agrupamento por código do município SIAFI. O resultado é salvo em um novo arquivo CSV, onde as colunas representam o número de linhas e o total repassado para cada código de município em novembro de 2020. O código demonstra habilidades em manipulação de dados usando pandas, tratamento de formatos e operações de agregação. Recomenda-se adicionar documentação ao repositório, incluindo um README explicativo.


Leitura de um Arquivo CSV:

O código lê um arquivo CSV localizado em C:/Users/User/202011_AuxilioEmergencial.csv usando a biblioteca pandas.
Manipulação dos Dados:

Substitui vírgulas por pontos na coluna "VALOR PARCELA" para tornar os valores numéricos válidos.
Agrupa os dados pelo código do município SIAFI.
Calcula o número de linhas e a soma dos valores da coluna "VALOR PARCELA" para cada grupo.
Renomeação de Colunas:

Renomeia as colunas resultantes para "Número de Linhas" e "Total Repassado".
Adição de Coluna de Ano:

Adiciona uma coluna chamada "ID_ANO" com o valor 2021.
Reset do Índice:

Reseta o índice do DataFrame resultante após a operação de agrupamento.
Salvamento dos Resultados:

Salva o DataFrame resultante em um novo arquivo CSV no caminho especificado (C:\Users\João Miguel\Documents\projeto\Auxilio Emergencial\arq_csvaux2), com o nome 202011_AuxilioEmergencial.csv.
Impressão do Caminho de Saída:

Imprime no console o caminho onde o arquivo CSV resultante foi salvo.

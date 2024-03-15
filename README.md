# CDados_1
GitHub para o Primeiro projeto de Ciência dos Dados, matéria ministrada no segundo semestre de Engenharia da Computação no Insper

###O que será realizado?

Será produzido um Classificador para identificção de sentenças, produzidas por Humanos e Inteligência Artificial

### Descrição

O classificador será feito com o intuito de analisar quantas frases foram feitas por inteligência artificial(AI) e quantas frases foram feitas por humanos(HG, Human Generated, em ingles) e isso será feito por meio da comparação das frequências relativas entre cada palavra dita por humanos e por cada palavra dita pela inteligência artificial, que está armazenada em uma base de dados, arquivo com o nome "dados_teste_TRIO_USERNAME.csv", no código. Com esse arquivo e com o arquivo"dados_treino_TRIO_USERNAME.csv", será possível calcular as frequências relativas entre as palavras, sendo possível associar essas frequências com a probabilidade e então identificar qual frase possui uma maior probabilidade de ser HG ou AI.

Isso será feito por meio da probabilidade condicional (teorema de Bayes) com um incremento nesse teorema, sendo conhecido no "mundo" do estudo de dados como "naive Bayes", em que "naive", do inglês, significa ingênuo. A ingenuidade desse algoritmo se da pelo fato do incremento no teorema se fundamentar na independência de eventos entre si, ou seja, aplicando para esse caso, a probabilidade de um evento acontecer não depende de nenhum outro que já aconteceu ou que acontecerá. Trazendo para o caso das frases, a principal característica desse modelo é de não considerar que a palavra que está sendo dita está em um contexto e a probabilidade dessa nova palavra ser dita não depende da palavra anterior e nem da futura.

Com isso, será feita uma comparação entre as probabilidades e será analisada qual probabilidade é maior e então será classificada como "AI" ou como "HG".

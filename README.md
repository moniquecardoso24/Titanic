# Titanic
Aprendizado do projeto Titanic

Link do Kaggle: https://www.kaggle.com/competitions/titanic/overview

O objetivo da competição é usar Machine Learning para criar um modelo que preveja quais passareiros sobreviveram ao naugrágio do Titanic.

Embora houvesse algum elemento de sorte envolvido na sobrevivência, parece que alguns grupos de pessoas eram mais propensos a sobreviver do que outros.

O desafio requer a construção de um modelo preditivo que responda à pergunta: “que tipo de pessoa tem maior probabilidade de sobreviver?” usando os dados do passageiro (ou seja, nome, idade, sexo, classe socioeconômica, etc).

Um conjunto de dados utilizados são os arquivos train.csv e test.csv.

- Train.csv contém os detalhes de um subconjunto dos passageiros a bordo (891 para ser exato) e, mais importante, revelará se eles sobreviveram ou não, também conhecido como “verdade terrestre”.

- Test.csv contém informações semelhantes, mas não revela a “verdade básica” para cada passageiro. É seu trabalho prever esses resultados.

Usando os padrões encontrados nos dados train.csv, preveja se os outros 418 passageiros a bordo (encontrados em test.csv) sobreviveram.

O conjunto de treino(train) foi usado para criar seus modelos de aprendizado de máquina. Nesse conjunto treinamento, o resultado é fornecido (também conhecido como “verdade básica”) para cada passageiro. O modelo é baseado em “características” como sexo e classe dos passageiros. 

O conjunto de teste(test) foi usado para ver o desempenho do modelo em dados não vistos. Não é fornecida a verdade básica para cada passageiro. O trabalho do projeto é prever esses resultados. Para cada passageiro no conjunto de teste, foi usado o modelo que treinado para prever se eles sobreviveram ou não ao naufrágio do Titanic.

O resultado é avaliado através da acurácia:
"Sua pontuação é a porcentagem de passageiros que você prevê corretamente. Isso é conhecido como acurácia."


Foi utilizado o ydata-profiling (antigo Pandas Profiling) para começar a entender essa base. Link do código:
https://github.com/ydataai/ydata-profiling

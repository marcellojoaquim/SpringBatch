# Processamento de arquivos com Spring Batch

## Descricao

Neste projeto é apresentado o Spring Batch e como usa-lo para processar dados em lotes.
A partir de uma planilha (sample-data.csv) os dados são processados e persistidos em banco de dados,
antes da persistência os dados são normalizados.

Com Spring Batch é possível processar grandes volumes de dados com alta performance.
Cada linha do arquivo csv é mapeado para a entidade, os dados são validados, normalizados e persistidos no banco
com alta performance no processamento. Cada etapa pode ser vista no console durante a execução do projeto.

## Tecnologias

* Java 17
* Spring Batch
* Hsqldb para persistência dos dados em memória

## Como executar

* mvn clean package
* Localize o arquivo .jar no diretório target e execute o comando: java -jat arquivo.jar para executar o projeto.

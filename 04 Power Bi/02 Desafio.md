# Desafio de Projeto: Processamento de Dados com Power BI e MySQL na Azure

Neste desafio, você será responsável por aplicar as etapas de coleta, obtenção e transformação de dados utilizando o Power BI e MySQL na plataforma Azure.

## Descrição do Projeto

O projeto consiste em realizar o processamento de dados utilizando o Power BI e MySQL na Azure, seguindo as seguintes etapas:

### Processamento de Dados Simplificado com Power BI

1. Criação de uma instância na Azure para MySQL.
2. Criar o banco de dados com base disponível no [GitHub](https://github.com/nome_usuario/repositorio).
3. Integração do Power BI com MySQL na Azure.
4. Verificar problemas na base a fim de realizar a transformação dos dados.

### Diretrizes para Transformação dos Dados

1. Verificar os cabeçalhos e tipos de dados.
   - Conversão para português nos títulos.
2. Modificar os valores monetários para o tipo double preciso.
3. Verificar a existência dos nulos e analisar a remoção.
4. Verificar se há employees com nulos em Super_ssn que podem ser os gerentes.
5. Verificar se há algum departamento sem gerente.
6. Se houver departamento sem gerente, preencher as lacunas.
7. Verificar o número de horas dos projetos.
8. Separar colunas complexas.
9. Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores.
10. Eliminar colunas desnecessárias.
11. Realizar a junção dos colaboradores e respectivos nomes dos gerentes.
12. Mesclar as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores.
13. Mesclar os nomes de departamentos e localização.
14. Explicar o motivo de utilizar apenas a mescla e não o atribuir em determinados casos.
15. Agrupar os dados a fim de saber quantos colaboradores existem por gerente.
16. Eliminar as colunas desnecessárias de cada tabela.

### Configuração do Setup de BD na Azure

1. Configurar o servidor na Azure com MySQL.
2. Popular o servidor com script fornecido.

### Integração do MySQL com Power BI

1. Integrar o MySQL com Power BI.

### Realização das Transformações Indicadas

1. Realizar as transformações descritas nas etapas anteriores.

## SQL Utilizado

Se for utilizado SQL para alguma etapa do processo de transformação, especifique a query utilizada no README.

## Agradecimentos

Este projeto foi elaborado como parte de um desafio de curso. Agradeço a oportunidade de aprender e desenvolver habilidades em Power BI e MySQL na Azure.


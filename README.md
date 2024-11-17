# Esquema Conceitual para Oficina Mecânica

Curso: Suzano - Análise de Dados com Power BI

Autor: Carlos Afonso Feldhaus Filho

## Objetivo:

- Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

## Ferramentas utilizadas

- [MySQL Workbench](https://www.mysql.com/products/workbench/)

## Narrativa:

Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica

Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas

Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.

A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra

O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços

A mesma equipe avalia e executa os serviços

Os mecânicos possuem código, nome, endereço e especialidade

Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

## Modelagem:

![Oficina](https://github.com/user-attachments/assets/349568e9-a851-47a8-a497-2f47bef180cc)

- Clientes podem ser PF ou PJ e podem possuir mais de um veículo;
  
- Após o veículo chegar a oficina os mecânicos fazem uma avaliação;
  
- Na avaliação temos o tipo de serviço a ser executado e a relação das peças e mão de obra com valores pré estabelicidos;
  
- Após a avaliação é gerada uma ordem de serviço onde os mesmos mecânicos, os quais avaliaram o veículo, executam o serviço;

# Certificado:

![MYZ4JKRT-1](https://github.com/user-attachments/assets/56e6e9dd-be71-4e4a-a79d-ce9d95bd52c5)



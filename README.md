# Back-end JR Challenge
Esse desafio tem o objetivo de testar algumas habilidades em back-end.

## O Desafio
Criar uma API para gestão de frete de uma transportadora

A api consiste em algumas entidades:

##### Motorista - Motorista que irá efetuar o frete)
- O motoristorista pode aceitar o frete de apenas uma transportadora

##### Transportadora - Empresa que irá disponibilizar o frete)
- A transportadora pode disponibilizar vários fretes
- Os fretes precisam ser ordenados por status e data

##### Frete - Frete disponibilizado peka transportadora)
- O cálculo do frete é a soma do KM + volume da carga em KG

##### Veículo - Veículo que irá efetuar o frete
- Veículo deve ser de um motorista

##### Tipo de veículo - Tipos de veículos
 - Os tipos de veículos devem conter os seguintes campos:
	- Capacidade em kg
	- Algura do baú
	- Largura do baú
	- Comprimento do baú
	- Peso total do veículo


## Documentação
 No README do projeto explique:
- Passos para execução do projeto.

## Requisitos
 - Usar língua inglesa para escrita do código
 - Usar NodeJs + TypeScript
 - Banco de dados Postgres
 - Adicionar swagger 
 -  API RestFull
 - Você é livre para utilizar algum framework node ex: Nest 
 - Você é livre para definir a modelagem e organização das features a serem implementadas.

## O que será avaliado
 - Organização do projeto.
 - Simplicidade da implementação.
 - Modelagem do Banco de Dados.
 - Qualidade do código.
 - Utilização correta dos status HTTP (200, 404, 500, etc...)
 Processo de build.
 - Qualidade dos testes (é um diferencial).

## Dúvidas
Caso não encontre a sua resposta, sinta-se à vontade para abrir uma issue =]



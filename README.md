# DesafioProjeto_DIO

## Repositório criado para o Desafio de Projeto do BOOTCAMP de Dados da DIO.
#### Objetivo: criar um Esquema Conceitual do zero de uma Oficina Mecânica.

### SISTEMA DE CONTROLE E GERENCIAMENTO DE EXECUÇÃO DE ORDENS DE SERVIÇO EM UMA OFICINA MECÂNICA.

- O cliente leva o veículo para a Mecânica para ser consertado ou para passar por revisão periódica --> ESSA INFORMAÇÃO FOI INCLUÍDA COMO ATRIBUTO NA ENTIDADE Ordem_Servico
- Uma equipe de mecânicos avalia, abre uma Ordem Serviço (OS) e a mesma equipe executa o serviço;
- O cliente autoriza o serviço;
- A partir da OS é calculado o valor do serviço, conultando tabela de mão de obra;
- O valor de cada peça também irá compor a OS;
- Entidade mecânicos possui: código, nome, endereço e especialidade; Entidade OS possui: n°, data de emissão, valor, status e uma data para conclusão dos trabalhos.


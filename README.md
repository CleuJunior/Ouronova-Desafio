## Desafio Ouro Novo

#### Considerando o projeto de monitoramento de risers:

- Uma plataforma pode conter `N` **risers**;
- Cada **riser** tem `64` arames, ordenados de `1` a `64`;
- Um cordão de **fibra ótica** tem `16` sensores, ordenados de `1` a `16`;
- Cada arame tem um **sensor ótico** conectado, portanto, um cordão consegue monitorar `16` arames;
- Um cordão pode dar defeito e ser trocado por outro cordão, porém os dados do cordão defeituoso não podem ser trocados;

Crie um modelo de dados que atenda aos requisitos acima e pelo menos um serviço REST para cadastro de uma das entidades do modelo de dados criado.
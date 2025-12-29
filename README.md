# JornadaDev - Projeto de Certificação 2

## Dados dos atletas

***Aplicação em JavaScript para armazenar e apresentar os dados de um atleta numa competição de ginástica artística, além de calcular média e imc.***

**Cenário:** Em uma determinada competição de ginástica artística, vários atletas realizam apresentações para uma banca composta por cinco jurados. Cada jurado é responsável por avaliar um critério em específico, sendo eles o tempo de duração da apresentação, originalidade da coreografia, postura do atleta, dificuldade das acrobacias e sincronismo.

A competição em questão possui a seguinte regra de avaliação:

- Cada jurado pode fornecer uma nota de um (1) a dez (10);
- A média é calculada com base nas três notas do meio, desconsiderando a maior e menor nota.

**Especificações:** Criar uma classe "Atleta" para concentrar os atributos e métodos dos atletas.

A classe deverá receber os seguintes atributos:

- nome;
- idade;
- peso;
- altura;
- notas.

A classe deverá possuir os seguintes métodos:

- calculaCategoria(), para calcular a categoria do atleta;
- calculaIMC(), para calcular o IMC do atleta;
- calculaMediaValida(), para calcular a média válida do atleta;
- obtemNomeAtleta(), que retorna o nome do atleta;
- obtemIdadeAtleta(), que retorna a idade do atleta;
- obtemPesoAtleta(), que retorna o peso do atleta;
- obtemNotasAtleta(), que retorna as notas do atleta;
- obtemCategoria(), que retorna a categoria do atleta;
- obtemIMC(), que retorna o IMC do atleta;
- obtemMediaValida(), que retorna a média válida do atleta.

Utilize as seguintes regras:

1. Para calcular a categoria

- Infantil: 9 a 11 anos;
- Juvenil: 12 e 13 anos;
- Intermediário: 14 e 15 anos;
- Adulto: 16 a 30 anos;
- Sem categoria: demais idades.

2. Para calcular o IMC

**Fórmula: imc = peso / (altura x altura)**

3. Para calcular a média válida

**Método: Utilize o metodologia abordada no Projeto de Certificação 1.**


**Entrada:**
```JavaScript
const atleta = new Atleta("Cesar Abascal",
    30, 80, 1.70,
    [10, 9.34, 8.42, 10, 7.88]);
```

**Saída:**
```
Nome: Cesar Abascal
Idade: 30
Peso: 80
Altura: 1.7
Notas: 10,9.34,8.42,10,7.88
Categoria: Adulto
IMC: 27.68166089965398
Média válida: 9,25333333
```

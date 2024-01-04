# Projeto Comportamento do Consumidor: Pandas x SQL

****

## Sobre o projeto:

Este projeto foi inteiramente feito apenas utilizando Pandas e PandasSQL para analisar os dados!

Este projeto busca entender quais são os principais produtos comprados pelo consumidor e suas principais características buscando, com isso, nortear estratégias de marketings para as marcas e produtos, visando um aumento nas vendas e em sua receita!.

O dataset pode ser baixado [aqui]([https://www.kaggle.com/datasets/spscientist/students-performance-in-exams](https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset?select=shopping_trends.csv)).

##  Análise descritiva:

Respondendo as perguntas:

1. Qual é a distribuição demográfica dos clientes em termos de idade e gênero?
   
![pergunta 1 pandas](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/6b46839c-1f59-4494-8e9c-ec84a2873418)

<br>

![pergunta 1 sql](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/a62c4b45-19c2-437f-9a4f-43bf7b42873d)


**De acordo com o dataset, os homens possuem um maior número de usuários em relação às mulheres. No entanto, ambos os gêneros dos usuários apresentam uma média de idade semelhante, 44 anos!**

<br>

<br>

2. Qual é o item mais comprado em cada categoria entre os diferentes gêneros dos usuários?

2.1 Para a categoria de Acessórios:

![pergunta 2 pandas part 1](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/93e825d1-4a47-4393-aedd-0f9e348c27a2)
![pergunta 2 pandas part 2](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/c10bd38b-5ab8-4689-82d2-f0026802c74a)

<br>

![pergunta 2 sql part 1](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/2cd16616-a3d6-48e3-ac2b-4994895e6385)
![pergunta 2 sql part 2](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/7af945ba-5384-4cf0-9dd1-c481ab5c0560)


**O item mais comprado entre o público masculino foi Jóias que representou uma porcentagem de 13,79%, enquanto que para o publico feminino foi Mochila de Mão com 14% das compras da categoria Acessórios!**

<br>

2.2 Para a categoria de Vestuário:
   
![pergunta 2 pandas part 3](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/b44751f8-700c-4ffb-b21c-1aa665a34c6e)
![pergunta 2 pandas part 4](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/bffc5b79-e066-4e47-a726-bc66afebbfcf)

<br>

![pergunta 2 sql part 3](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/cbf60c0f-97d2-403d-ad27-fe886031ae6a)
![pergunta 2 sql part 4](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/a587709c-df3c-4e6f-a6d1-1b6367daae9d)


**Os itens mais comprados entre o público masculino da categoria de Vestuário foram calças e sweters , representando 10% e 9% respectivamente, enquanto que no público feminino foram Blusas, com 11%, e Camisetas, com 10%, de todas as compras da categoria!**


<br>


2.3 Para a categoria de calçados:

![pergunta 2 pandas part 5](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/d0257f88-c9f1-4029-91ba-1dad265a75c3)

<br>

![pergunta 2 sql part 5](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/81e4f47c-6d0f-489e-ab47-f4a470a85e02)
![pergunta 2 sql part 6](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/ff4a8335-ec2f-4fc2-a584-bdd1f4277d70)


**O item mais comprado entre o público masculino da categoria de Calçados foram tênis, sapatos e sandálias cada um deles representando 25% do total, enquanto que no público feminino foi sandália, com 29% de todas as compras da categoria!**


<br>


2.4 Para a categoria de Agasalhos:

![pergunta 2 pandas part final](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/e3dec9c2-b543-41ed-9296-2e6ff7a57416)

<br>

![pergunta 2 sql part 7](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/8dbf0a5c-d579-49be-83c1-72d364f3cfa1)
![pergunta 2 sql part final](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/da9af933-701c-43a9-9ca8-549c78ff84ce)


**O item mais comprado entre o público masculino da categoria de Agasalhos foi casacos, representando 51%, enquanto que no público feminino foi jaqueta com 53% de todas as compras da categoria!**

<br>

<br>

3. Os clientes que usam códigos promocionais têm maior propensão à assinatura?

![pergunta 3 pandas](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/d39d97a1-b4a8-46a4-be0a-abad40b61767)

<br>

![pergunta 3 sql](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/72fa90b9-140b-4fd8-90e8-1335c41623f1)



**De acordo com as análises, é visto que a maioria dos usuários, 63% deles, que usam código promocional em suas compras optaram pelo plano de assinatura!**

<br>

<br>

4. Qual a predileção de produtos comprados pelos jovens (entre 18 e 25 anos) em relação aos adultos (maior que 25 anos)? Esta predileção varia em relação ao gênero?
   
   4.1 Em relação aos usuários masculinos:

![pergunta 4  homem pandas part 1](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/2a8ceb35-852e-430f-90e2-5712a502cf5c)
![pergunta 4  homem pandas part 2](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/55fb0fbc-e4e7-449f-9e9a-e9fddccc8513)
![pergunta 4  homem pandas part 3](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/4097c9ca-a97a-44d0-9448-ee82fd67dd61)
![pergunta 4  homem pandas part 4](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/c86f871d-8c1f-4690-b816-1cf4144aae57)

<br>

![pergunta 4  homem sql part 1](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/ecec8d01-03d1-46ad-b0f8-4bd0b5a23d94)
![pergunta 4 homem sql part 2](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/7251f2e1-0343-4193-b075-4d22bb69685e)

**De acordo com o dados, foi visto que o público masculino adulto, usuários maiores de 25 anos, compram mais itens em relação aos jovens e possuem um gosto na escolha dos itens diferentes!**

**Os adultos costumam comprar mais joias e calças, enquanto que os jovens costumam comprar, principalmente, sueters e saias, sendo este como um possivel presente para, mãe, irmã ou namorada!**

<br>

4.2 Em relação às usuárias femininas:

![pergunta 4 mulher part 1](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/58951767-a3b6-41af-8d53-5ec06114bfba)
![pergunta 4 mulher part 2](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/4536b5dc-a071-4356-8034-7ea9cc2bbe3f)

<br>

![pergunta 4 mulher sql part 1](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/cbf469bd-069c-4c1e-aaed-34f6a778e1fe)
![pergunta 4 mulher sql part 2](https://github.com/LucasJMFreire/Projeto_Comportamento_Consumidor_PandaSQL/assets/108015773/a6de6d65-0bb7-4aeb-9965-e5db78780e96)

**De acordo com o dados, foi visto que o público feminino adulto, usuárias maiores de 25 anos, compram mais itens em relação às jovens e possuem um gosto na escolha dos itens diferentes!**

**As adultas costumam comprar mais blusas e saias, enquanto que as jovens costumam comprar, principalmente, shorts, tênis e sueters e blusas!**

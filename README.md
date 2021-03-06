# Project 2.1: Data Cleanup

## Passo 1: Entendimento do Negócio e dos Dados

Forneça uma explicação das principais decisões que precisam ser feitas. (Limite de 250 palavras)
Decisões Chave:
Responda estas perguntas

1.	Que decisões devem ser tomadas?

Uma rede líder de pet shops localizada no estado de Wyoming, chamada Pawcity, tem necessidade de um estudo sobre onde abrir a 14ª loja da rede.

2.	Que dados são necessários para subsidiar essas decisões?

Para obtermos resultados satisfatórios no estudo, precisamos de informações para incluirmos na modelagem do projeto. Precisamos de informações como: população total das cidades do estador de Wyoming, as vendas das lojas Pawcity por cidade, vendas dos competidores, número de casas com pessoas com menos de 18 anos, tamanho das áreas, densidade populacional e total de famílias por cidades. Estas informações são cruciais para entendermos o tamanho das cidades, tamanhos das famílias, propensão a consumir produtos de petshop e entendermos as nossas vendas x competidores por cada uma das variáveis a serem analisadas.

## Passo 2: Construindo o Conjunto de Treinamento

Construa seu conjunto de treinamento dado os dados fornecidos a você. As somas de coluna do seu conjunto de dados devem corresponder às somas na tabela abaixo.

Além disso, forneça as médias do seu conjunto de dados aqui para ajudar os revisores a verificar o seu trabalho. Você deve arredondar até duas casas decimais, ex: 1.24

![table1](https://user-images.githubusercontent.com/34245933/50059977-ec12cd00-0174-11e9-920b-5bbfba2edc0d.PNG)

## Passo 3: Tratando os Outliers

Responda estas perguntas

Existem cidades que são outliers no conjunto de treinamento? Qual outlier você escolheu para remover ou imputar? Como esse conjunto de dados é um conjunto de dados pequeno (11 cidades), você deve apenas remover ou imputar um outlier. Explique o seu raciocínio.

![scatterplots](https://user-images.githubusercontent.com/34245933/50060132-d9999300-0176-11e9-902a-42581190f513.PNG)

Analisando os resultados obtidos pelos scatterplots acima, vemos que as cidades de Cheyenne e Gillette são outliers, pois seus números de vendas são muito maiores em relação às outras cidades. Cheyenne podemos ignorá-la pois os dados são de uma cidade grande e não influenciam nos demais resultados. Enquanto isso, eu excluiria Gillette por conta que apenas a variável de vendas é outlier, com isso a cidade não tem característica de uma cidade grande, portanto influenciaria nos demais resultados, podemos considerá-la como anormal.

Antes de enviar
Por favor, verifique suas respostas contra os requisitos do projeto ditados por esta rubrica usada pelos revisores para classificar seu projeto.

## Fluxo Alteryx

![alteryx workflow](https://user-images.githubusercontent.com/34245933/50060157-3a28d000-0177-11e9-892f-d8eba2df6f27.PNG)

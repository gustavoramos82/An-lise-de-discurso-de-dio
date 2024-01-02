# Análise Inicial

Nesta etapa mais inicial será feito apenas uma filtragem dos texto em que apresentam um discurso de ódio e os que não apresentam e fazer uma comparação entre eles.

Se compararmos a quantidade, veremos que temos muito textos sem discurso de ódio do que com discurso, temos então que este dataset é desbalanceado e tratativas acerca disso 
deve ser tomadas caso seja utilizado um modelo de classificação

![image](https://github.com/gustavoramos82/An-lise-de-discurso-de-dio/assets/39843884/f3340032-ca94-44ed-890e-9957d4732ffe)


## Nuvem de palavras

Fazendo uma nuvem de palavras temos que uma certa diferença se fomros comparar

1) Nuvem de palavras de discurso sem ódio

![image](https://github.com/gustavoramos82/An-lise-de-discurso-de-dio/assets/39843884/a482638e-d606-4835-9bd2-0486a8d5c6d8)


2) Nuvem de palavras de discurso com ódio

![image](https://github.com/gustavoramos82/An-lise-de-discurso-de-dio/assets/39843884/9a389dab-fa1f-43f3-a8ff-ae10f64bd725)

Se comparamos as duas nuvem de palavras tem palavras mais gerais como think, callç entre outrso, agora se fomos ver do discurso de ódio fuck é o termo mais destacado da nuvem,
sendo que slut é o termo em comum entre os dois, necessitando de uma análise mais semântica para ver qual contexto slut é utilizado nas difrentes situações

## Frequência dos termos

Isso aparece também quando vamos verificar quais o termo que aparece mais

1) Frequência de termos dos discurso sem ódio

![image](https://github.com/gustavoramos82/An-lise-de-discurso-de-dio/assets/39843884/60650a61-b21d-4e23-85f6-eb86a3f7754b)

2)  Frequência de termos dos discurso com ódio

![image](https://github.com/gustavoramos82/An-lise-de-discurso-de-dio/assets/39843884/4f893b88-cf28-4d7f-9d57-61fc398dadab)

Podemos ver que fuck aparecem em grande parte dos textos com discurso de ódio se comparado ao que não tem, mostrando que esse termo noi termo há uma grande possibilidade do textio
ser um conteudo com discurso de ódio

## Próximos passos

A partir dessa análise inicial foi feita uma separação do dataset um com os discurso de ódio e outro sem para fazer uma análise separada e depois comparar os resultados
e também fazer uma análise de cluster ou uma analise mais aprofundada dos termos para avaliar quai termos se relaciona com qual.

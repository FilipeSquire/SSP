# SSP
 Analysis of São Paulo Police Criminal Data

This dataset is about crime data in São Paulo City Brazil. I've scraping this data in SSP (Secretária de Segurança Pública) website. SSP is a government agency of public security in São Paulo state. A observation, São Paulo city is capital of state the of São Paulo, equal in Rio de Janeiro.
Although I've got this data from SSP, probably these numbers doesn't match with real situation, because the process to make a B.O (police report) is bureaucratic, slow and many times the brazilian laws is so freak, that allows little crimes like picking has not been reported. Besides that the SSP data doesn't provide information about crimes by neighborhood/Streets, this is a problem when analyzing violence in São Paulo, because São Paulo has specific details that makes a difference when looking into crime data, for example: Morumbi neighborhood (is the most expensive neighborhood in São Paulo, with mansions, richest families and big houses, but in some streets in this neighborhood happen many violent thefts with assault riffles, and it is considered one of most dangerous neighborhoods in São Paulo), and there are the favelas which are controlled by PCC (its a mafia/organization that controls most São Paulo favelas), and they impose their rules throughout their territory, crimes that happens within the favelas are judged by PCC.

# Context 

This dataset contains criminal data per neighborhood of São Paulo's City in Brazil. São Paulo is the financial heart of Latin America and is one of the biggest cities in the world, and for being a big city within an in development-country it also has many flaws related to it's inequality, crime rates and poor education.
The objective of this analysis is to understand the distribution of the crime rate throughout the city and it's changes through time.
* What are the most dangerous neighborhoods in São Paulo?
* What are the most growing crime categories from 2019 to 2020?
* What kind of application could be developed using this data?

# Data Understanding

We have 15 .csv files captured from the Kaggle dataset, but some of these not gonna be necessary in order to answer the questions made before. 
Another problem when we look into these files is that their names and columns probabily are in portuguese and along our analysis I'll have to translate the data in order for this analysis to be understandable to the international community. 

1. Crimes em Sao Paulo Capital 2020 e 2021
2. Duvidas razoaveis ou morte provocada Data SSP
3. Encontro de cadver sem leses aparentes Data SSP
4. Endereco das delegacias
5. Feminicidio Data SP
6. Furto de celular Data SSP
7. Furto de Veiculo Data SSP
8. Homicidio Doloso Data SSP
9. Latrocinios Data SSP
10. Leso corporal seguida de morte Data SSP
11. Morte Acidental Data SSP
12. Morte decorrente de interveno Policial
13. Morte subida e natural SSP
14. Registro de Obitos IML Data SSP
15. Roubo de Veiculo Data SSP

In order to answer the questions we basically need mainly the criminal data per neighborhood and their categories. Therefore the data that we'll be using is:

1. Feminicidio Data SP (Female Murders)
2. Furto de celular Data SSP (Cellphone theft)
3. Furto de Veiculo Data SSP (Vehicle theft)
4. Homicidio Doloso Data SSP (Intentional Murder)
5. Latrocinios Data SSP (Theft followed by murder)
6. Leso corporal seguida de morte Data SSP (Injury followed by murder)
7. Roubo de Veiculo Data SSP (Vehicle Theft at Gunpoint)

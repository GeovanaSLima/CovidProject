# Project Covid-19
Estudo criado para desenvolvimento de habilidades em análise e manipulação de dados.


<p align="center"><img src="https://github.com/GeovanaSLima/CovidProject/blob/main/Covid1.png"></p>

[Clique aqui](https://github.com/GeovanaSLima/CovidProject/blob/main/Estudo_sobre_o_COVID.ipynb) para ir ao *notebook* do projeto. 

[Clique aqui](https://www.learningdata.dev/post/estudo-sobre-o-covid19) para ir ao artigo do projeto.

<br>


# Dados sobre o COVID-19

Todos as informações utilizadas no projeto foram retiradas do *dataset* completo criado e administrado pelo *[Our World in Data](https://ourworldindata.org/coronavirus)*. Todos os dados são atualizados diariamente e podem ser encontrados [neste repositório](https://github.com/owid/covid-19-data/tree/master/public/data) ou pelos links abaixo.

### 🗂️ **Download do dataset completo: [CSV](https://covid.ourworldindata.org/data/owid-covid-data.csv) | [XLSX](https://covid.ourworldindata.org/data/owid-covid-data.xlsx) | [JSON](https://covid.ourworldindata.org/data/owid-covid-data.json)**

Abaixo temos uma lista das informações contidas no *dataset*.

Metrics |	Source | Updated | Countries
------- | ------ | ------- | ---------
Vaccinations | Official data collated by the Our World in Data team | Daily | 217
Tests & positivity | Official data collated by the Our World in Data team | Weekly | 136
Hospital & ICU | Official data collated by the Our World in Data team | Weekly | 34
Confirmed cases | JHU CSSE COVID-19 Data | Daily | 194
Confirmed deaths | JHU CSSE COVID-19 Data | Daily | 194
Reproduction rate | Arroyo-Marioli F, Bullano F, Kucinskas S, Rondón-Moreno C | Daily | 184
Policy responses | Oxford COVID-19 Government Response Tracker | Daily | 186
Other variables of interest | International organizations (UN, World Bank, OECD, IHME…) | Fixed | 240

*Obs.: Informações retiradas do repositório oficial do Our World in Data.*

## Os dados que você irá encontrar no *dataset*

> * Casos e mortes confirmadas: nossos dados vêm do Repositório de Dados sobre o COVID-19 do Center for Systems Science and Engineering (CSSE) da Universidade Johns Hopkins (JHU). Nós discutimos como e quando a JHU coleta e publica os dados aqui. O cases & deaths dataset é atualizado diariamente. Nota: o número de casos ou mortes reportados por qualquer instituição – incluindo JHU, o WHO, ECDC, entre outros – em qualquer dia, não necessariamente representa o número exato naquela data. Isso, por conta da longa cadeia de comunicação que existe entre um novo caso/morte e sua inclusão na estatística. Isso também significa que valores negativos em cases & deaths podem aparecer quando países corrigem os dados históricos por terem sobrestimado os números. Alternativamente, grandes mudanças podem ser feitas em toda a série de um país caso a JHU decida corrigir os valores retrospectivamente.
>
> * Hospitalização e entrada em unidade de tratamento intensivo (UTI): Nossos dados vêm do European Centre for Disease Prevention and Control (ECDC) para um seleto número de países europeus. Também foram utilizados dados dos governos das Nações Unidas, Estados Unidos, Canadá, Israel e Argélia. Infelizmente não foi possível disponibilizar dados de hospitalização de outros países: atualmente não existe uma base de dados global sobre hospitalizações por conta do COVID-19, e nosso time do Our World in Data não tem a capacidade de construir um.
>
> * Teste de COVID-19: Esses dados são coletados pelo time do Our World in Data a partir de relatórios oficiais. Você pode encontrar mais detalhes no nosso post sobre testes de COVID-19, incluindo nosso checklist de questões para entender dados de testes, informações de cobertura geográfica e temporal e informações detalhadas de país para país. O dataset de teste é atualizado duas vezes por semana.
>
> * Vacinação contra o COVID-19: Esses dados são coletados pelo time do Our World in Data a partir de relatórios oficiais.
>
> * Outras variáveis: Esses dados são coletados de uma variedade de fontes (Nações Unidas, World Bank, Global Burden of Disease, Blavatnik School of Government, etc.). Para mais informações, acesse nosso codebook.
> 
> *Obs.: Tradução livre*

<br>

**Para mais informações sobre a forma de extração e tratamento das variáveis, acesse o [repositório](https://github.com/owid/covid-19-data/tree/master/public/data) oficial do *Our World in Data*.**

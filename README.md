# Adaptaviz

<img width="1920" alt="Capture d’écran 2022-01-01 à 19 56 03" src="https://user-images.githubusercontent.com/28403617/147858065-bb7f4138-46f2-4a72-8ac4-e65be6c478fd.png">

## [www.adaptaviz.fr](https://www.adaptaviz.fr)

### 🇫🇷

Ce projet à été realiser par: [Mathieu Jouffroy](https://www.linkedin.com/in/mathieu-jouffroy/), [Gabriel Colas](https://www.linkedin.com/in/gabriel-colas-842250173/), [Clara Reichert](https://www.linkedin.com/in/clara-reichert0/), [Mai-Nhi Vo Van Tao](https://www.linkedin.com/in/mai-nhi-vo-van-tao/), [Samuel BOYER](https://www.linkedin.com/in/samuel-boyer-27724b158/), [Naïm Del Ben](https://www.linkedin.com/in/naimdb/) et [Othmane EL-AYADI](https://www.linkedin.com/in/othmane-el-ayadi/).

Adaptaviz est un outil d'aide à la décision. Il à été realiser lors du hackathon [Hacktaferme](https://www.hacktaferme.fr/) organisé par le Varenne agricole de l'eau et de l'adaptation au changement climatique.

Il permet d'estimer sur une parcelle qu'elles seront les cultures, légumes, céréales, légumineuses les plus adaptés au climat future.

Il se base sur trois projections climatiques par scénario d'émission de gaz à effet de serre, associer aux phénotypes des végétaux. Et ainsi pouvoir en sortir quelles sont les zones à risque et les nouvelles zones favorables d'une culture.

Le preneur de décision aura la possibilité de savoir s'il pourra maintenir ses cultures à l'avenir ou pouvoir anticiper ses changements de récolte.


### 🇺🇸

This project was realized by: [Mathieu Jouffroy](https://www.linkedin.com/in/mathieu-jouffroy/), [Gabriel Colas](https://www.linkedin.com/in/gabriel-colas-842250173/), [Clara Reichert](https://www.linkedin.com/in/clara-reichert0/), [Mai-Nhi Vo Van Tao](https://www.linkedin.com/in/mai-nhi-vo-van-tao/), [Samuel BOYER](https://www.linkedin.com/in/samuel-boyer-27724b158/), [Naïm Del Ben](https://www.linkedin.com/in/naimdb/) and [Othmane EL-AYADI](https://www.linkedin.com/in/othmane-el-ayadi/).

Adaptaviz is a decision support tool. It was realized during the [Hacktaferme](https://www.hacktaferme.fr/) hackathon of the Varenne agricole de l'eau et de l'adaptation au changement climatique.

It allows to estimate on a plot of land which crops will be the most adapted for future climate.
It is based on 3 climate projections of greenhouse gas emission and has 4 years of reference (today, 2050, 2075, 2100). Therefore the thermal and water stress scores are calculated from the the climate projections and the plant's phenotype. 
And thus to be able to get out of it which are the zones at risk and the new favorable zones of a culture.

The tool aims to help agricultors and regional politicians to anticipate if they were to maintain the production of a given crop or whether they should change the type of harvest given climate deregulation.


[Score calculations algorithms](https://github.com/owalid/adaptaviz/tree/main/score)


[Data used for the scores calculations](https://github.com/owalid/adaptaviz/tree/main/score/data_ref)


[Data used in the website](https://github.com/owalid/adaptaviz/tree/main/static/data)

## Build Setup

####  With node

```bash
# install dependencies
$ yarn

# serve with hot reload at localhost:3000
$ yarn dev
```

####  With docker

```bash
# Create volume
$ docker create volume adaptaviz_node_modules

# Build and run app
$ docker compose up
```

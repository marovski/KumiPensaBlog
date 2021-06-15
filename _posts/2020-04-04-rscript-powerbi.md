---
layout: post
title:  "Linguagem R no Power BI"
author: "Marovski"
lang: pt
lang-ref: r-power-bi
image: https://i.ytimg.com/vi/yF04SIXfKis/maxresdefault.jpg

---

![R + Power BI](https://i.ytimg.com/vi/yF04SIXfKis/maxresdefault.jpg)
<br>

_R_ é uma linguagem e um software livre criada em xxxx com objetivo de facultar uma variedade de técnicas e visualizações estatísticas, sendo uma das linguagens mais utilizadas atualmente para _Data Science_. Embora a sua área de utilização inicial foi a Estatística, esta, tem evoluído bastante para acompanhar o desenvolvimento de modelos de machine learning e data mining.

Power BI é o software mais utilizado mundialmente para _Business Intelligence_, agregando as funcionalidades do Excel e os seus suplementos (Power Pivot, Power Query, PowerMap, etc), sendo considerado por muitos um "_Excel on Steroids_". A verdade é que esta ferramenta poderosa permite obter dados de várias fontes, executar o processo de limpeza e transformação até à apresentação de visualizações de dados.

## Instalação

Para a utilização da linguagem R no ambiente do Power BI é necessário [descarregar](https://cran.r-project.org/bin/windows/base/) e instalar o mesmo na sua máquina.

## Configuração Power BI
 
 Para iniciar a utilização de scripts R no Power BI devemos então configurar o diretorio do R na sua máquina. Para isto, na área de trabalho do powerbi, vá para Ficheiro> Opções e configurações> Opções> Script R> Diretórios iniciais do R detectados> Outro e navegue até o local em que o R está instalado.

## Elaborar uma Script no R

Para a conceção da script no R que será posteriomente utilizado no Power BI, foi utilizado o Rstudio, um IDE para a linguagem, com uma interface bastante simples e intuitiva, que permite executar todas as tarefas inerentes à linguagem, desde instalação de pacotes à organização de ficheiros gerados pelo R, no entanto como alternativa pode-se utilizar um simples editor de texto para tal e executar o mesmo na consola do R.




No ambiente do Rstudio antes de criar o novo ficheiro _Rscript_ na consola teremos de instalar o package RJson para possibilitar a leitura do objeto JSON facultado pela API que iremos utilizar. Para isto, executaremos os seguintes comandos:

```
install.package("RSJSONIO")

```



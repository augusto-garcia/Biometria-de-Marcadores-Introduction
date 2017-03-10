--- 
title       : LGN 5830 - Biometria de Marcadores Genéticos
subtitle    : INTRODUÇÃO
author      : Antonio Augusto Franco Garcia (http://about.me/augusto.garcia)
job         : Departamento de Genética, ESALQ/USP (2017)
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : solarized_light    # era tomorrow
linenums    : true
widgets     : [mathjax, bootstrap, quiz]   # {mathjax, quiz, bootstrap}
mode        : selfcontained # {selfcontained, standalone, draft}
--- 

# Apresentações

## Responsável

- Antonio Augusto Franco Garcia

## Monitores

- João Ricardo B F Rosa
- Kaio O Graças Dias
- Felipe V Ferrão
- Marianella F Quezada Macchiavello
- Letícia A Castro Lara
- Rafael Storto Nalin

## Alunos e ouvintes

- Fale algo a seu respeito!

---

## Perfil heterogêneo...

- Buscamos excelência, alto nível de entendimento
- Literatura internacional
- **Genética Estatística (Statistical Genetics)** 

---

## Página na internet

[Biometria de Marcadores Genéticos](http://augusto-garcia.github.io/Biometria-de-Marcadores/)

---

## Conteúdo

- Mapas Genéticos
  - Tipos de marcadores: tradicionais e SNPs
  - Tipos de populações: RC, $F_2$, RILs, "outcrossing", DIII
  - Teste da segregação mendeliana
  - Análise de ligação (dois pontos, três pontos e multiponto)
  - Ordenação de locos

---

## Conteúdo (cont.)

- Mapeamento de QTL's
  - Análise de marcas individualmente
  - Mapeamento por Intervalo
  - Mapeamento por Intervalo Composto
  - Interação QTL x E
  - Mapeamento para Múltiplos Caracteres
  - Mapeamento de Múltiplos Intervalos
  - Modelos mistos e mapeamento

---

## Conteúdo (cont.)

- Mapeamento Associativo
  - Desequilíbrio de Ligação
  - Estrutura Populacional
  - Modelos de GWAS
- Seleção Genômica

---

## Conteúdo (cont.)

- Programas Principais
  - R
  - OneMap
  - R/qtl
  - QTLCartographer (eventual)
  - Outros (MAPMAKER/EXP, GenStat, ...)

---

# OneMap

## Muito usado, especialmente no exterior

- USP, UNICAMP, IAC, EMBRAPA
- CIAT, UC Davis, North Carolina State University, Duke University,
    Purdue University, Summer Institute in Statistical Genetics (UW),
    Kansas State Universiy, Universidad del Vale (Colombia),
    University of Missouri, UC Irvine, Chinese Academy of Fishery
    Sciences, Universidad de la Republica (Uruguay), USDA, University
    of California, Universitaet Hohenheim (Stuttgart, Germany),
    University of Texas, Technische Universität München, University of
    Stirling (Scotland), China Agriculture University, University of
    Georgia, New Zealand Institute for Plant and Food Research,
    University of Edinburgh, Université catholique de Louvain
    (Belgium), University of Oregon, Illinois State University, Orissa
    University of Agriculture and Technology (India), University of
    Chicago, CRA-GPG - Genomic Research Center, ...

---

## Livro - 2017

- ![libro](./figures/LosTresAmigos.jpg)
- Augustanis, Gabrieles, Marcelitcho

---

## Livro

![book](./figures/book.jpg)

---

## OneMap

- [CRAN](http://cran.r-project.org/web/packages/onemap/index.html)
- Purdue University
- Summer Institute in Statistical Genetics (Seattle, USA; Piracicaba,
  SP, Brazil).
- OneMap, versão experimental no
[github](https://github.com/augusto-garcia/onemap)


---

## Reprodutibilidade

- Dados experimentais (vídeos, que tal?)
- Web
- Códigos para analisar os dados
  - [FOAS](http://www.foastat.org/)
  - [ggvis](http://ggvis.rstudio.com/)
  - [QTL](http://kbroman.org/qtlcharts/)
  - html5

---

## Bagunça vs Reprodutibilidade

- Você arruma sua casa antes de receber visitas?
- Você gostaria que alguém repetisse as análises que você fez na sua
tese?
- E nos artigos já publicados?
  - (Fiz isso no meu pós-doc)

---

## Hoje temos muitas possibilidades

- Emacs + R + $BibTex$
- [RStudio](http://www.rstudio.com/): sensacional, impressionante
- [Código fonte](https://github.com/augusto-garcia/Biometria-de-Marcadores-Introduction) destes slides

--- plot

## R e html5


```r
library(ggplot2)
qplot(hp, mpg, data=mtcars)+geom_smooth() 
```

![plot of chunk md-cars-scatter](assets/fig/md-cars-scatter-1.png)

---

# Plano de Ensino

## Parte didática

- Monitores: disponíveis para ajudar
- Ensino Dedutivo vs Indutivo
  - Deductive approach: General rule $\rightarrow$ Specific examples
    $\rightarrow$ Practice
  - Inductive approach: Specific examples $\rightarrow$ Practice
  $\rightarrow$ General rule
  

--- .segue .dark .quote

<q class = 'yellow'> Tell me and I forget, <br />
Teach me and I remember, <br />
Involve me and I learn.
<br />

</q>

<br />

- Benjamin Franklin (1706-90)

---

## Comprometimento

- Responsabilidade: alunos produtivos, proativos, engajados
- Cientistas: eternos aprendizes

---

## Estratégia: uso da internet, computação

- Web 2.0, Tablets, Smartphones, $\ldots$
- Internet ``Social''
- Meu [Lab](http://statgen.esalq.usp.br)

---

## Estaremos sempre em contato!

- Fórum no
  [Google Groups](https://groups.google.com/forum/#!forum/forum-biomarc-2015)
- Lista de emails (enviarei convites)
- Página no [Google+](https://plus.google.com/u/0/communities/114505085464124213449)
- [Mendeley](http://www.mendeley.com/profiles/a-augusto-f-garcia)

---

## (SEMPRE em contato!)

<iframe width="854" height="510" src="https://www.youtube.com/embed/OMOGaugKpzs" frameborder="0" allowfullscreen></iframe>

---

## Diversos

- [Youtube](http://www.youtube.com/edu) (você conhece?)
- [WikiBooks](http://en.wikibooks.org)
- [Linear Algebra](https://www.youtube.com/results?search_query=gilbert+strang+linear+algebra)

---

## Statistical Genetics

- Sendo bem sincero, não é algo simples
- Poucos conceitos podem fazer uma grande diferença

<iframe width="854" height="510"
src="https://www.youtube.com/embed/5pidokakU4I?list=RD5pidokakU4I"
frameborder="0" allowfullscreen></iframe>

---

## Conceitos e Avaliação

###  Participação no curso é fundamental (incluindo Forum, Comunidades, etc)


-  Listas de exercícios com **prazos para entrega**
  - Não imprimir, mandar apenas em PDF para
      _biometriamarcadores@gmail.com_
  - Use o Google Docs ou o $LaTeX$ (Uôrdi queima o seu filme, mas é válido)
  - (Opção avançada: _knitr_ com RStudio)
  - Muitos exercícios serão respondidos no Fórum diretamente
- Formem grupos de trabalho, por afinidade, com até 4 pessoas

---

## Primeiras Tarefas (para 16/03/17):

- Entrar no Google+ (se possível, configure webcam)
  - Adicione-me como contato
  - Procure a comunidade _Biometria de Marcadores Genéticos_ e
    inscreva-se
  - Apresente-se na comunidade, dizendo sua área de afinidade, etc
- Crie uma conta no [Mendeley](http://www.mendeley.com/), configure seu perfil e adicione-me
- Crie uma conta no [Gravatar](http://pt.gravatar.com/) e, obviamente, insira sua foto
- Inscreva-se no [Fórum da disciplina](https://groups.google.com/forum/#!forum/forum-biometria-de-marcadores-2017)
- (Opcional: crie uma conta no [github](https://github.com) e adicione-me como contato)


---


```r
print(sessionInfo(), locale = FALSE)
```

```
## R version 3.3.2 (2016-10-31)
## Platform: x86_64-pc-linux-gnu (64-bit)
## Running under: Ubuntu 16.04.2 LTS
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
## [1] slidify_0.5   knitr_1.15.1  ggplot2_2.2.1
## 
## loaded via a namespace (and not attached):
##  [1] Rcpp_0.12.8      codetools_0.2-15 digest_0.6.12    assertthat_0.1  
##  [5] grid_3.3.2       plyr_1.8.4       gtable_0.2.0     magrittr_1.5    
##  [9] evaluate_0.10    scales_0.4.1     highr_0.6        stringi_1.1.2   
## [13] lazyeval_0.2.0   whisker_0.3-2    labeling_0.3     tools_3.3.2     
## [17] stringr_1.1.0    munsell_0.4.3    markdown_0.7.7   yaml_2.1.14     
## [21] compiler_3.3.2   colorspace_1.3-2 tibble_1.2
```

--- bg:#fee6ce

<q>OBRIGADO!</q>



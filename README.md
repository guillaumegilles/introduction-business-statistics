## Materials

### R/Stats Books

## Quelle est la différence entre erreur d’estimation et erreur de prévision ?

Une **erreur d’estimation** est une erreur lors de la phase d’entraînement
du modèle. (biais) ; alors que l’**erreur de prévision**, c’est une erreur
du modèle pendant la phase de test (variance).

## Clustering

> [!NOTE]
> Faire attention aux ordres de grandeurs des différentes variables. Si
> les ordres de grandeurs sont différentes, le calcul des distances sera
> donc **faux**

1. [Tidy Modeling with R](https://www.tmwr.org/)
2. [R for Data Science](https://r4ds.hadley.nz/intro)
3. R pour la science des données + Régression Linéaire
4. [Tidy Design Pinciples](https://design.tidyverse.org/)
5. [Tidyverse style guide](https://style.tidyverse.org/syntax.html#comments)
5. [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/)
5. [Hands-On Programming with R | 5 - R Objects](https://rstudio-education.github.io/hopr/r-objects.html#lists)
6. [Advanced R](https://adv-r.hadley.nz/)
7. [R Manuals :: An Introduction to R](https://rstudio.github.io/r-manuals/r-intro/)
8. [Flexible Imputation of Missing Data]( https://stefvanbuuren.name/fimd/)
9. [Mastering Shiny](https://mastering-shiny.org/index.html)
10. [R Packages](https://r-pkgs.org/)

- Kuhn, M, and K Johnson. 2013. Applied Predictive Modeling. Springer.
- ———. 2020. Feature Engineering and Selection: A Practical Approach for Predictive Models. CRC Press.
- [ ] [Maîtrisez les bases des probabilités](https://openclassrooms.com/fr/courses/4525296-maitrisez-les-bases-des-probabilites)
- [ ] [Khan Academy](https://www.khanacademy.org/math/ap-statistics)
- [ ] [OpenIntro](https://www.openintro.org/)
- [ ] [Introductory Statistics 2e](https://openstax.org/details/books/introductory-statistics-2e?Book%20details)
- [ ] [Statistical Computing](https://www.stephaniehicks.com/jhustatcomputing2021/)
- [ ] processus stochastic miage
- [ ] [Qu’est-ce que la Variance ?](https://kobia.fr/quest-ce-que-la-variance/)
- [ ] [Openclassroom](https://openclassrooms.com/fr/partners/ensae-ensai-formation-continue-cepe)
- [ ] [Statistics How To](https://www.statisticshowto.com/)
- [ ] Cassie Kozyrkov:
  - https://www.youtube.com/@kozyrkov
  - https://kozyrkov.medium.com/
  - https://github.com/kozyrkov/
- [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/)
- [Fundamentals of data visualization](https://clauswilke.com/dataviz/index.html)
- https://ledaliang.github.io/journalclub/

## TODOs

- [ ] Embedded shiny app into a webpage pour faire les QCM



## The purpose of a descriptive model is to describe or illustrate characteristics of some data


The analysis might have no other purpose than to visually emphasize
some trend or artifact in the data [@978-1492096481kuhnTidyModeling2022].

Organizing and summarizing data is called descriptive [[statistics]]. Two ways to summarize data are by graphing and by using numbers (for example, average) [@illowskyIntroductoryStatistics2e2023].





# Is statistics accurate?

One of the main concerns in the field of [[statistics]] is how accurately a
statistic estimates a [[statistics.parameter]]. The accuracy really depends on
how well the [[satistics.sample]] represents the [[statistics.population]]. The sample
must contain the characteristics of the population in order to be a
representative sample. We are interested in both the sample statistic and the
population parameter in [[inferential-statistics]].

title: Confidence Interval
desc: ''
updated: 1729068716853
created: 1729068716853
isDir: false
id_imported: uht8fj4ip4p6cxelxy5241r
title_imported: intervalle de confiance
desc_imported: L’intervalle de confiance est une marge d’erreur en statistique
updated_imported: 1710920956672
created_imported: 1670270096489
---

## Objectif d'un intervalle de confiance

En mathématiques, cette notion permet de définir une marge d'erreur entre les
résultats d'un sondage et un relevé exhaustif de la population totale.

### Comment le calculer

## Références

- [Wikipédia FR](https://fr.wikipedia.org/wiki/Intervalle_de_confiance)
- [Wikipadia EN](https://en.wikipedia.org/wiki/Confidence_interval)

# Density Curve
desc: ''
updated: 1729068716853
created: 1729068716853
isDir: false
id_imported: o9dqljpvn7a9mi21f4dta52
title_imported: Density Curve
desc_imported: ''
updated_imported: 1706085691901
created_imported: 1706085665922
---

# [Density curves](https://www.khanacademy.org/math/ap-statistics/sampling-distribution-ap/xfb5d8e68:the-normal-distribution-revisited/e/probability-normal-density-curves)

Different dealers may sell the same car for different prices. The sale prices for a articular car are normally distributed with a mean and standard deviation of $26$ thousand dollars and $2$ thousand dollars, respectively. Suppose we select one of these cars at random. Let $X =$ the sale price (in thousands of dollars) for the selected car. Find
$P(X > 25)$.

$$P(X > K)=P(z > \dfrac{K - \mu_X}{\sigma_X})$$

As a result,

$$P(X > 25) = P(z > \dfrac{25 - 26}{2})$$

$$= P(z > -0.5)$$

$$= 1 - P(z < -0.5)$$

$$\approx 1-0.3085 ~~~~\text{(from table)}$$

$$\approx0.6915$$

title: Glissement
desc: ''
updated: 1729068716853
created: 1729068716853
isDir: false
id_imported: vvr8is7a70ikxoas17ol9eb
title_imported: évolution en glissement
desc_imported: ''
updated_imported: 1682455381654
created_imported: 1646689804175
---

Une **évolution en glissement** compare deux valeurs séparées par une période de temps, généralement un trimnestre ou un an. La notion de glissement s'applique en général à des grandeurs qui ont la dimension d'un [[stock|mathématiques.statistiques.stock]], c'est à dire qu'elles sont mesurables à un instant donné.

Par exemple, le _glissement annuel_ d'une valeur à un trimestre T correspond au taux d'évolution (en %) obtenu en rapportant le niveau de la variable en T à son niveau au même trimestre de l'année précédente (T-4).

$$
(T - (T-4)/(T-4)) * 100
$$

Lorsque la variable est mensuelle, le glissement annuel rapporte le niveau atteint un mois donné à celui du même mois, un an auparavant, par exemple décembre 2020 par rapport à décembre 2019.

Le _glissement trimestriel_ est obtenu en rapportant le niveau de la variable en T à son niveau au trimestre précédent (T-1).

$$
(T - (T-1)/(T-1)) * 100
$$

> Attention, il faut être vigilant à ne pas confondre évolution en glissement annuel et [[mathématiques.statistiques.glissement]]. Une phrase telle que « En 2006, l'emploi salarié a augmenté de... » peut avoir deux significations :
>
> 1. On parle de la moyenne de l'emploi salarié au cours de l'année 2006 par rapport à la moyenne de 2005;
> 2. Ou bien, on compare, en glissement annuel, la situation au 31 décembre 2006 par rapport au 31 décembre 2005.

---

### Source(s) :

- [INSEE](https://www.insee.fr/fr/metadonnees/definition/c1373)


Une **évolution en moyenne annuelle** compare la moyenne d'une année à la moyenne de l'année précédente. On doit être vigilant à ne pas confondre avec les [[statistics.glissement]].

L'évolution en moyenne est plus pertinente pour des grandeurs qui ont la dimension d'un [[flux|statistics.stock]].

---

### Source(s) :

- [INSEE](https://www.insee.fr/fr/metadonnees/definition/c1373)

### title: Panel Data
desc: ''
updated: 1733779559670
created: 1729068716853
---

In statistics and econometrics, _panel data_ and longitudinal data are both
multi-dimensional data involving measurements over time. Panel data is a subset
of longitudinal data where observations are for the same subjects each time.

Panel data is also a time based dataset.

The difference is that, in addition to time series, it also contains one or more
related variables that are measured for the same time periods.

Typically, the columns present in panel data contain explanatory variables that
can be helpful in predicting the Y, provided those columns will be available at
the future forecasting period.

title: Secret
desc: ''
updated: 1729068716853
created: 1729068716853
isDir: false
id_imported: bprh6jbal2snczdrmbnny1f
title_imported: Secret statistique
desc_imported: ''
updated_imported: 1702851604853
created_imported: 1670270445160
---

## Objectif du secret statistique

Le secret statistique garantit le respect (1) de la confidentialité due à la vie privée, personnelle et familiale, pour les personnes physiques et (2) du secret commercial et des affaires, pour les entreprises.

### Pour les entreprises

Pour les données relatives aux entreprises, aucun résultat publié ne concerne **moins de trois entreprises ou établissements**. De plus, aucun résultat n’est diffusé quand une entreprise ou un établissement **contribue à lui seul à plus de 85 % de ce résultat**.

### Pour les particuliers

Pour les particuliers, les données publiées à partir des enquêtes et du recensement de la population **ne doivent pas permettre une identification ni directe ni indirecte** des répondants et de leurs réponses. 

## Références

- [Loi n° 51-711 du 7 juin 1951 sur l'obligation, la coordination et le secret en matière de statistiques](https://www.legifrance.gouv.fr/loda/id/JORFTEXT000000888573)
- [Secret statistique](https://www.insee.fr/fr/information/1300624)



# K-nearest neighbors

We will build a classification model using the "K-nearest neighbors" strategy. To predict the target of a new sample, a k-nearest neighbors takes into account its k closest samples in the training set and predicts the majority target of these samples.

## Références

- https://lms.fun-mooc.fr/courses/course-v1:inria+41026+session03/courseware/ea2a140204de4e7fbc316fd96a163c7f/f5a3613d45224fde86a195e91223961d/

###################################

# The `fit` method is called to train the model from the input (features) and target data.

```python
from sklearn.neighbors import KNeighborsClassifier

model = KNeighborsClassifier()
_ = model.fit(data, target)
```

<png>

The method `fit` is composed of two elements: (i) a learning algorithm and (ii) some model states. The learning algorithm takes the training data and training target as input and sets the model states. These model states will be used later to either predict (for classifiers and regressors) or transform data (for transformers).

Both the learning algorithm and the type of model states are specific to each type of model.

## Références

- https://lms.fun-mooc.fr/courses/course-v1:inria+41026+session03/courseware/ea2a140204de4e7fbc316fd96a163c7f/f5a3613d45224fde86a195e91223961d/

###################################

# Let's use our model to make some predictions using the same dataset.

```python
```

title: Stock
desc: ''
updated: 1729068716853
created: 1729068716853
isDir: false
id_imported: 80tn1xcuurdywjdj5c5li1k
title_imported: Différence entre un stock et un flux
desc_imported: ''
updated_imported: 1710347608451
created_imported: 1646691915267
---

La définition d’un stock et d’un flux est assez simple lorsqu’on imagine une
baignoire. Le **stock** est le niveau d’eau dans la baignoire, c’est à dire le
solde à un instant donné. Alort que les **flux** sont l’eau s’écoulant du
robinet (flux entrant) et l’eau s’écoulant du siphon (flux sortant).

On comprend très vite que le stock est une notion statique dans le temps ; le
niveau d’eau dans la baignoire ne peut être mesuré qu’à un instant T. À
l’inverse, le flux possède une dimension temporelle ; c’est la somme des flux
entrants et sortants pendant une période.

title: Univariate
desc: ''
updated: 1729068716854
created: 1729068716854
isDir: false
id_imported: 9o93nv4a5swr63rw73p6tij
title_imported: statistiques descriptives univariées
desc_imported: analyse univariée de données
updated_imported: 1702851473347
created_imported: 1682366426488
---

## variables quantitatives (_continuous_)

- **central tendancy**: mean, mode, median, max, min
- **dispersion**: spread of values arounf a central tendancy
  - mean +- SD
- histogram, box plot
- range, standard deviation, variance
- skewness

## variables qualitative (_categorical_)

- pie chart / bar chart
- **frequency distribution**: count in numbers and %

| Défaillance |   #    |  %  |
| :---------: | :----: | :-: |
|     `0`     | 874325 | 99% |
|     `1`     |   67   | 1%  |

title: Z Score
desc: ''
updated: 1729068716854
created: 1729068716854
isDir: false
id_imported: x4751rxouv8rjoeyyq62icg
title_imported: Z Score
desc_imported: ''
updated_imported: 1706123357346
created_imported: 1706123352823
---

A z-score is an example of a standardized score. A z-score measures how many standard deviations a data point is from the mean in a distribution.

https://www.khanacademy.org/math/ap-statistics/density-curves-normal-distribution-ap/measuring-position/v/z-score-introduction

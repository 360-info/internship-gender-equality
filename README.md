
# The journey towards women's legal empowerment

For the past 47 years, International Women's Day has been celebrated worldwide on the 8th of March. It honours women's social, economic, cultural, and political achievements. The day also serves as a rallying cry for greater gender equality. Although the past decades have been significant progress for women's and girls' rights. Overall, though, progress has been uneven and slow. The worldwide gender gap will not close for another 100 years at the current rate of progress. Women's rights are human rights, the Convention on the Elimination of All Forms of Discrimination Against Women was adopted 40 years ago, however, discrimination is still prevalent in law and practise, women and girls have fewer access to resources and opportunities and are under-represented in decision-making at all levels. Over the last decades, 131 countries have added 274 gender-related reforms to their laws and regulations, yet it is projected that more than 2.5 billion women and girls live in countries with at least on discriminatory law (UnitedNations, n.d.). It is the purpose of this project to examine the journey towards women's legal empowerment.

![Source: The World Bank](figures/gender.png)

## Use + Remix rights

![[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0)](https://mirrors.creativecommons.org/presskit/buttons/80x15/png/by.png)

These charts, as well as the analyses that underpin them, are available under a Creative Commons Attribution 4.0 licence. This includes commercial reuse and derivates.

<!-- Do any of the data sources fall under a different licence? If so, describe the licence and which parts of the data fall under it here! if most of it does, change the above and replace LICENCE.md too -->

Data in these charts comes from:

* World Bank 
  * [Women, Business and the Law Data Portal](https://wbl.worldbank.org/en/wbl-data)
  * [Overall Global Gender Gap Index Portal](https://tcdata360.worldbank.org/indicators/af52ebe9?country=BRA&indicator=27959&viz=line_chart&years=2006,2021)
  * [Gender Portal](https://data.worldbank.org/topic/gender)
* [V-Dem (Varieties of Democracy by University of Gothenburg)](https://www.v-dem.net/vdemds.html)
  

**Please attribute 360info and the data sources when you use and remix these visualisations.**

## Reproduce the analysis

We typically publish graphics using [Quarto](https://quarto.org) notebooks, which can be found in the`*.qmd` files. Quarto allows reproducible analysis and visualisation to be done in a mix of languages, but we typically use [R](https://r-project,.org) and [Observable JS](https://observablehq.com/@observablehq/observables-not-javascript).

You'll need to:
- [Download and install Quarto](https://quarto.org/docs/get-started)
- [Download the install R](https://www.r-project.org)
- Satisfy the R package dependencies. In R:
  * Install the [`renv`](https://rstudio.github.io/renv) package with `install.packages("renv")`,
  * Then run `renv::restore()` to install the R package dependencies.
  * (For problems satisfying R package dependencies, refer to [Quarto's documentation on virtual environments](https://quarto.org/docs/projects/virtual-environments.html).)

Now, render the `.qmd` files to the `/docs` directory with:

```sh
quarto render --output-dir docs *.qmd
```

## Help

<!-- replace `report-template` with the name of this repo in the link below  -->

If you find any problems with our analysis or charts, please feel free to [create an issue](https://github.com/360-info/report-template/issues/new)!








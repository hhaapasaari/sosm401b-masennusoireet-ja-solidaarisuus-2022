## Masennusoireiden jatkuvuuden suhde sosiaaliturvan solidaarisuuskäsityksiin suomenkielisillä mannersuomalaisilla vuonna 2022

Projekti on osa Helsingin yliopiston sosiaalitieteiden maisteriopintojen kurssityötä, joka käsittelee koetun masentuneisuuden jatkuvutta ja siihen liittyvien kokemusten suhdetta ihmisten käsityksiin Suomen sosiaaliturvan tasapuolisuudesta ja solidaarisuudesta. Analyysissä on käytetty Mikko Niemelän (2025) FSD3999 Hyvinvointi ja eriarvoisuus Suomessa 2022 kyselytutkimusaineistoa.

Tutkimuskysymykset:
1. **Miten masentuneisuuden kokemukset selittävät käsityksiä sosiaaliturvan solidaarisuudesta ja tasa-arvosta?**
2. **Miten eri kulttuuriset, taloudelliset ja sosiaaliset tekijät vaikuttavat masennus oireiden jatkuvuuden ja sosiaaliturvan solidaarisuuskäsityksen yhteyteen?**


## Scriptit

Tulokset on toistettavissa suorittamalla /code/ hakemiston .rmd kooditiedostot seuraavassa järjestyksessä:

1. 01_aineston_kasittely.rmd
2. 02_faktorianalyysi_ja_summamuuttuja.rmd
3. 03_regressio_analyysit.rmd
4. 04_kuviot_ja_taulukot.rmd
5. 05_diagnostiikka.rmd

## Aineisto

Niemelä, Mikko. (2025). Hyvinvointi ja eriarvoisuus Suomessa 2022 (Versio 1.0) [Dataset]. Yhteiskuntatieteellinen tietoarkisto [jakaja]. https://doi.org/10.60686/t-fsd3999

## Ohjelmisto ja paketit

Tilastollinen analyysi on suoritettu R-ohjelmointikoodilla ja Rstudio -ohjelmointiympäristöllä hyödyntäen seuraavia paketteja ja versioita:

R version 4.5.2 (2025-10-31 ucrt) 

brant (0.3-0)
modelsummary (2.5.0)
here (1.0.2)
sostieteidentaulukointityylit (0.1.1)
writexl (1.5.4)
broom (1.0.10)
lm.beta (1.7-2)
psych (2.5.6)
janitor (2.2.1)
haven (2.5.5)
lubridate (1.9.4)
forcats (1.0.1)
stringr (1.6.0)
dplyr (1.1.4)
purrr (1.2.0)
readr (2.1.5)
tidyr (1.3.1)
tibble (3.3.0)
ggplot2 (4.0.0)
tidyverse (2.0.0)
MASS (7.3-65)

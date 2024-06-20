# Predikcija broja poena igrača Eurolige

## Opis projekta

Ovaj projekat ima za cilj predikciju broja poena koje igrači Eurolige postižu na utakmici. Korišćenjem različitih skupova podataka koji sadrže statistike igrača, timske statistike i kvote bukmejkera, razvio sam model koji pruža tačne predikcije poena. Projekat takođe testira primenu modela za potrebe klađenja, nudeći potencijalne uvide za bukmejkere i kladioničare.

## Opis korišćenog skupa podataka

Koristio sam nekoliko skupova podataka za izradu i testiranje ovog prediktivnog modela:
 
1. **Euroliga skupovi podataka sa Kaggle-a:**
   - [Euroliga skupovi podataka](https://www.kaggle.com/datasets/babissamothrakis/euroleague-datasets)
   - **euroleague_alltime.csv**: Ova tabela sadrži informacije o imenima igrača i njihovim pozicijama u timu.
   - **euroleague_box_score.csv**: Ova tabela pruža detaljne statistike učinka pojedinačnih igrača na svakom meču.
   - **euroleague_header.csv**: Ova tabela uključuje sveobuhvatne statistike učinka timova na svakom meču.

2. **Prilagođeni skup podataka:**
   - **granice_igraci.csv**: Tabela koju sam sam kreirao, a koja sadrži imena igrača sa određenih mečeva i njihove granice poena određene od strane bukmejkera. Ovaj skup podataka služi kao dodatna karakteristika za naš model, potencijalno poboljšavajući njegovu tačnost i relevantnost za klađenje.

## Struktura Projekta

Repozitorijum je strukturiran na sledeći način:

- **data/**: Sadrži skupove podataka korišćene u projektu.
- **figures/**: Sadrži slike i grafike generisane tokom analize.
- **organized_data/**: Sadrži sačuvane tabele kreirane tokom rada programa.
- **README.md**: Ovaj fajl, koji pruža pregled projekta.

Repozitorijum takođe sadrži sledeće Jupyter notes fajlove:

- **01_data_exploration.ipynb**: Istraživanje i sređivanje podataka.
- **02_regression_model.ipynb**: Kreiranje i testiranje regresionog modela.
- **03_betting_test_regression.ipynb**: Testiranje klađenja korišćenjem regresije.
- **04_betting_test_classification.ipynb**: Testiranje klađenja korišćenjem klasifikacije.


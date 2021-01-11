# Repozytorium na potrzeby przedmiotu WIRDS 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/krakovska/wirds-2021-binder-przyklad/main?urlpath=rstudio)

Aby binder działał potrzebuje następująego pliku:

1. 'runtime.txt' --- określamy z jakiej wersji R będziemy korzystać oraz z jakiego dnia mają być pakiety (np. 'r-2021-01-01', 'r-3.6-2021-01-01')

Możemy założyć jakie pakiety mają być na w ramach tego obrazu. W takim razie powinniśmy utworzyć plik o nazwie 'install.R' do instalacji pakietów. Na przykład:

```{r}
install.packages("tidyverse")
install.packages("data.table")
install.packages("sf")
install.packages("rio")
```


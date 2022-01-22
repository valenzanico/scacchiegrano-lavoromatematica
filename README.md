## Progetto scacchi e grano


### tipo di dati 
- productions/supplies
- price
- area harvested
- yield
spiegazione: http://www.fao.org/waicent/faostat/agricult/pr_ele-e.htm

### fonti productions

2019-1961 - http://www.fao.org/faostat/en/#data

1961-1948 - http://www.fao.org/3/ap649e/ap649e.pdf pag151

1938-1885 - https://www.nber.org/research/data/nber-macrohistory-i-production-commodities
https://data.nber.org/databases/macrohistory/data/01/a01013.db
https://data.nber.org/databases/macrohistory/rectdata/01/docs/a01013.txt
https://data.nber.org/databases/macrohistory/rectdata/01/a01013.dat

1885-1865 - https://rpds.princeton.edu/sites/rpds/files/media/wp_12.pdf


### fonti wheat price

2019-1991 - wheatprice-1991to2019-FAOSTAT_data_4-22-2021.csv http://www.fao.org/faostat/en/#data

1991-1966 - wheatprice-1966to1990-FAOSTAT_data_4-22-2021.csv http://www.fao.org/faostat/en/#data

1947-1959 http://www.fao.org/3/ap647e/ap647e.pdf
pag 200 prezzi export - AVERAGE EXPORT UNIT VALUES

1947-1909 - https://core.ac.uk/download/pdf/7044326.pdf
pag 66

1909-1841 - https://data.nber.org/databases/macrohistory/rectdata/04/m04001a.dat
https://data.nber.org/databases/macrohistory/data/04/m04001a.db
https://data.nber.org/databases/macrohistory/rectdata/04/docs/m04001a.txt


### fonti yield

2019-1961 - wheat-yield-FAOSTAT_data_4-21-2021.csv http://www.fao.org/faostat/en/#data


### fonti harvested area

2019-1961 - wheat-harvestedarea-FAOSTAT_data_4-21-2021.csv http://www.fao.org/faostat/en/#data





### come funziona il sito
- server jupyter notebook contaneirizzato su docker
- iframe in pagina html con url al server docker
- prima riga codice nasconde barra tool e codice

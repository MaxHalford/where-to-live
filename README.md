# Where to live?

Here's an attempt to find towns in France that are:

- Close to a railway station
- Close to a lake
- Not too far from friends and family

Check out the result [here](https://maxhalford.github.io/where-to-live/).

Here's the data sources I downloaded and placed in the `data` directory:

| Name                     | File                                 | Source                                                                                                |
| ------------------------ | ------------------------------------ | ----------------------------------------------------------------------------------------------------- |
| Town locations           | `communes-departement-region.csv`    | [Source](https://www.data.gouv.fr/fr/datasets/communes-de-france-base-des-codes-postaux/)             |
| Population count by town | `ensemble.xls`                       | [Source](https://www.insee.fr/fr/statistiques/2387611?sommaire=2119504)                               |
| Railways                 | `formes-des-lignes-du-rfn.geojson`   | [Source](https://www.data.gouv.fr/fr/datasets/fichier-de-formes-des-lignes-du-reseau-ferre-national/) |
| Lakes                    | `hydrographie-surfaces-deau.geojson` | [Source](https://public.opendatasoft.com/explore/dataset/hydrographie-surfaces-deau/information/)     |

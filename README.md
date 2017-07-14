# foodtruckdb

## Publicated version 
[Temp Domain 1](https://app-btohsabsvn.now.sh/)

[Temp Domain 2](https://allofoodtruck.now.sh/)

[Final Domain](https://allofoodtruck.com/) - **Not published**


## Data model for food-trucks table
- (**name**)           : *Nom du FoodTruck*
- (**slug**)           : *Slug/ID*
- (**slogan**)         : *Slogan*
- (**tags**)           : *Hashtags (Spécialités, Univers, ...)* séparés par une virgule au sein d'une même **string**
- (**cover**)          : *Image de couverture*, lien de l'image dans une **string**
- (**latlng**)         : *Latitude et Longitude*, séparés par une virgule dans une **string**
- (**city**)           : *Ville*
- (**open_days**)      : *Jours d'ouverture*
- (**description**)    : *Description (Menus, Infos diverses, ...)*
- (**private_events**) : *Dispo pour des évents privés (OUI/NON)*, **boolean**
- (**reservation**)    : *Dispo pour des réservations de repas (OUI/NON)*, **boolean**
- (**local**)          : *Pignon sur rue (OUI/NON)*, **boolean**
- (**phone**)          : *Téléphone*
- (**mail**)           : *Mail*
- (**website**)        : *Site web*
- (**facebook**)       : *Facebook*
- (**twitter**)        : *Twitter*
- (**instagram**)      : *Instagram*


## Process of data input in database
1. Pull the repo
2. Edit datas in json files
3. Verify your json files by copy them and paste in [JSONLint](https://jsonlint.com/) to verify them
4. If verification is ok : you can push your job with a very descripted commit
5. That's all !


## Potentials data sources
- [Tribune de Lyon](http://www.tribunedelyon.fr/?art-de-vivre/gastronomie/41535-ou-trouver-les-meilleurs-food-trucks-a-lyon)
- [Yelp](https://www.yelp.fr/search?cflt=foodtrucks&find_loc=Lyon)
- [Le Petit Paumé](https://www.petitpaume.com/selection/les-food-trucks-a-lyon)
- [HelpLing](https://blog.helpling.fr/just-for-fun/food-truck-lyon/)
- [20 Minutes](http://www.20minutes.fr/lyon/1551051-20150227-selection-food-trucks-tester-quatre-coins-lyon)
- [LyonResto](http://www.lyonresto.com/restaurant-lyon/Food-truck/restaurant-lyon-Food-truck.htm)
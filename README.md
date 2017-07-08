# foodtruckdb

## Data model for food-trucks table
- (**name**)           : *Nom du FoodTruck*
- (**slug**)           : *Slug/ID*
- (**tags**)           : *Hashtags (Spécialités, Univers, ...)* séparés par une virgule au sein d'une même **string**
- (**cover**)          : *Image de couverture*, lien de l'image dans une **string**
- (**latlng**)         : *Latitude et Longitude*, séparés par une virgule dans une **string**
- (**city**)           : *Ville*
- (**open days**)      : *Jours d'ouverture*
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
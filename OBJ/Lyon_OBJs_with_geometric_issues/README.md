# OBJs

Use the branch [filter_ids](https://github.com/VCityTeam/py3dtilers/tree/filter_ids) of py3dtilers to target the CityObjects.

```bash
py3dtilers --type <type> --obj <output_obj_name> --ids <cityobject_ids>
```

Example:

```bash
py3dtilers --type building --obj tour_part_dieu --ids 69383AR8
```

## tour_part_dieu

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: 69383AR8  
type: building  
problème: surfaces manquantes  

## palais_de_justice

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: 69385AH128  
type: building  
problème: surfaces manquantes  

## cloche_hopital_charite

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: 69382PUBLIC10  
type: building  
problème: surfaces manquantes + lié à un autre bâtiment  

## ensemble_de_batiments_1

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: 69388CI75  
type: building  
problème: bâtiments distincts liés en une entité  

## ensemble_de_batiments_2

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: 69388AW117  
type: building  
problème: bâtiments distincts liés en une entité  

## extrait_terrain_lyon_2

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: gml_38179d6d-9886-48a9-9634-4e5eb1016a06  
type: relief  
problème: normales inversées + surfaces manquantes  

## extrait_1_terrain_lyon_5

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: gml_af20ae56-d662-4581-b17f-e7ca01101e3e  
type: relief  
problème: normales inversées + surfaces manquantes  

## extrait_2_terrain_lyon_5

source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: gml_f61667a0-435c-4d2f-973b-8b6d916fa9f9  
type: relief  
problème: normales inversées + surfaces manquantes  

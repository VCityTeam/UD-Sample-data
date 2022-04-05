# OBJs

Use the branch [filter_ids](https://github.com/VCityTeam/py3dtilers/tree/filter_ids) of py3dtilers to target the CityObjects.

```bash
citygml-tiler --type <type> --obj <output_obj_name> --ids <cityobject_ids>
```

Example:

```bash
citygml-tiler --type building --obj tour_part_dieu --ids 69383AR8
```

## Part Dieu tower building

<img src="tour_part_dieu_scene_view.png" alt="tour_part_dieu_scene_view" width="200"/>

* Problem: missing surfaces (after py3dTilers treatment)
* [Obj file](tour_part_dieu.obj)
* source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
* cityobject_id: 69383AR8  
* CityGML type: building

## Palais de justice

<img src="palais_de_justice_scene_view.png" alt="palais_de_justice_scene_view" width="400"/>

* Problem: missing surfaces (after py3dTilers treatment)
* [Obj file](palais_de_justice.obj)
* source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
* cityobject_id: 69385AH128  
* CityGML type: building

## Charity hospital bell tower

<img src="cloche_hopital_charite_scene_view.png" alt="palais_de_justice_scene_view" width="200"/>

* Problem: missing surfaces (after py3dTilers treatment) and also two
  geometrical buildings in one logical descriptor (refer below for details)
* [Obj file](cloche_hopital_charite.obj)
* Source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)
* cityobject_id: 69382PUBLIC10  
* CityGML type: building

## Building set 1

<img src="ensemble_de_batiments_1_scene_view.png" alt="ensemble_de_batiments_1_scene_view" width="400"/>

* Problem: two geometrically distinct buildings erroneously regrouped in
  a single logical descriptor
* [Fichier obj](ensemble_de_batiments_1.obj)
* source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)
* cityobject_id: 69388CI75
* CityGML type: building  

## Building set 2

<img src="ensemble_de_batiments_2_scene_view.png" alt="ensemble_de_batiments_1_scene_view" width="400"/>

* Problem: two geometrically distinct buildings erroneously regrouped in
  a single logical descriptor
* [Obj file](ensemble_de_batiments_2.obj)
* source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
cityobject_id: 69388AW117  
* CityGML type: building  

## Building set 3

<img src="ensemble_de_batiments_3_cloche_hopital_charite_scene_view.png" alt="ensemble_de_batiments_3_cloche_hopital_charite_scene_view" width="400"/>

* Problem: two geometrically distinct buildings erroneously regrouped in
  a single logical descriptor triggers a scale fusing algorithm two go off
  the charts
* [Obj file](cloche_hopital_charite.obj)
* Source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)
* cityobject_id: 69382PUBLIC10  
* CityGML type: building

## Terrain extract 1 (lyon_5)

Data before treatment

<img src="extrait_1_terrain_lyon_5_pre_py3dtilers_scene_view.png" alt="extrait_1_terrain_lyon_5_pre_py3dtilers_scene_view" width="400"/>

Data after treatment

<img src="extrait_1_terrain_lyon_5_scene_view.png" alt="extrait_1_terrain_lyon_5_scene_view Post traitement" width="400"/>

* Problem: inverted normals and missing surfaces/triangles
* [Obj file](extrait_1_terrain_lyon_5_pre_py3dtilers.obj)
* Source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
* cityobject_id: gml_af20ae56-d662-4581-b17f-e7ca01101e3e  
* CityGML type: relief  

## Terrain extract 2 (lyon_5)

<img src="extrait_2_terrain_lyon_5_scene_view.png" alt="extrait_2_terrain_lyon_5_scene_view" width="400"/>

* Problem: inverted normals. Too many (degenerated) triangles. Too many
  vertices not providing geometrical information.
* [Obj file](extrait_2_terrain_lyon_5.obj)
* Source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
* cityobject_id: gml_38179d6d-9886-48a9-9634-4e5eb1016a06  
* CityGML type: relief  

## Terrain extract 3 (lyon_2)

<img src="extrait_3_terrain_lyon_2_scene_view_a.png" alt="extrait_3_terrain_lyon_2_scene_view" width="400"/>

<img src="extrait_3_terrain_lyon_2_scene_view_b.png" alt="extrait_3_terrain_lyon_2_scene_view" width="600"/>

* Problem: inverted normals. Too many (degenerated) triangles. Too many
  vertices not providing geometrical information.
* Source: [maquette texturée 2018](https://data.grandlyon.com/jeux-de-donnees/maquettes-3d-texturees-2018-communes-metropole-lyon/info)  
* cityobject_id: gml_f61667a0-435c-4d2f-973b-8b6d916fa9f9  
* CityGML type: relief  

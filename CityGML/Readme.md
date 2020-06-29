### Concerning the LYON_1ER_BATI_2015_small_house example
In order to retrieve the citygml file LYON_1ER_BATI_2015_small_house.gml
out of [Lyon open data](https://data.grandlyon.com/accueil)
 - download the following archive
   ```
   wget https://download.data.grandlyon.com/files/grandlyon/localisation/bati3d/LYON_1ER_2015.zip
   unzip LYON_1ER_2015.zip
   ```
 - With your favorite (robust) editor, edit `LYON_1ER_2015/LYON_1ER_BATI_2015.gml`
   and keep the `cityObjectMember` xml tag which has the `gml:id` of value `BU_69381AB133`
   (i.e. the `cityObjectMember`with the line `<bldg:Building gml:id="BU_69381AB133">`) 
   while removing all the other `cityObjectMember` entries.
 - Rename the `app:imageURI` entry within the 
   `<app:Appearance> <app:surfaceDataMember><app:ParameterizedTexture>` tag i.e. you should
   get something like
   ```
   <app:Appearance>
       <app:theme>RhinoCity ObliqueTexturing</app:theme>
       <app:surfaceDataMember>
          <app:ParameterizedTexture>
              <app:imageURI>LYON_1ER_BATI_2015_small_house.jpg</app:imageURI>
          ...
   ```
 - Copy and rename the appearance texture accordingly i.e.
   ```
   cp LYON_1ER_2015/LYON_1ER_BATI_2015_Appearance/69381AB133.jpg ./LYON_1ER_BATI_2015_small_house.jpg
   ```

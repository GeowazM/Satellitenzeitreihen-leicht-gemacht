# <div align="center"> Satellitenzeitreihen leicht gemacht </div>
## <div align="center"> Einfach selber machen mit *Streamlit Geospatial* </div>


Hier finden Sie eine Sammlung an Satellitenzeitreihen, die mit Hilfe von leafmap, geemap &amp; streamlit schnell und einfach in verschiedenen Bandkombinationen erstellt wurden und mit Hilfe des GIF Scrubber Add-Ons visuell interpretiert werden können.



Mit [Streamlit for Geospatial Applications](https://streamlit.gishub.org/) lassen sich schnell und bequem Satellitenzeitreihen von überall auf der Erde erstellen. 
Das Erstellen dieser Zeitreihen ermöglicht die Cloudcomputing Platform [Google Earth Engine](https://earthengine.google.com/) und die Python Bibliothek [geemap](https://geemap.org/).  Mehr Informationen finden Sie [hier](https://streamlit.gishub.org/).


<br>

<p align="center">
  <img src="/Satellitenzeireihen/Rheinisches-Braunkohlerevier_321_tcc.gif" width="800" alt="Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier"/>
</p>

###### <div align="center"> Figure 1: Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier</div>




<br>
Folgen Sie dem *Demovideo* auf der [Streamlit for Geospatial Applications](https://streamlit.gishub.org/) Seite um eine Satellitenzeitreihe Ihres Untersuchungsgebietes zu erstellen.
<br>


<br>
Anschließend können Sie mit wenigen Klicks die Google Chrome Erweiterung *GIF Scrubber* installieren, welches aktuell ausschließlich mit dem Browser *Google Chrome* funktioniert.
<br>
Wenn Sie *GIF Scrubber* installiert haben können Sie in diesem github Verzeichnis unter dem Ordner *Satellitenzeitreihen* eine Reihe an Beispielen finden. Klicken Sie bspw. auf *Rheinisches-Braunkohlerevier_432_fcc.gif* und es öffnet sich eine Animation. Mit einem Rechtsklick.... 
Im Aufbau


GIF Scrubber: https://chrome.google.com/webstore/detail/gif-scrubber/gbdacbnhlfdlllckelpdkgeklfjfgcmp?hl=en


### What we will learn
* How to plot data in QGIS
*	How to install a plugin
*	How to add further data
*	How to create a cartogram


### What we need
* Dataset "*UNESCO World Heritage in Danger*" (own research based on [UNESCO](https://whc.unesco.org/en/danger/), Copyright©1992-2021 UNESCO/World Heritage Centre. All rights reserved)</div>
* UN subregions scheme (Data source: [Countries](https://www.naturalearthdata.com/http//www.naturalearthdata.com/download/110m/cultural/ne_110m_admin_0_countries.zip), Scheme source: [UN subregion M49](https://unstats.un.org/unsd/methodology/m49/))
* Oceanic basemap (Source: [Natural Earth](https://www.naturalearthdata.com/))

> [**Download data here**](https://github.com/GeowazM/The-Network-of-UNESCO-Sites-Changes-and-Patterns-visualized-with-Cartograms/blob/main/data/Download-Data_UNESCO_World-Heritage_Sites-in-Danger_HIS-GIS.zip)


### What to do
1. Download the provided data & open in QGIS
2. Install plugins
3. Explore a World Heritage Site in Danger
4. Analyse the distribution of World Heritage Sites in Danger worldwide

<br/>

--- 

### The context we are working in
Since its foundation in 1945, the United Nations Educational, Scientific and Cultural Organization (UNESCO) became one of the most famous international institutions worldwide. With its different programs, the UNESCO has transformed itself into an important brand for the protection of cultural and natural landmarks. Continuously, the list of UNESCO designated sites is growing. However, the last five decades have been characterized by global economic and political changes, which have also repeatedly made it necessary for UNESCO to adapt. The List of World Heritage in Danger shows impressively, that also centuries-old properties have to accommodate to ascertained and potential sources of danger.<br/>
The constantly increase of UNESCO designated sites can be shown very well on the basis of tables and graphs. However, the regional weighting and influence of certain policies can barely be displayed with tables and numbers, if at all. Maps can be helpful, making the spatial distribution over varying times visible. By using cartograms, warping a regular map based on a certain value, the different weighting of the individual regions can be shown even more clearly. This allows an interpretation of past developments and implementation of the individual policies of UNESCO.
<br/>
<p align="center">
  <img src="/images/UNESCO_sites_overview.png" width="800" alt="Map of global distribution of UNESCO sites"/>
</p>


<br>

<br/>


---

<div align="center">
<img src="/Bilder/rgeo_unesco-chair_uni-hd_v2.jpg" width="750" alt="rgeo Heidelberg University of Education"/>
</div>



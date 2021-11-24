# <div align="center"> Neue Perspektiven auf die Welt im Wandel </div>
## <div align="center"> Satellitenzeitreihen selbst gemacht mit *Streamlit Geospatial* </div>


Hier finden Sie ein Tutorial wie Sie mit *Streamlit for Geospatial Applications* schnell und bequem Satellitenzeitreihen von überall auf der Erde erstellen können. Darüber hinaus erklären wir Ihnen wie Sie mit Hilfe der Browser Erweiterung *GIF Scrubber* diese Satellitenzeitreihen genauer unter die Lupe nehmen können, um den Wandel auf der Erdoberfläche noch besser verstehen zu können.
<br>
Ein Beispiel einer solchen Satellitenzeitreihe sehen Sie in Abbildung 1. Sie zeigt die Veränderungen der Landschaft im Rheinischen Braunkohlerevier zwischen 1984 und 2020 zeigt.

<br>

<p align="center">
  <img src="/Anwendungsbeispiele/Deutschland_Rheinisches-Braunkohlerevier//Rheinisches-Braunkohlerevier_321_tcc.gif" width="800" alt="Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier"/>
</p>

###### <div align="center"> Abbildung 1: Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier für den Zeitraum 1984 - 2020</div>


<br>
<br>
<br>

## <div align="center"> Eine Satellitenzeitreihe selber machen</div>
<br>


Mit folgenden Schritten gelangen wir zur Satellitenzeitreihe:
1. Die Browser Erweiterung *GIF Scrubber* kennen lernen
2. Mit *Streamlit Geospatial* eine Satellitenzeitreihen selber machen
3. Mit zusätzlichen Bändern den Blick erweitern
4. Mehr thematische Anwendungsbeispiele (optional)


<br>
<br>

Für die Erstellung von Satellitenzeitreihen nutzen wir folgende Web Anwendungen: 
1. Web-Browser mit einer Erweiterung für GIF Animationen
    - Google Chrome Web-Browser inklusive der Erweiterung *GIF Scrubber*  oder der
    - Firefox Web-Browser inklusive der Erweiterung *GIF remote sensing* 
3. *Streamlit for Geospatial Applications* (1. Release November 2021) 

<br>

---

</br>

### 1. Die Browser Erweiterung *GIF Scrubber* nutzen

- Erweiterung GIF Scrubber bzw. GIF remote sensing hinzufügen
- Erweiterung testen

<br>

#### Hinzufügen der Browser Erweiterung *GIF Scrubbers* bzw. *GIF remote sensing*

Um die visuelle Interpretation der Satellitenzeitreihe voll ausschöpfen zu können empfehlen wir das hinzufügen der Erweiterung *GIF Scrubber* bzw. dessen Äquivalent *GIF remote sensing*:
- Für Google Chrome
    - Öffnen Sie dafür *GIF Scrubber* im Google Chrome Web Store (hier der Link)
    - Klicken Sie auf *Zu Chrome hinzufügen*

- Für Firefox
    - Öffnen Sie die *GIF remote sensing* Erweiterung im Mozilla Add-ons Store ([hier der Link](https://addons.mozilla.org/de/firefox/addon/gif-remote-sensing/))
    - Klicken Sie auf *Zu Firefox hinzufügen* und bestätigen Sie den Button *Zulassen*


<br>

Die Erweiterung ist jetzt für Ihren Google Chrome bzw. Firefox Browser verfügbar.
<br>

#### Testen Sie den *GIF Scrubber*

Um zu prüfen ob die Erweiterung verfügbar ist, klicken Sie mit der rechten Maustaste auf die Abbildung 1 (siehe oben). Wenn die Erweiterung erfolgreich hinzugefügt wurde erscheint die Option *GIF Scrubber* mit diesem Logo <img src="/Bilder/gif-scrubber/logo_gif-scrubber.PNG" width=25 alt="Logo GIF Scrubber">. Klicken Sie diese Option an. <br>
Es öffnet sich ein neues Fenster, in dem Sie die Satellitenzeitreihe kontrollieren können. Testen Sie die Funktionen. Mit der Option <img src="/Bilder/gif-scrubber/buttons_gif_scrubber_explode.PNG" alt="GIF Scrubber option explode"> können Sie die einzelnen Jahre begutachten und mit dem Button <img src="/Bilder/gif-scrubber/buttons_gif_scrubber_download.PNG" alt="GIF Scrubber option download"> können Sie die Zeitreihe als einzelne Bilder herunterladen. Versuchen Sie es!
<br>

<p align="center">
  <img src="/Bilder/gif-scrubber/buttons_gif_scrubber_overview.PNG" width=550 alt="GIF Scrubber window">
</p>

###### <div align="center"> Abbildung 2: Einblick in die Nutzeroberfläche der GIF Scrubbber Erweiterung</div>

<br> 


<br>


---

<br>

### 2. Erstellen einer Satellitenzeitreihe mit *Streamlit for Geospatial Applications*

Mit [Streamlit for Geospatial Applications](https://streamlit.gishub.org) lassen sich schnell und bequem Satellitenzeitreihen von überall auf der Erde erstellen. 
Wenn Sie den Link zur Web-Anwendung öffnen (siehe unten) kommen Sie auf die Startseite (siehe Abbildung 3). Wählen Sie im Menü auf der linken Seite die Option "*Create Timelapse*".
Folgen Sie dem *Demovideo* auf der [Streamlit for Geospatial Applications](https://streamlit.gishub.org) Seite um eine Satellitenzeitreihe Ihres Untersuchungsgebietes zu erstellen.<br>
*Tipp*: Öffnen Sie die Seite in einem neuen Reiter bzw. Tab. 
<br>

###### <div align="center"> Zur Web-Anwendung kommen Sie über diesen Link: </div>

### <div align="center"> [Streamlit for Geospatial Applications öffnen](https://streamlit.gishub.org) </div>



<br>

<p align="center">
  <img src="/Bilder/streamlit-geospatial/screen_1_home.PNG" width="800" alt="Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier">
</p>

###### <div align="center"> Abbildung 3: Startbildschirm von *Streamlit for Geospatial Applications* </div>



<br>

Das Erstellen dieser Zeitreihen ermöglicht die Cloudcomputing Platform [Google Earth Engine](https://earthengine.google.com) und die Python Bibliothek [geemap](https://geemap.org/).  Mehr Informationen zu den technischen Hintergründen finden Sie [hier](https://streamlit.gishub.org/).

<br>
<br>



---


### 3. Mit zusätzlichen Bändern den Blick erweitern

<br/>

Satelliten erfassen die Erdoberfläche in verschiedenen Kanälen für unterschiedliche Bereiche des Lichts. Blaues Lict wird im blauen Kanal, grünes Licht im grünen Kanal und rotes Licht im roten Kanal gespeichert. Satelliten können darüber hinaus Lichtbereiche aufnehmen, die für das menschliche Auge unsichtbar sind. Deshalb gibt es Kanäle für z.B. Infrarotlicht (NIR = Nahes Infrarot / IR = Infrarot). Wenn der rote Kanal für (R), den grünen für (G) und den blauen Kanal für (B) zugeordnet wurde erhält ein sog. Echtfarbenbild – die Farben werden so angezeigt, wie es das menschliche Auge gewohnt ist: 

<p align="center">
  <img src="/Bilder/rgeo_echtfarbenbild.png" width="800" alt="Echtfarbenbild">
</p>

###### <div align="center"> Abbildung 4: Zusammenstellung eines Echtfarbenbild </div>


Vertauschst du die Farben oder wählst einen Kanal aus, der für das menschliche Auge eigentlich unsichtbar ist, wird ein Falschfarbenbild erzeugt. Die Farben im Satellitenbild sehen dann unnatürlich aus, helfen aber oft zusätzliche Informationen über das abgebildete Gebiet sichtbar zu machen: 

<p align="center">
  <img src="/Bilder/rgeo_falschfarbenbild.png" width="800" alt="Falschfarbenbild">
</p>

###### <div align="center"> Abbildung 5: Zusammenstellung eines Falschfarbenbild </div>

<br/>

So entsteht aus einer Auswahl von fünf verfügbaren Kanälen ein Falschfarbenbild von Bitterfeld. Das Bild sieht ungewohnt aus, dafür erkennt man bestimmte Bildelemente deutlich besser als im Echtfarbenbild. Gesunde Pflanzen reflektieren z.B. sehr stark im Infraroten Licht (NIR). Da dieser Kanal hier in rot dargestellt wird, lässt sich der Zustand von Pflanzen so besser ablesen.

<br/>
<br>

<p align="center">
  <img src="/Anwendungsbeispiele/Deutschland_Rheinisches-Braunkohlerevier/Rheinisches-Braunkohlerevier_432_fcc.gif" width="800" alt="Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier als Falschfarbenkomposite"/>
</p>

###### <div align="center"> Abbildung 6: Ein Beispiel einer Zeitreihe in Falschfarbendarstellung vom Rheinischen Braunkohlerevier</div>

<br/>
<br>


---


### 4. Mehr thematische Anwendungsbeispiele



<br>
<br>
<br>

<p align="center">
  <img src="/Anwendungsbeispiele/USA_Las_Vegas/las_vegas_432_fcc.gif" width="800" alt="Landsat Satellitenzeitreihe von Las Vegas, USA"/>
</p>

###### <div align="center"> Abbildung 7: Landsat Satellitenzeitreihe von Las Vegas, USA</div>

<br>
<br>

<p align="center">
  <img src="/Anwendungsbeispiele/Iran_Urmiasee/Lake-Urmia_543.gif" width="500" alt="Landsat Satellitenzeitreihe vom Urmiasee"/>
</p>

###### <div align="center"> Abbildung 8: Landsat Satellitenzeitreihe vom Urmiasee im Nordsosten des Irans für den Zeitraum 1984 - 2020</div>

<br>
<br>

<p align="center">
  <img src="/Anwendungsbeispiele/Schweiz_Grosse-Aletschgletscher/Aletsch_654.gif" width="500" alt="Landsat Satellitenzeitreihe vom Grossen Aletschgletscher"/>
</p>

###### <div align="center"> Abbildung 9: Landsat Satellitenzeitreihe vom Grossen Aletschgletscher</div>

<br>





---

<div align="center">
<img src="/Bilder/rgeo_unesco-chair_uni-hd_v2.jpg" width="750" alt="rgeo Heidelberg University of Education"/>
</div>



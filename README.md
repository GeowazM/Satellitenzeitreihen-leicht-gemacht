# <div align="center"> Neue Perspektiven auf die Welt im Wandel </div>
## <div align="center"> Satellitenzeitreihen selbst gemacht mit *Streamlit Geospatial* </div>


Hier finden Sie ein Tutorial wie Sie mit *Streamlit for Geospatial Applications* schnell und bequem Satellitenzeitreihen von überall auf der Erde erstellen können. Darüber hinaus erklären wir Ihnen wie Sie mit Hilfe der Browser Erweiterung *GIF Scrubber* diese Satellitenzeitreihen genauer unter die Lupe nehmen können, um den Wandel auf der Erdoberfläche noch besser verstehen zu können.
<br>
Ein Beispiel einer solchen Satellitenzeitreihe sehen Sie in Abbildung 1, dass die Veränderungen der Landschaft im Rheinischen Braunkohlerevier zwischen 1984 und 2020 zeigt.



<br>

<p align="center">
  <img src="/Satellitenzeireihen/Rheinisches-Braunkohlerevier_321_tcc.gif" width="800" alt="Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier"/>
</p>

###### <div align="center"> Abbildung 1: Landsat Satellitenzeitreihe vom Rheinischen Braunkohlerevier für den Zeitraum 1984 - 2020</div>


<br>
<br>
<br>

## <div align="center"> Eine Satellitenzeitreihe selber machen</div>
<br>


Überblick
1. Die Browser Erweiterung *GIF Scrubber* nutzen
2. Mit *Streamlit Geospatial* Satellitenzeitreihen selber machen
3. Mit weiteren Bändern den Blick erweitern
4. Mehr thematische Anwendungsbeispiele


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

Um zu prüfen ob die Erweiterung verfügbar ist, klicken Sie mit der rechten Maustaste auf die Abbildung 1 (siehe oben). Wenn die Erweiterung erfolgreich hinzugefügt wurde erscheint die Option *GIF Scrubber* mit diesem Logo (Bild). Klicken Sie diese Option an. <br>
Es öffnet sich ein neues Fenster, in dem Sie die Satellitenzeitreihe kontrollieren können. Testen Sie die Funktionen. Mit der Option <img src="/Bilder/gif-scrubber/buttons_gif_scrubber_explode.PNG" alt="GIF Scrubber option download"> können Sie die einzelnen Jahre begutachten und mit dem Button <img src="/Bilder/gif-scrubber/buttons_gif_scrubber_download.PNG" alt="GIF Scrubber option download"> können Sie die Zeitreihe als einzelne Bilder herunterladen. Versuchen Sie es!
<br>

<p align="center">
  <img src="/Bilder/gif-scrubber/buttons_gif_scrubber_overview.PNG" width=520 alt="GIF Scrubber window">
</p>

###### <div align="center"> Abbildung 2: Einblick in die Nutzeroberfläche der GIF Scrubbber Erweiterung</div>

<br> 

Ein Videotutorial dazu finden sie hier(!!!).

<br> 

## Notiz an mich: 
- Video wie die Chrome Erweiterung hinzugefügt wird und an dem Rheinischen Braunkohlerevier getestet wird.
- Irgendwo muss der Hinweis hin, dass es das nur auf englisch gibt
- Anleitung Erweiterung Google Chrome https://support.google.com/chrome_webstore/answer/2664769?hl=de
GIF Scrubber: https://chrome.google.com/webstore/detail/gif-scrubber/gbdacbnhlfdlllckelpdkgeklfjfgcmp?hl=en
- Maßstab in Zeitreihen einfügen

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




---


### 3. Mit weiteren Bändern den Blick erweitern


<br/>

---



### 4. Mehr thematische Anwendungsbeispiele


---

<div align="center">
<img src="/Bilder/rgeo_unesco-chair_uni-hd_v2.jpg" width="750" alt="rgeo Heidelberg University of Education"/>
</div>



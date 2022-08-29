# Lern-Bericht
Modul 133 Webapplikationen mit JSF realisieren

## Einleitung

Im Auftrag LA_133_9954_Pokemon durfte ich in Anlehnung an das Spiel Pokémon Go eine webbasierte Konfiguration des Avatars. Zur Übung der Techniken Navigation und Session erfolgt die Konfiguration über mehrere Seiten. Für die unterschiedlichen Konfigurationsmöglichkeiten steht Ihnen eine Auswahl an Bildern zur Verfügung. 

## Was habe ich gelernt?

Gelernt habe ich wie ich Bilder in einer Webapplikation darstelle und dmait Benutzereingaben entgegenehmen kann.

## Beschreibung

Mittels h:commandLink ermöglicht es dem Benutzer das Bild anzuklicken und mittels h:graphicImage, wird das Bild dargestellt. 
Im h:commandLink steht library="img" da das Bild sich im Ordner ressources\img befindet, das Bild heisste name="h.png".
Mittels f:setPropertyActionListener wird bei einem klick der Wert skinColor im HelloManagedBean auf h gesetzt.

```
<h:commandLink value="" action="EyeColor.xhtml">
    <!-- Backing Bean handover user input -->
    <f:setPropertyActionListener target="#{helloManagedBean.skinColor}" value="h"/>
    <!-- library = \resources\img -->
    <h:graphicImage library="img" name="h.png" width="200"/> 
</h:commandLink>
```

![LA_133_9954_Pokemon](https://user-images.githubusercontent.com/94226346/187175103-4c568e33-24be-4ab0-859d-29c89f7756b0.jpg)


## Verifikation



# Reflektion zum Arbeitsprozess

👍 

👎 

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.

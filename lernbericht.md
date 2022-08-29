# Lern-Bericht
Modul 133 Webapplikationen mit JSF realisieren

## Einleitung

Im Auftrag LA_133_9954_Pokemon durfte ich in Anlehnung an das Spiel Pokémon Go eine webbasierte Konfiguration des Avatars. Zur Übung der Techniken Navigation und Session erfolgt die Konfiguration über mehrere Seiten. Für die unterschiedlichen Konfigurationsmöglichkeiten steht Ihnen eine Auswahl an Bildern zur Verfügung. 

## Was habe ich gelernt?

Gelernt habe ich wie ich Bilder in einer Webapplikation darstelle und dmait Benutzereingaben entgegenehmen kann.

## Beschreibung

```
<h:commandLink value="" action="EyeColor.xhtml">
    <!-- Backing Bean handover user input -->
    <f:setPropertyActionListener target="#{helloManagedBean.skinColor}" value="h"/>
    <!-- library = \resources\img -->
    <h:graphicImage library="img" name="h.png" width="200"/> 
</h:commandLink>
```

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.

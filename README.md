# Groenanalyse-Haarlem

## Rapportage
Voor het volledige rapport van de uitkomsten van deze analyse, zie [`Groenanalyse_Haarlem.pdf`](/reports/Groenanalyse_Haarlem.pdf).

## Korte beschrijving
Dit project onderzoekt de mate van verstening in Haarlem door een vergelijking te maken tussen twee methoden: een analyse op basis van de Basisregistratie Grootschalige Topografie (BGT) en een datagedreven classificatie van CIR-luchtfoto’s met behulp van een Random Forest model. Daarbij wordt per buurt het oppervlak aan groen, verharding en water berekend. De resultaten worden geanalyseerd, gevisualiseerd en vergeleken met de uitkomsten van het onderzoek van Natuur & Milieu uit 2022.

## Doel
Het doel van dit project is om beter inzicht te krijgen in de verhouding tussen verharding en vegetatie in Haarlem, en te onderzoeken in hoeverre dit afhangt van de gebruikte bron en definitie van "groen". De analyse beoogt een completer beeld te geven van functioneel en beleefbaar groen in de stad, en bij te dragen aan datagedreven beleidsvorming rond stedelijke vergroening, hittestress en waterbeheer.

## Onderzoeksvraag

> **Hoofdvraag**: In hoeverre wijkt het beeld van verstening in Haarlem op basis van luchtfoto’s af van de analyse van Natuur & Milieu (2022), die gebruikmaakt van de BGT?

### Deelvragen:
1. Wat zijn de belangrijkste verschillen tussen de gebruikte datasets (BGT en luchtfoto's) en hun definities van "groen"?

2. Wat is het verschil in gemeten groen per woning tussen de BGT en de luchtfoto-classificatie in Haarlem?

3. Wat zijn de meest versteende buurten volgens beide methoden?

4. Wat verklaart de verschillen tussen de uitkomsten van beide methoden?

5. Wat zijn de implicaties van deze verschillen voor beleidsmatig sturen op vergroening?

## Projectstructuur

```bash
Verstening_Haarlem_Project/
├── data/              # Invoerdata: luchtfoto's, shapefiles
│   ├── private/       # Bestanden die niet naar Github moeten worden geupload
│   ├── raw/           # Originele bronnen
│   └──  processed/    # Bewerkt (bijgesneden, opgeschoond)
├── docs               # Relevante documenten
├── notebooks/         # Jupyter notebooks voor elke stap
├── output/            # Visualisaties, kaarten, resultaten
├── qgis/              # Alle QGIS projectbestanden voor ruimtelijke analyse
├── reports/           # Eindrapport
├── README.md          # Dit bestand
├── requirements.txt   # Lijst van benodigde Python packages
└── .gitignore         # Bestanden die GitHub moet negeren
```

Let op: grote bestanden zoals het luchtfoto-bestand zijn niet opgenomen in deze repository. Plaats dit handmatig in data/private/ om het project volledig te laten draaien.

## Status
Dit project is afgerond en gedocumenteerd als onderdeel van een verkennende analyse naar stedelijke vergroening in Haarlem.

## Auteur
Mijn naam is Aaron Janssens, afgestudeerd watermanager met interesse in data science en klimaatadaptatie. Dit project is onderdeel van een leerroute naar datagedreven werken in het waterbeheer en het ruimtelijk domein.

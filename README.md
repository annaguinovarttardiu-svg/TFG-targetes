# Anàlisi a de les sancions esportives en la Lliga de futbol

Aquest repositori conté el codi desenvolupat per al Treball de Fi de Grau (TFG) del Grau en Estadística.

## Descripció del projecte

L'objectiu d'aquest treball és analitzar les sancions disciplinàries a la Primera Divisió masculina de futbol professional durant les temporades 2023-24 i 2024-25.

L'estudi es basa en dades obtingudes mitjançant un procés de web scraping a partir de la pàgina web de LaLiga i desenvolupat en R. A partir d'aquestes dades es realitzen anàlisis descriptives i es construeix un model mixt de Poisson amb la finalitat d'identificar factors relacionats amb l'aparició de targetes.

## Estructura del repositori

- `annexos/`: scripts utilitzats per a l'extracció i preparació de les dades, així com les anàlisis descriptives, bivariants i la modelització estadística.
- `cards2324/`: informació de les targetes per a la temporada 23-24.
- `cards2425/`: informació de les targetes per a la temporada 24-25.
- `cards_all/`: base de dades final creada en el web scraping (combinació de les dues temporades) i emprada en l'estudi.
- `taula_model/`: dataset utilitzat per a construir el model.
  
## Metodologia

El treball es desenvolupa seguint les etapes següents:

1. Obtenció de les dades mitjançant web scraping.
3. Anàlisi descriptiva univariant i bivariant.
4. Construcció d'un model mixt de Poisson.
5. Validació del model mitjançant tècniques de diagnòstic, prediccions i validació Leave-One-Group-Out (LOGO).

## Programari utilitzat

Les anàlisis s'han dut a terme amb:

- RStudio

## Autora

**Anna Guinovart**

Grau en Estadística  
Universitat de Barcelona (UB) - Universitat Politècnica de Catalunya (UPC)

## Finalitat del repositori

Aquest repositori es posa a disposició amb finalitats acadèmiques i de reproduïbilitat. El codi inclòs correspon a les anàlisis desenvolupades en el Treball de Fi de Grau.

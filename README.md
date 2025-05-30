# Noliktavas maršrutēšanas lietotnes apraksts

Šī repozitorija saturs ir saistīts ar akadēmisko darbu par pasūtījumu komplektētāja maršrutēšanas algoritmu analīzi un testēšanu.

##  Struktūra un failu saturs

- **index.html** – Galvenā lietotnes lietotāja saskarne. Satur vizualizācijas aspektus: CANVAS un vadības elementus.
- **indexTest.html** – Automātisko eksperimentu veikšanas fails.
- **main.css** – Lietotnes stilu apraksts(adaptīvais dizains).

- **globalSystemInit.js** – Inicializē galvenos klases objektus, sasaista tos.
- **globalSystemInitTest.js** – Inicializē testēšanas metodi un eksperimentu parametrus.
- **globalUIControl.js** – Lietotāja saskarnes darbību apstrāde.

- **warehouseModel.js** – Satur klasi `WarehouseModel`. Atbild par noliktavas struktūras ģenerēšanu, parametrizāciju.
- **pickListGenerator.js** – Klase `PickListGenerator`. Ģenerē komplektēšanas sarakstus no pieejamām uzglabāšanas vietu pozicijam.
- **RouteCalculate.js** – Klase `RouteCalculate`. Realizē maršrutu plānošanu, tostarp izmanto TSP un A* algoritmus.
- **RouteDisplay.js** – Klase `RouteDisplay`. Nodrošina noliktavas karti un maršruta attēlošanu uz CANVAS.
- **warehouses.json**, **warehouses2.json** – Noliktavas eksperimentu parametru apraksti JSON formātā.

## Klases

- `WarehouseModel` – Noliktavas modelēšana.
- `PickListGenerator` – Komplektēšanas saraksta izveide.
- `RouteCalculate` – Maršrutu aprēķini un optimizācija.
- `RouteDisplay` – Vizualizācija un attēlošana.

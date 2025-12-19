<p align="center">
  <img src="assets/logo.svg" alt="OPEN LYUBOMYR" width="200">
</p>

<p align="center">Una raccolta centralizzata di dataset personali puliti e standardizzati.</p>
<p align="center">Questo progetto espone dati geospaziali, statistiche di gioco e archivi media tramite file statici ottimizzati. Ogni risorsa segue schemi rigorosi per eliminare il data munging per gli sviluppatori finali. Scarica, importa, usa.</p>


## Indice

- [Indice](#indice)
- [Dataset](#dataset)
- [Struttura progetto](#struttura-progetto)

## Dataset

<p align="right">(<a href="#indice">indice</a>)</p>

<table>
  <thead>
    <tr>
      <th>Dataset ID</th>
      <th>File Path</th>
      <th>Standard di Riferimento</th>
      <th>Stato</th>
      <th>Prima Entry</th>
      <th>Ultima Entry</th>
      <th>Live Map</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>cestini</td>
      <td>/data/cestini.geojson</td>
      <td>RFC 7946 (GeoJSON)</td>
      <td>in pausa</td>
      <td>2023-09-15</td>
      <td>2024-02-16</td>
      <td><a href="http://geojson.io/#data=data:text/x-url,https://cdn.jsdelivr.net/gh/plumkewe/open-lyubomyr@main/data/cestini.geojson">geojson.io</a></td>
    </tr>
    <tr>
      <td>panchine</td>
      <td>/data/panchine.geojson</td>
      <td>OSM Tags</td>
      <td>in pausa</td>
      <td>2023-10-06</td>
      <td>2025-10-08</td>
      <td><a href="http://geojson.io/#data=data:text/x-url,https://cdn.jsdelivr.net/gh/plumkewe/open-lyubomyr@main/data/panchine.geojson">geojson.io</a></td>
    </tr>
    <tr>
      <td>fiori</td>
      <td>/data/fiori.geojson</td>
      <td>GBIF Taxonomy</td>
      <td>in pausa</td>
      <td>2022-09-01</td>
      <td>2023-10-06</td>
      <td><a href="http://geojson.io/#data=data:text/x-url,https://cdn.jsdelivr.net/gh/plumkewe/open-lyubomyr@main/data/fiori.geojson">geojson.io</a></td>
    </tr>
    <tr>
      <td>iamhere</td>
      <td>/data/iamhere.geojson</td>
      <td>OSM Artwork</td>
      <td>completo</td>
      <td></td>
      <td></td>
      <td><a href="http://geojson.io/#data=data:text/x-url,https://cdn.jsdelivr.net/gh/plumkewe/open-lyubomyr@main/data/iamhere.geojson">geojson.io</a></td>
    </tr>
    <tr>
      <td>chess</td>
      <td>/data/chess.json</td>
      <td>PGN Standard</td>
      <td>attivo</td>
      <td>2022-11-05</td>
      <td>2025-08-23</td>
      <td>-</td>
    </tr>
    <tr>
      <td>zeb89</td>
      <td>/data/zeb89.json</td>
      <td>Custom JSON</td>
      <td>completo</td>
      <td></td>
      <td></td>
      <td>-</td>
    </tr>
    <tr>
      <td>voti</td>
      <td>/data/voti.json</td>
      <td>Custom JSON</td>
      <td>completo</td>
      <td>2020-10-02</td>
      <td>2025-06-03</td>
      <td>-</td>
    </tr>
</table>

## Struttura progetto

<p align="right">(<a href="#indice">indice</a>)</p>

```
├── assets/
├── data/
│   ├── cestini.geojson
│   ├── chess.json
│   ├── fiori.geojson
│   ├── iamhere.geojson
│   ├── panchine.geojson
│   ├── voti.json
│   └── zeb89.json
├── media/
│   ├── audio/
│   └── images/
├── README.md
```
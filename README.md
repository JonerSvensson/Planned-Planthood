# Planned-Planthood

Skapa sida med HTML och CSS som har samma utseende som följande mall: <figure><img src='./assets/images/screenshot.png'></figure>

## Projektbeskrivning

- Kort beskrivning av vad er webbplats handlar om.

## Tekniker som använts

- HTML: Semantik, struktur
- CSS: Layout, responsivitet (flexbox, grid & clamps)

## Utmaningar & lösningar

- Reflektera över svårigheter och hur ni löste dem.

- Utmanande att skapa en knapp för **mina sidor** där varje planta som skiljer sig åt utseendemässigt beroende på om man är på mobil eller inte.

  - På mobilen var det en ganska simpel lösning där varje listad planta är ett 2x3 grid och gick att applicera på alla 3 plantor.

  - På desktop var det mer utmanande då plantor under **planerade planteringar** och **planterade planteringar** skiljer sig åt med antal plantor. Lösningen på detta blev att hantera varje kategori olika i CSS. **planerade planteringar** görs om till ett 2x4 grid när media query triggras.

- Svårt att skapa en responsivitet när man zoomar in och ut mellan olika storlekar av enheter.
  - Lösning här blev att lära sig clamps som gör att vi kan styra minimum, rekommenderad och maximal storlek på t.ex. titlar och texter mm. Svårt att få till rekommenderad storlek då denna gärna får vara dynamisk och ofta gick det att köra vw som enhet i CSS.

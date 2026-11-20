<p align="center">
  <b>Mapas sin conexión de LiteDash</b><br>
  <i>LiteDash offline maps</i><br><br>
  <a href="https://github.com/IrvingGuerra/litedash">LiteDash</a> ·
  <a href="https://litedash.dev/">litedash.dev</a> ·
  <a href="https://litedash.dev/en/">English</a>
</p>

<p align="center">
  <a href="https://ko-fi.com/irvingguerradev"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Apóyame en Ko-fi"></a>
</p>

Paquetes de mapa por estado o región para [LiteDash](https://github.com/IrvingGuerra/litedash), el launcher para
pantallas Android de auto. **Este repo no tiene la app**: solo los datos que la app baja cuando eliges tu estado en
Ajustes, publicados en sus [Releases](https://github.com/IrvingGuerra/litedash-maps/releases).

Cada región trae tres archivos:

| Archivo | Qué es |
| --- | --- |
| `<región>.pmtiles` | El mapa ([PMTiles v3](https://github.com/protomaps/PMTiles), esquema [OpenMapTiles](https://openmaptiles.org/), zooms 12–14): calles, agua, parques, edificios y nombres |
| `<región>.ldm` | Las calles para calcular rutas sin internet (sentido, tipo de vía, velocidad, vueltas prohibidas) |
| `<región>.srch` | El índice para buscar calles, colonias, localidades y lugares sin internet |

Se arman a partir de los extractos de [Geofabrik](https://download.geofabrik.de/) con
[Planetiler](https://github.com/onthegomap/planetiler) y los scripts de LiteDash. Hoy: **México** (32 estados),
**Estados Unidos** (50 estados, Washington D. C. y Puerto Rico), **Canadá** (10 provincias y 3 territorios),
**Colombia** (33 departamentos), **Ecuador** (24 provincias), **Perú** (24 departamentos y el Callao), **Chile** (16 regiones) y **Argentina** (23 provincias y la Ciudad de Buenos Aires). ¿Falta tu país? Pídelo desde LiteDash o abre un issue.

---

Offline map packages per state or region for [LiteDash](https://github.com/IrvingGuerra/litedash), the launcher for
Android car head units. **This repo doesn't hold the app**, only the data the app downloads when you pick your
region, published in [Releases](https://github.com/IrvingGuerra/litedash-maps/releases). Each region has a map
(`.pmtiles`), the streets for offline routing (`.ldm`) and an offline search index (`.srch`). Available today:
**Mexico** (32 states), the **United States** (50 states, Washington, D.C. and Puerto Rico), **Canada** (10 provinces
and 3 territories), **Colombia** (33 departments), **Ecuador** (24 provinces), **Peru** (24 departments and Callao), **Chile** (16 regions) and **Argentina** (23 provinces and the City of Buenos Aires).

## Atribución y licencia · Attribution and license

- Datos del mapa © [colaboradores de OpenStreetMap](https://www.openstreetmap.org/copyright), disponibles bajo la
  [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Map data © OpenStreetMap
  contributors, available under the ODbL 1.0.
- Esquema de teselas © [OpenMapTiles](https://openmaptiles.org/) ([CC-BY 4.0](https://github.com/openmaptiles/openmaptiles/blob/master/LICENSE.md)).
- Las bases de datos de este repo se comparten bajo la misma ODbL 1.0 (ver [LICENSE.md](LICENSE.md)).

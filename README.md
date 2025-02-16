# Easy-Docker-Pgrouting  3.6.2 (pg16)

![Docker automated](https://img.shields.io/docker/cloud/automated/pgrouting/pgrouting)
![Docker status](https://img.shields.io/docker/cloud/build/pgrouting/pgrouting)
![Docker builds](https://img.shields.io/docker/pulls/pgrouting/pgrouting)

<hr/>
<div align="center">
    <img src="./ico/logo-fmr.png"       alt="FMR"       style="margin: 0 10px; height: 70px;    width: 200px" />
    <img src="./ico/logo-disbral.png"   alt="Disbral"   style="margin: 0 10px; height: 100px;   width: 300px" />
    <img src="./ico/logo-enapa.png"     alt="ENAPA"     style="margin: 0 10px; height: 70px;    width: 200px" />
</div>
<hr/>
<br>

**Note**: The outdated docker images folders for the unsupported pgRouting versions are removed, but they can be retrieved from the Git history, if needed by someone.

pgRouting Docker image (version 3.6.2) built over [Postgres 16/PostGIS 3.4](https://hub.docker.com/r/postgis/postgis) and dependencies.

## Links

Links for pgRouting v3 Forked:

- [https://pgrouting.org/](*/). Oficial Website Pgrouting.

- [https://github.com/pgRouting/docker-pgrouting](16-3.4-3.6.2/). Base Repositorie: `pgrouting/pgrouting:16-3.4-3.6.2`

- [https://github.com/pgRouting/pgrouting](*/). Base Repositorie Pgrouting.

- [https://hub.docker.com/r/pgrouting/pgrouting](*/). Base Image Docker.

- [https://hub.docker.com/r/pgrouting/pgrouting/tags](*/). Base Image Docker Tags Pgrouting - Version.

- [https://docs.pgrouting.org/latest/en/index.html](*/). Docs Pgrouting.

- [https://github.com/pgRouting/osm2pgrouting](*/). Gith Osm2PGrouting.

- [https://manpages.ubuntu.com/manpages/trusty/man1/osmconvert.1.html](*/). Osmconvert.

 - [https://live.osgeo.org/en/quickstart/pgrouting_quickstart.html](*/). QuickStart PGrouting.

## 1° Step
 - Download your osm grahp in [Geofabrik](https://download.geofabrik.de/)
 - Save Your file downloaded *.pbf in `src\OSM\<Your File>.pbf`
 - Update `<Your File>.pbf` in `src\Dockerfile`

## 2° Step
 - Open cmd and acess `src\`
 - Run `Docker compose up --build -d`
 - Finish Your have Pgrouting Online!!
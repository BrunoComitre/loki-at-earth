# Loki at Earth

Challenge project for [Challenge - WARNING: THINGS ARE HEATING UP!](https://2021.spaceappschallenge.org/challenges/statements/warning-things-are-heating-up/details) 

&nbsp;

ANHANGÁ: CIÊNCIA CIDADÃ PARA ALERTA DE QUEIMADAS E INCÊNDIOS

Os sistemas de monitoramento orbital de queimadas e incêndios são baseados no uso de imagens de baixa resolução espacial. Sendo assim, as queimadas cuja extensão é muito inferior à resolução espacial do sensor podem não ser identificadas. É  caso, por exemplo, de queimadas que acontecem no perímetro urbanos dos municípios e que são muito frequentes no período de estiagem.
Este projeto tem como objetivo, desenvolver um sistema que permita que qualquer cidadão possa fazer o registro de uma queimada (cidadãos como sensores), fornecendo uma foto com geotag (localização da foto).

Os dados de coordenadas espaciais da queimada são enviados para as instituições responsáveis pelo combate e autuação. Além disso, esses dados de ciência cidadã são úteis para validação (verificação de erros de omissão e de comissão) de produtos de monitoramentos de queimadas (área queimada e focos).
Outra funcionalidade do sistema é enviar alertas de queimadas e incêndios que estão ocorrendo nas proximidades (até 2 km) de uma determinada localização, como residência de interessados em receber o alerta, aeroportos, áreas protegidas (unidades de conservação e terras indígenas) linhas de transmissão de energia e outros.

O sistema deve consumir os seguintes dados:
- Produto MYD09Q1 (Reflectância de superfície, composição de 8 dias, com resolução de 250 m)para visualização da superfície terrestre, considerando o melhor pixel dos últimos 8 dias
- Produto MYD09GQ (Reflectância de superfície, diário, com resolução de 250 m) para visualização da superfície terrestre diária (com possibilidade de cobertura de nuvens e ausência de imagens)
- Produto MYD14A1.006 (Anomalias térmicas e fogo diário, com resolução de 1 km) para visualização da localização de queimadas
- Produto MYD04_L2 (Aerossol, 5 minutos, com resolução de 10 km) para visualização de plumas de fumaça
- Focos de queimadas ocorridas nas últimas 2 horas (todos os satélites) disponibilizados pelo Projeto Queimadas do INPE para visualizar as coordenadas de queimadas e incêndios detectados por outros satélites além do MODIS/Aqua
- OpenStreetMap (OSM), que é um projeto de mapeamento colaborativo para facilitar a buscar de uma determinada localização

O sistema apresenta também uma análise espaço-temporal dos incêndios de vegetação detectados pelo MODIS/Aqua (satélite de referência) durante os últimos 10 anos por município.

Na Mitologia Nórdica, Loki é o deus do fogo. O nome do grupo é um trocadilho para a expressão "Look at" com o nome de Loki, remetendo à frase "Olhe para a Terra".

Seguindo os princípios da Open Science, os dados e o código estarão disponíveis na plataforma online do github (https://github.com/BrunoComitre/loki-at-earth).

****TRADUÇÃO****
ANHANGÁ: CITIZEN SCIENCE FOR FIRE ALERT

Orbital fire and brush fire monitoring systems are based on the use of low spatial resolution imagery. Thus, fires whose extension is much less than the spatial resolution of the sensor may not be identified. This is the case, for example, with fires that occur in the urban perimeters of municipalities and are very frequent during the dry season. This Project aims to develop a system that allow citizens to register forest and urban fires (citizens as sensors) through a photo that contains a geotag (photo location).

Spatial coordinate data of fires are sent to institutions that are responsible for fighting and conduct law issues. In addition, these citizen science data are useful for validation (checking for errors of omission and commission) of burn monitoring products (burned area and trouble spots).
Other system funcionality is sent warnings of fires that are occurring next a certain location (2 km), such as residence of interested in receiving the alert, airports, protected areas (conservation units and indigenous lands), power transmission lines and others.

The system will sent alerts identified by a caption in the visualization map according to their sources: 1) registers sent by citizens; 2) ocurrences detected by MYD14A1.006 (thermal anomalies and fires); 3) occurrences detected by INPE’s fire monitoring system.
The system consumes the following data:
- MYD09Q1 product (Aqua Surface Reflectance 8-Day L3 Global 250m), for visualizing Earth surface considering the best pixel in the last 8 days
- MYD09GQ product (Aqua Surface Reflectance Daily L2G Global 250m), for visualizing daily Earth surface (with the possibility of cloud cover and lack of images);
- MYD14A1.006 product (Aqua Thermal Anomalies & Fire Daily Global 1km), for visualizing fire location and sent alerts;
- MYD04_L2 product (Aqua Aerosol 5-Min), for visualizing fire smoke;
- Vegetation fires detected during the last 2 hours (all satellites) provided by INPE’s (Brazilian National Institute for Space Research) Queimadas Project, for visualizing fire coordinates detected by satellites other than Aqua and also sent alerts;
- OpenStreetMap (OSM), a collaborative mapping project to make it easy to search places.

The system also displays a spatial-temporal analysis of vegetation fires detected by MODIS/Aqua (reference satellite) during the last 10 year by municipality.

In Norse Mythology, Loki is the god of fire. The group's name is a play on the expression "Look at" with the name of Loki, referring to the phrase "Look at the Earth".

Following the principles of Open Science, the data and code will be available on the github online platform (https://github.com/BrunoComitre/loki-at-earth).

#UrbanFires #VegetationFires #earthobservation #CitizenScience #CitizensAsSensors #MODIS #Aqua #FireMonitoring  #geotag


&nbsp;

## Documentation

All project documentation is located in [Notion](https://www.notion.so/product), and is open for contributions, the access link is: [LOKI AT EARTH](https://www.notion.so/brunocomitre/LOKI-AT-EARTH-e2b784b6fcc34ebfa6eade2544279688)

We have a basic navigation flow between the user and the backend, along with the prediction, which can be updated in:
[FLOW](https://whimsical.com/app-flow-LbDu9wRn42MBA6g3dMiWfw@2Ux7TurymMeBJsVycdo5)


&nbsp;

## Members

- [Adrielly Inocencio](https://www.linkedin.com/in/adrielly-inocencio-4a4007210/) | [@dryinoccencio](https://www.instagram.com/dryinoccencio/)
- [Bruno Alves Comitre](https://www.linkedin.com/in/brunocomitre/) | [@the_comitre](https://www.linkedin.com/in/brunocomitre/)
- [Edgar Miyamoto](https://www.linkedin.com/in/edgarmiyamoto/) | [@miyamotoedgar](https://www.instagram.com/miyamotoedgar/)
- [Fernanda Cristina Guerra](https://www.linkedin.com/in/fernandacguerra/) | [@fer.cris.guerra](https://www.instagram.com/fer.cris.guerra) 
- [Silvia de Jesus](https://www.linkedin.com/in/silviadejesus/) | [@silviadejesus_](https://www.instagram.com/silviadejesus_/) | [Silvia de Jesus](https://www.facebook.com/silvia.crisj/)
- [Vinicius Loiola Beserra](https://www.linkedin.com/in/newearth-6672a026/) | [@viniitz](https://www.instagram.com/viniitz/)

## References

- [FIRMS - Fire Information for Resource Management System](https://firms.modaps.eosdis.nasa.gov/map/#d:24hrs;@-46.9,-22.6,7z)
- [Wildfire Data Resources](https://earthdata.nasa.gov/learn/wildfires-resource-page)
- [MCD64A1 v006 MODIS/Terra+Aqua Burned Area Monthly L3 Global 500 m SIN Grid](https://lpdaac.usgs.gov/products/mcd64a1v006/)
- [Global Imagery Browse Services (GIBS)](https://earthdata.nasa.gov/eosdis/science-system-description/eosdis-components/gibs)
- [Web Service: MODIS/VIIRS Land Products](https://modis.ornl.gov/data/modis_webservice.html)
- [Getting Started with the AρρEEARS API: Submitting and Downloading an Area Request](https://lpdaac.usgs.gov/resources/e-learning/getting-started-with-the-a%CF%81%CF%81eears-api-submitting-and-downloading-an-area-request/)
- [urs.earthdata.nasa.gov/users/new/](https://e4ftl01.cr.usgs.gov/MOTA/MCD64A1.006/?_gl=1*pi0bzx*_ga*MTUxOTgzMDAyOS4xNjMyNzgzMjYz*_ga_0YWDZEJ295*MTYzMzEzNTEzMTE2Mi50bjN1bWt4OC4xLjEuMTYzMzEzNTEzMS4w)
- [Surface Reflectance Global](https://modis.gsfc.nasa.gov/data/dataprod/mod09.php)
- [MODIS Aerosol Product](https://modis.gsfc.nasa.gov/data/dataprod/mod04.php)
- [MODIS Thermal Anomalies/Fire](https://modis.gsfc.nasa.gov/data/dataprod/mod14.php)
- [Programa Queimadas INSTITUTO NACIONAL DE PESQUISAS ESPACIAIS](https://queimadas.dgi.inpe.br/queimadas/portal)
- [openstreetmap](https://www.openstreetmap.org/#map=5/-15.130/-53.189)

Goodchild, M.F. Citizens as sensors: the world of volunteered geography. GeoJournal v. 69, p. 211–221 (2007)

***

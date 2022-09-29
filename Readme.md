# Datenplattform Darmstadt API

[![.github/workflows/openapi_check.yml](https://github.com/t-huyeng/datenplattform-darmstadt-api/actions/workflows/openapi_check.yml/badge.svg)](https://github.com/t-huyeng/datenplattform-darmstadt-api/actions/workflows/openapi_check.yml) [![.github/workflows/schemathesis.yaml](https://github.com/t-huyeng/datenplattform-darmstadt-api/actions/workflows/schemathesis.yaml/badge.svg)](https://github.com/t-huyeng/datenplattform-darmstadt-api/actions/workflows/schemathesis.yaml)

Datenplattform der Wissenschaftsstadt Darmstadt

  Die Datenplattform soll nach Angaben der Digitalstadt Darmstadt GmbH zum Sammeln, Verarbeiten, Vernetzen, Analysieren und Visualisieren von Daten aus dem städtischen Alltag dienen.


  Die Plattform ging im Februar 2021 online und die Kosten sollen sich in den Jahren 2020-2026 auf maximal 6,3 Mio. Euro (!) belaufen. Hierbei ist die Datenplattform nicht Open Source, es sollen allerdings 'einzelne Bestandteile' gesondert als Open Source zur Verfügung gestellt werden [[Quelle](https://www.digitalstadt-darmstadt.de/datenplattform-beteiligung/)].

 ### CORS

  Die Datenplattform verfügt leider nicht über einen `Access-Control-Allow-Origin: *` Header. Daher funktionieren die Testabfragen innerhalb der Swagger UI nicht. Die angegebenen `CURL`-Befehle funktionieren in einer Konsole.


  Zum Testen kann ein kostenloser CORS-Service verwendet werden (siehe Serverauswahl). Dieser CORS-Server wird von imjacobclark zur Verfügung gestellt. Die Abfragegeschwindigkeit ist reduziert [[GitHub](https://github.com/imjacobclark/cors-container)].

  ### [Link zur Datenplattform](https://datenplattform.darmstadt.de/#!/tiles/)





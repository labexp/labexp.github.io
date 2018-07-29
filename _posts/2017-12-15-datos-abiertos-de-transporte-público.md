---
layout: post
title: "Datos abiertos de transporte público"
date: 2017-12-15
---

Los archivos <a href="https://en.wikipedia.org/wiki/General_Transit_Feed_Specification">GTFS (en inglés, General Transit Feed Specification)</a> son un estándar de facto para compartir información de transporte público, por tanto un insumo fundamental para aplicaciones que proveen información detallada para planificar viajes. 

Con la información geoespacial disponible en Open Street map y el horario de los servicios del tren publicados en el sitio web del <a href="http://www.incofer.go.cr/">Incofer</a>, es posible generar un archivo GTFS. Utilizando el script <a href="https://github.com/grote/osm2gtfs">osm2gtfs</a> este proceso es automatizado.

Este archivo <a href="http://ic-itcr.ac.cr/~jgutierrez/incofer/cr-incofer_20171103.zip">GTFS</a> con los datos del servicio de transporte en Tren del INCOFER (a noviembre del 2017) no es un archivo oficial del Incofer y se comparte con una Licencia Libre de Creative Commons <a href="https://creativecommons.org/licenses/by/3.0/cr/">CC-BY </a>. Si en algún momento el Incofer quisiera distribuirlo de forma oficial está en potestad de hacerlo (los invitamos a hacerlo). 

Como se indicó antes, es posible planificar viajes con esta información. La herramienta Transportr a partir de la versión 2.0.0-beta1 incluye esta información. La aplicación puede descargarse siguiendo las indicaciones del sitio web de <a href="https://transportr.grobox.de/">Transportr</a> en el subtítulo "Testing Beta Release".


<table>
  <tr>
    <img src ="http://ic-itcr.ac.cr/~jgutierrez/incofer/transport_beta.png" width=145 height=240 style="margin-left:25px;"/>
    <spam/>
    <img src ="http://ic-itcr.ac.cr/~jgutierrez/incofer/transportr_osm.jpg" width=145 height=240 style="margin-left:25px;"/>
    <spam/>
    <img src ="http://ic-itcr.ac.cr/~jgutierrez/incofer/alajuela_cartago.png" width=145 height=240 style="margin-left:25px;"/>
  </tr>
</table>

Estas herramientas y datos son libres y todos podemos colaborar para mantenerlos funcionando. 

La información geoespacial se gestiona desde Open Stret Map, en la wiki de Open Street Map se creó  <a href= "https://wiki.openstreetmap.org/wiki/ES:Alajuela#Trenes">una página</a> en la que se encuentran enlaces a las rutas mapeadas. Se procura mantener la información actualizada, siguiendo la <a href="https://wiki.openstreetmap.org/wiki/Public_transport">version 2</a> del esquema de mapeo de transporte público.

Dado que el INCOFER actualiza los datos de forma muy frecuente, <a href="https://github.com/labexp/incofer-datos">acá</a> se ha creado un repositorio de github para mantener la información de los horarios del servicio del tren actualizada.


# Veracruz: law history in git

The law of the State of Veracruz (Estado Libre y Soberano de Veracruz de Ignacio de la Llave, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-ver/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

95 ordenamientos with 1045 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE- ANTES CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE VERACRUZ-LLAVE- | 169 | as first published, then each reform: 28 September 1917 to 14 August 2026 |
| `codigo-244-hacendario-para-el-municipio-de-misantla-estado-d/` | CODIGO 244 HACENDARIO PARA EL MUNICIPIO DE MISANTLA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 5 | as first published, then each reform: 1 January 2020 to 29 February 2024 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 87 | as first published, then each reform: 18 September 1932 to 8 April 2025 |
| `codigo-de-procedimientos-administrativos/` | CODIGO DE PROCEDIMIENTOS ADMINISTRATIVOS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 24 | as first published, then each reform: 1 February 2001 to 5 February 2025 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE VERACRUZ | 43 | as first published, then each reform: 15 October 1932 to 4 July 2020 |
| `codigo-financiero/` | CODIGO FINANCIERO PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 65 | as first published, then each reform: 4 April 2001 to 13 January 2026 |
| `codigo-hacendario-municipal/` | CODIGO HACENDARIO MUNICIPAL PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 40 | as first published, then each reform: 1 January 2003 to 11 March 2021 |
| `codigo-hacendario-para-el-municipio-de-cordoba-estado-de-ver/` | CODIGO HACENDARIO PARA EL MUNICIPIO DE CORDOBA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 12 | oldest version available, then each reform: 17 April 2003 to 11 March 2021 |
| `codigo-numero-484-hacendario-para-el-municipio-de-cuichapa-e/` | CODIGO NUMERO 484 HACENDARIO PARA EL MUNICIPIO DE CUICHAPA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 1 January 2024 |
| `codigo-numero-490-hacendario-para-el-municipio-de-cuitlahuac/` | CODIGO NUMERO 490 HACENDARIO PARA EL MUNICIPIO DE CUITLAHUAC ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 25 December 2025 |
| `codigo-numero-531-hacendario-para-el-municipio-de-medellin-e/` | CODIGO NUMERO 531 HACENDARIO PARA EL MUNICIPIO DE MEDELLIN, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 7 | as first published, then each reform: 17 February 2009 to 11 March 2021 |
| `codigo-numero-536-hacendario-para-el-municipio-de-tierra-bla/` | CODIGO NUMERO 536 HACENDARIO PARA EL MUNICIPIO DE TIERRA BLANCA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 8 | as first published, then each reform: 17 February 2009 to 29 December 2023 |
| `codigo-numero-541-hacendario-para-el-municipio-de-boca-del-r/` | CODIGO NUMERO 541 HACENDARIO PARA EL MUNICIPIO DE BOCA DEL RIO, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 19 | as first published, then each reform: 20 February 2003 to 30 December 2022 |
| `codigo-numero-542-hacendario-para-el-municipio-de-orizaba-es/` | CODIGO NUMERO 542 HACENDARIO PARA EL MUNICIPIO DE ORIZABA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 10 | as first published, then each reform: 8 April 2009 to 11 March 2021 |
| `codigo-numero-543-hacendario-para-el-municipio-de-veracruz-e/` | CODIGO NUMERO 543 HACENDARIO PARA EL MUNICIPIO DE VERACRUZ, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 18 | as first published, then each reform: 11 March 2003 to 31 December 2023 |
| `codigo-numero-553-hacendario-para-el-municipio-de-alvarado-e/` | CODIGO NUMERO 553 HACENDARIO PARA EL MUNICIPIO DE ALVARADO, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 11 | as first published, then each reform: 1 January 2007 to 16 August 2024 |
| `codigo-numero-554-hacendario-para-el-municipio-de-xalapa-est/` | CODIGO NUMERO 554 HACENDARIO PARA EL MUNICIPIO DE XALAPA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 12 | as first published, then each reform: 1 January 2007 to 29 December 2023 |
| `codigo-numero-569-hacendario-para-el-municipio-de-emiliano-z/` | CODIGO NUMERO 569 HACENDARIO PARA EL MUNICIPIO DE EMILIANO ZAPATA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 7 | as first published, then each reform: 8 August 2009 to 11 March 2021 |
| `codigo-numero-570-hacendario-para-el-municipio-de-coatzacoal/` | CODIGO NUMERO 570 HACENDARIO PARA EL MUNICIPIO DE COATZACOALCOS DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 9 | as first published, then each reform: 1 January 2004 to 30 December 2022 |
| `codigo-numero-571-hacendario-para-el-municipio-de-minatitlan/` | CODIGO NUMERO 571 HACENDARIO PARA EL MUNICIPIO DE MINATITLAN DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 8 | as first published, then each reform: 1 January 2004 to 29 December 2023 |
| `codigo-numero-577-electoral/` | CODIGO NUMERO 577 ELECTORAL PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 19 | as first published, then each reform: 2 July 2015 to 29 August 2026 |
| `codigo-numero-577-hacendario-para-el-municipio-de-cosoleacaq/` | CODIGO NUMERO 577 HACENDARIO PARA EL MUNICIPIO DE COSOLEACAQUE DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 10 | as first published, then each reform: 5 November 2009 to 11 March 2021 |
| `codigo-numero-711-hacendario-para-el-municipio-de-ixtaczoqui/` | CODIGO NUMERO 711 HACENDARIO PARA EL MUNICIPIO DE IXTACZOQUITLAN, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 29 December 2023 |
| `codigo-numero-712-hacendario-para-el-municipio-de-jaltipan-e/` | CODIGO NUMERO 712 HACENDARIO PARA EL MUNICIPIO DE JALTIPAN, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 1 January 2024 |
| `codigo-numero-726-hacendario-para-el-municipio-de-tlalixcoya/` | CODIGO NUMERO 726 HACENDARIO PARA EL MUNICIPIO DE TLALIXCOYAN, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 27 February 2024 |
| `codigo-numero-734-hacendario-para-el-municipio-de-tlapacoyan/` | CODIGO NUMERO 734 HACENDARIO PARA EL MUNICIPIO DE TLAPACOYAN, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 25 August 2024 |
| `codigo-numero-783-hacendario-para-el-municipio-de-papantla-e/` | CODIGO NUMERO 783 HACENDARIO PARA EL MUNICIPIO DE PAPANTLA, ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 4 | as first published, then each reform: 22 November 2018 to 11 March 2021 |
| `codigo-numero-820-hacendario-para-el-municipio-de-coatepec/` | CODIGO NUMERO 820 HACENDARIO PARA EL MUNICIPIO DE COATEPEC DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 7 | as first published, then each reform: 20 February 2010 to 11 March 2021 |
| `codigo-numero-860-de-derechos/` | CODIGO NUMERO 860 DE DERECHOS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 20 | as first published, then each reform: 1 August 2013 to 9 May 2025 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO LIBRE Y SOBERANO DE VERACRUZ DE IGNACIO DE LA LLAVE | 128 | as first published, then each reform: 1 January 2004 to 11 July 2026 |
| `ley-contra-el-lucro-inmoderado/` | LEY CONTRA EL LUCRO INMODERADO | 5 | as first published, then each reform: 17 November 1946 to 19 April 1968 |
| `ley-contra-el-ruido-en-el-estado-de-veracruz/` | LEY CONTRA EL RUIDO EN EL ESTADO DE VERACRUZ | 2 | as first published, then each reform: 21 October 1942 to 24 August 2018 |
| `ley-de-adquisiciones-arrendamientos-administracion-y-enajena/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS, ADMINISTRACION Y ENAJENACION DE BIENES MUEBLES DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE - LEY NUMERO 539- | 11 | as first published, then each reform: 23 March 2003 to 5 February 2025 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO-PRIVADAS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 5 | as first published, then each reform: 25 October 2014 to 5 February 2020 |
| `ley-de-bienes-del-estado/` | LEY DE BIENES DEL ESTADO | 2 | as first published, then each reform: 1 October 1980 to 14 April 2011 |
| `ley-de-caminos-y-puentes-del-estado/` | LEY DE CAMINOS Y PUENTES DEL ESTADO | 4 | as first published, then each reform: 9 September 1930 to 11 March 2021 |
| `ley-de-campana-para-la-erradicacion-de-la-garrapata-en-la-ga/` | LEY DE CAMPAÑA PARA LA ERRADICACION DE LA GARRAPATA EN LA GANADERIA DEL ESTADO | 1 | as first published: 24 December 1963 |
| `ley-de-fomento-al-empleo/` | LEY DE FOMENTO AL EMPLEO DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 4 | as first published, then each reform: 10 May 2012 to 5 February 2020 |
| `ley-de-fomento-y-proteccion-de-ciudades-industriales-nuevas/` | LEY DE FOMENTO Y PROTECCION DE CIUDADES INDUSTRIALES NUEVAS EN EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 8 February 1972 to 17 April 2003 |
| `ley-de-fomento-y-proteccion-de-la-vainilla/` | LEY DE FOMENTO Y PROTECCION DE LA VAINILLA | 1 | as first published: 13 September 1941 |
| `ley-de-inquilinato/` | LEY DE INQUILINATO | 1 | as first published: 16 September 1937 |
| `ley-de-operaciones-inmobiliarias/` | LEY DE OPERACIONES INMOBILIARIAS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 16 May 2013 to 5 February 2020 |
| `ley-de-prevencion-y-atencion-del-acoso-escolar/` | LEY DE PREVENCION Y ATENCION DEL ACOSO ESCOLAR PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE - ANTES LEY NUMERO 303 CONTRA EL ACOSO ESCOLAR PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE- | 4 | as first published, then each reform: 2 November 2011 to 1 June 2017 |
| `ley-del-ejercicio-profesional/` | LEY DEL EJERCICIO PROFESIONAL PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 12 | as first published, then each reform: 27 December 1963 to 6 December 2019 |
| `ley-del-patronato-de-construcciones-laboratorios-y-equipos-d/` | LEY DEL PATRONATO DE CONSTRUCCIONES, LABORATORIOS Y EQUIPOS DE LA UNIVERSIDAD VERACRUZANA | 1 | as first published: 17 December 1963 |
| `ley-del-seguro-social-de-los-trabajadores-de-la-educacion/` | LEY DEL SEGURO SOCIAL DE LOS TRABAJADORES DE LA EDUCACION DEL ESTADO DE VERACRUZ - LEY NUMERO 4- | 1 | as first published: 18 May 1967 |
| `ley-del-servicio-publico-de-carrera-en-la-administracion-pub/` | LEY DEL SERVICIO PUBLICO DE CARRERA EN LA ADMINISTRACION PUBLICA CENTRALIZADA DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 9 December 2003 to 31 December 2016 |
| `ley-estatal-de-proteccion-ambiental/` | LEY ESTATAL DE PROTECCION AMBIENTAL | 16 | as first published, then each reform: 1 July 2000 to 11 July 2026 |
| `ley-ganadera/` | LEY GANADERA PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 9 | as first published, then each reform: 1 June 1979 to 16 July 2021 |
| `ley-no-860-del-servicio-profesional-de-carrera-del-congreso/` | LEY NO. 860 DEL SERVICIO PROFESIONAL DE CARRERA DEL CONGRESO DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 23 September 2004 |
| `ley-num-259-que-establece-el-arancel-para-el-cobro-de-honora/` | LEY NUM. 259 QUE ESTABLECE EL ARANCEL PARA EL COBRO DE HONORARIOS DE LOS ABOGADOS POSTULANTES, DEPOSITARIOS, PERITOS MEDICOS, PERITOS VALUADORES, ARBITROS, INTERPRETES Y TRADUCTORES | 1 | as first published: 6 September 1974 |
| `ley-numero-11-de-austeridad/` | LEY NUMERO 11 DE AUSTERIDAD PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 31 December 2018 |
| `ley-numero-113-de-salud/` | LEY NUMERO 113 DE SALUD DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 37 | as first published, then each reform: 17 August 1988 to 19 December 2020 |
| `ley-numero-12-de-planeacion/` | LEY NUMERO 12 DE PLANEACION DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 29 December 2018 to 19 December 2025 |
| `ley-numero-139-que-establece-las-bases-normativas-a-que-se-s/` | LEY NUMERO 139 QUE ESTABLECE LAS BASES NORMATIVAS A QUE SE SUJETARAN LOS REGLAMENTOS EN MATERIA DE FALTAS DE POLICIA QUE EXPIDAN LOS AYUNTAMIENTOS DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 17 July 1988 to 8 August 2005 |
| `ley-numero-21-de-aguas/` | LEY NUMERO 21 DE AGUAS DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 11 | as first published, then each reform: 30 June 2001 to 5 February 2020 |
| `ley-numero-21-para-prevenir-y-sancionar-la-tortura-en-el-est/` | LEY NUMERO 21 PARA PREVENIR Y SANCIONAR LA TORTURA EN EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 2 May 1999 to 17 April 2003 |
| `ley-numero-224-del-instituto-veracruzano-de-desarrollo-munic/` | LEY NUMERO 224 DEL INSTITUTO VERACRUZANO DE DESARROLLO MUNICIPAL | 2 | as first published, then each reform: 2 February 2008 to 18 September 2021 |
| `ley-numero-230-de-mecanismos-alternativos-de-solucion-de-con/` | LEY NUMERO 230 DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 25 January 2025 |
| `ley-numero-231-organica-del-poder-judicial/` | LEY NUMERO 231 ORGANICA DEL PODER JUDICIAL DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 30 January 2025 to 29 August 2026 |
| `ley-numero-233-de-obras-publicas-y-servicios-relacionados-co/` | LEY NUMERO 233 DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON ELLAS DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 5 February 2025 to 25 July 2026 |
| `ley-numero-233-para-el-establecimiento-y-desarrollo-de-zonas/` | LEY NUMERO 233 PARA EL ESTABLECIMIENTO Y DESARROLLO DE ZONAS ECONOMICAS ESPECIALES DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 24 January 2017 |
| `ley-numero-235-de-acceso-de-las-mujeres-a-una-vida-libre-de/` | LEY NUMERO 235 DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 22 | as first published, then each reform: 29 February 2008 to 3 July 2026 |
| `ley-numero-236-para-la-declaracion-especial-de-ausencia-por/` | LEY NUMERO 236 PARA LA DECLARACION ESPECIAL DE AUSENCIA POR DESAPARICION DE PERSONAS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 21 March 2019 |
| `ley-numero-24-para-la-transferencia-de-funciones-y-servicios/` | LEY NUMERO 24 PARA LA TRANSFERENCIA DE FUNCIONES Y SERVICIOS PUBLICOS DEL ESTADO A LOS MUNICIPIOS | 1 | as first published: 1 August 2001 |
| `ley-numero-240-para-el-otorgamiento-de-pensiones-a-deudos-de/` | LEY NUMERO 240 PARA EL OTORGAMIENTO DE PENSIONES A DEUDOS DE INTEGRANTES DE LAS FUERZAS ARMADAS CAIDOS EN CUMPLIMIENTO DEL DEBER | 1 | as first published: 19 February 2011 |
| `ley-numero-241-de-desarrollo-urbano-ordenamiento-territorial/` | LEY NUMERO 241 DE DESARROLLO URBANO, ORDENAMIENTO TERRITORIAL Y VIVIENDA PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 11 | as first published, then each reform: 14 April 2011 to 5 February 2025 |
| `ley-numero-247-de-educacion/` | LEY NUMERO 247 DE EDUCACION DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 20 | as first published, then each reform: 8 March 2014 to 5 February 2020 |
| `ley-numero-247-del-registro-publico-de-la-propiedad/` | LEY NUMERO 247 DEL REGISTRO PUBLICO DE LA PROPIEDAD PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 24 May 2008 |
| `ley-numero-249-de-la-gaceta-oficial-del-gobierno/` | LEY NUMERO 249 DE LA GACETA OFICIAL DEL GOBIERNO DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 16 July 2005 to 30 August 2007 |
| `ley-numero-25-de-autonomia-de-la-universidad-veracruzana/` | LEY NUMERO 25 DE AUTONOMIA DE LA UNIVERSIDAD VERACRUZANA | 2 | as first published, then each reform: 1 December 1996 to 29 June 2000 |
| `ley-numero-250-de-transparencia-y-acceso-a-la-informacion-pu/` | LEY NUMERO 250 DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 1 July 2025 |
| `ley-numero-251-de-proteccion-de-datos-personales-en-posesion/` | LEY NUMERO 251 DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 1 July 2025 |
| `ley-numero-259-de-adopciones/` | LEY NUMERO 259 DE ADOPCIONES PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 21 June 2011 to 4 July 2020 |
| `ley-numero-259-de-victimas/` | LEY NUMERO 259 DE VICTIMAS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 5 April 2017 to 8 March 2025 |
| `ley-numero-271-de-desarrollo-integral-de-la-juventud/` | LEY NUMERO 271 DE DESARROLLO INTEGRAL DE LA JUVENTUD PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 6 | as first published, then each reform: 16 August 2005 to 11 September 2020 |
| `ley-numero-271-de-fomento-a-las-actividades-de-desarrollo-so/` | LEY NUMERO 271 DE FOMENTO A LAS ACTIVIDADES DE DESARROLLO SOCIAL DE LAS ORGANIZACIONES CIVILES PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE -ANTES VERACRUZ-LLAVE- | 4 | as first published, then each reform: 12 February 2002 to 10 February 2016 |
| `ley-numero-272-que-crea-el-instituto-de-la-policia-auxiliar/` | LEY NUMERO 272 QUE CREA EL INSTITUTO DE LA POLICIA AUXILIAR Y PROTECCION PATRIMONIAL PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 13 August 2005 to 4 July 2013 |
| `ley-numero-276-de-ingresos-del-gobierno/` | LEY NUMERO 276 DE INGRESOS DEL GOBIERNO DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-276-que-crea-la-universidad-popular-autonoma-de-v/` | LEY NUMERO 276 QUE CREA LA UNIVERSIDAD POPULAR AUTONOMA DE VERACRUZ | 3 | as first published, then each reform: 4 August 2011 to 15 January 2026 |
| `ley-numero-28-que-regula-el-procedimiento-para-fijar-las-cuo/` | LEY NUMERO 28 QUE REGULA EL PROCEDIMIENTO PARA FIJAR LAS CUOTAS, TARIFAS Y TABLAS DE VALORES UNITARIOS DE LAS CONTRIBUCIONES SOBRE LA PROPIEDAD INMOBILIARIA | 1 | as first published: 28 September 2001 |
| `ley-numero-287-de-pensiones/` | LEY NUMERO 287 DE PENSIONES DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 22 July 2014 to 13 November 2015 |
| `ley-numero-29-de-premios/` | LEY NUMERO 29 DE PREMIOS DEL ESTADO DE VERACRUZ | 10 | as first published, then each reform: 13 October 2001 to 28 February 2020 |
| `ley-numero-290-para-el-otorgamiento-de-beneficios-a-deudos-d/` | LEY NUMERO 290 PARA EL OTORGAMIENTO DE BENEFICIOS A DEUDOS DE INTEGRANTES DE LAS INSTITUCIONES DE SEGURIDAD PUBLICA DEL ESTADO CAIDOS EN CUMPLIMIENTO DEL DEBER, DEL ESTADO DE VERACRUZ | 2 | as first published, then each reform: 30 August 2011 to 24 November 2017 |
| `ley-numero-296-del-himno-al-estado-de-veracruz-de-ignacio-de/` | LEY NUMERO 296 DEL HIMNO AL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 3 December 2005 to 5 February 2020 |
| `ley-numero-301-de-desarrollo-social-y-humano/` | LEY NUMERO 301 DE DESARROLLO SOCIAL Y HUMANO PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 4 | as first published, then each reform: 2 November 2011 to 17 August 2019 |
| `ley-numero-306-para-enfrentar-la-epidemia-del-vih-sida-en-el/` | LEY NUMERO 306 PARA ENFRENTAR LA EPIDEMIA DEL VIH-SIDA EN EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 26 December 2008 to 18 December 2017 |
| `ley-numero-309-para-la-administracion-de-bienes-asegurados-d/` | LEY NUMERO 309 PARA LA ADMINISTRACION DE BIENES ASEGURADOS, DECOMISADOS O ABANDONADOS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 1 | as first published: 1 December 2014 |
| `ley-numero-327-para-la-proteccion-de-los-no-fumadores/` | LEY NUMERO 327 PARA LA PROTECCION DE LOS NO FUMADORES DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 2 | as first published, then each reform: 11 March 2012 to 5 February 2020 |
| `ley-numero-336-para-la-entrega-y-recepcion-del-poder-ejecuti/` | LEY NUMERO 336 PARA LA ENTREGA Y RECEPCION DEL PODER EJECUTIVO Y LA ADMINISTRACION PUBLICA MUNICIPAL | 2 | as first published, then each reform: 17 October 2017 to 25 November 2025 |
| `ley-numero-348-del-sistema-estatal-anticorrupcion-de-veracru/` | LEY NUMERO 348 DEL SISTEMA ESTATAL ANTICORRUPCION DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 22 November 2017 to 20 December 2022 |
| `ley-numero-364-de-fiscalizacion-superior-y-rendicion-de-cuen/` | LEY NUMERO 364 DE FISCALIZACION SUPERIOR Y RENDICION DE CUENTAS DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 9 | as first published, then each reform: 19 December 2017 to 25 July 2026 |
| `ley-numero-364-estatal-del-servicio-civil-de-veracruz/` | LEY NUMERO 364 ESTATAL DEL SERVICIO CIVIL DE VERACRUZ | 9 | as first published, then each reform: 4 April 1992 to 31 December 2016 |
| `ley-numero-366-de-responsabilidades-administrativas/` | LEY NUMERO 366 DE RESPONSABILIDADES ADMINISTRATIVAS PARA EL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE | 3 | as first published, then each reform: 22 December 2017 to 20 December 2022 |
| `ley-numero-367-organica-del-tribunal-de-justicia-administrat/` | LEY NUMERO 367 ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE VERACRUZ -- ANTES LEY NUMERO 367 ORGANICA DEL TRIBUNAL ESTATAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE VERACRUZ DE IGNACIO DE LA LLAVE -- | 5 | as first published, then each reform: 22 December 2017 to 19 July 2023 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication, the state rule SCJN cites.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.

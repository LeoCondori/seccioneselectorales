# Bienvenido  API Secciones electorales!
En la siguiente documentación aprenderás a consumir esta API con el objetivo de recuperar la **sección electoral** a partir de la **localidad**.


# API
A continuación vamos a conocer todos los recursos disponibles.

## [GET] Secciones 
Para obtener todas las **Secciones Electorales** simplemente deberás hacer un GET a la siguiente URL.

**[https://api.shippinggroup.net/secciones/]**

## [GET] Partidos

Para obtener todos los **Partidos** simplemente deberás hacer un GET a la siguiente URL.

**[https://api.shippinggroup.net/secciones/partidos]**

## [GET] Localidades

Para obtener todos los **Localidades** simplemente deberás hacer un GET a la siguiente URL.
**[https://api.shippinggroup.net/secciones/localidades]**

## [GET] Sección electoral predictor

Ahora es posible utilizar la API **seccion_predictor** para conocer la sección electoral.
[https://api.shippinggroup.net/secciones/seccion_predictor/{localidad}]

**[https://api.shippinggroup.net/secciones/seccion_predictor/budge]**

# Respuestas

Todas las respuestas serán un objeto JSON.

## Secciones electorales
[{
	    "id": "1",
	    "descripcion": "Primera Seccion electoral",
	    "fec_ult_act": "2019-07-09 21:25:25"
 },...]

## Partidos
  [{
    "ID": "1",
    "descripcion": "Campana",
    "fk_seccion_electoral": "1",
    "fec_ult_act": "2019-07-09 21:27:57"
  },...]
  
## Localidades
[{
    "ID": "1",
    "descripcion": "Campana",
    "fk_partidos": "1",
    "fec_ult_act": "2019-07-09 21:31:26"
  },...]
## Seccion Predictor
[
  {
    "PARTIDO": "Lomas de Zamora",
    "LOCALIDAD": "Ingeniero Budge",
    "SECCION_ELECTORAL": "Tercera Sección electoral"
  }
]

## Por: Leo Condorí

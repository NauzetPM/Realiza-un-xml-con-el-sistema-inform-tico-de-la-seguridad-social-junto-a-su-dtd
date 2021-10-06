# Realiza un xml con el sistema informático de la seguridad social junto a su dtd


Lo primero que hice para realizar es XML fue el DTD nombrando todas las etiqueta que he usado y que tipo de dato guarda dentro en este caso todos son de texto.
Utilizando los comandos 

< ?xml version="1.0" encoding="UTF-8" standalone="yes" ?>

< !DOCTYPE address [
  
	<!ELEMENT (Nombre de la etiqueta) (Nombre de las subetiquetas que hay dentro)

< !ELEMENT (nombre etiqueta) (#PCDATA) ← siendo el tipo de dato que voy a almacenar en este caso texto

Y asi con todas las etiquetas que coloque después empece el XML con la etiqueta 

< SeguridadSocia l> que tendría la subetiqueta < InformacionPersonal > que esta a su ves tendría la subetiqueta < Afiliados > y esta tendria la etiqueta < Afiliado > y 

esta tendría varias etiquetas que serian < DNI > ,< Nombre >, < Apellidos >, 

< SituacionLaboral > , < FechaNacimiento > ,< BajasLaborales > y  < PrestacionesCobradas >.

Que de estas algunas tendrían directamente datos como  < DNI > , < Nombre > y

< SituacionLaboral >.

Y otras que tendrían otras subetiquetas como :

< Apellidos > tendría: < Primer > y < Segundo >.

< FechaNacimiento > tendría: < dia >.< mes > y < anio >.

< BajasLaborales > tendría: < numerobajas >, < causa >, < FechaInicio > y 
< FechaFinal >.

y por ultimo la etiqueta< PrestacionesCobradas > tendría: < prestacion >, 
< FechaInicio > y < FechaFinal >.


![1](https://user-images.githubusercontent.com/91209288/136267476-def68ce6-a883-4ded-9648-75f129fe91ce.PNG)
![2](https://user-images.githubusercontent.com/91209288/136267488-3b0bf587-c7b5-42a8-8e2a-d8a8d0ce337c.PNG)


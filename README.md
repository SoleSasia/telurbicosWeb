# Telúrbicos Web

Sitio web para muralistas. Predominan carrouseles.

## Requerimientos generales
  + gestión de imágenes: optimización, almacenamiento (crud)
  	+ Cloudinary ==> implementado en Angular o en Spring boot?
    
  + mapa: crud ubicación de murales
  	+ Mapbox, leaflet? ==> 
    
  + gestión de datos: crud de información murales y artistas (cv)

  + login: jwt

  + gestión de contacto


## Secciones

### Home
  + slider/carousel automático (5 imágenes) con enlace a murales
___  
### Murales => contiene subsecciones
  + Murales Telúrbicos: 1 carousel x mural
  + Homenajes: idem
  + Otros Murales: idem
  + Mapa: ubicación de cada mural
___
### Prensa
  + Listado con enlace a artículos, entrevistas, etc.
___
### Nosotres
  + Ella:
  	+ Foto perfil
  	+ Breve descripcion
  	+ enlace a redes
  + Él: idem 
___
### Contacto
  + Formulario de contacto
	+ Nombre
	+ Email
	+ Asunto
	+ Mensaje 

## Decisiones

+ Fontend: Angular
	+ mobile first
+ Backend: Spring Boot o TS en Angular?
+ DB: Firebase, ?
___

## DER v2

![DER_telurbicos_v2](https://user-images.githubusercontent.com/101983696/194319921-ac069a18-b82d-42f5-99af-41cb067360d2.jpg)




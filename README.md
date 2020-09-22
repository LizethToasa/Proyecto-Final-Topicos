# Proyecto Final

# Integrantes:
- Jhonatan Pizarra
- Alfonso Heredia
- Lizeth Toasa

**Link de Youtube:**\
https://www.youtube.com/watch?v=EKjA91SmhnU&t=68s


Desarrollar una aplicación que muestre información de canciones al buscarlas, puede usar
el API REST de Spotify: https://developer.spotify.com/documentation/web-api/

La apllicación permitira guardar en la cuenta de firebase:
- Historial de búsqueda por usuario y su geolocalización.
- Historial de los 4 países consultados por el usuario y su geolocalización.
- Historial de canciones por usuario y su geolocalización.

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/spotify-logo.png)
# Api Spotify

Las aplicaciones de Spotify son básicamente aplicaciones web integradas en el navegador basado en Chromium y bajo el sandbox que incluye Spotify. Siguiendo el modelo Apple han creado una tienda donde descargar las aplicaciones, lo cual implica que no somos libres de descargar cualquier aplicaciones, sólo las que Spotify apruebe. De hecho, incluso las que estamos desarrollando hay que cargarla de nuevo cada vez que cerramos el reproductor

# Obtener enlace de Api Spotify
Lo primero que tenemos que hacer es registrarnos en API Spotify y crear una cuenta que nos permita usar tener acceso a nuestra api

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/1.png)

Luego de crear nuestro proyecto obtenemos Clave id secret

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/a.png)

Realizamos pruebas para la realización de token con la ayuda de POSTMAN

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/2.png)


# Registro

Procedemos a registrar Logeo de la siguiente forma

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/4.png)

Verifica el correo electrónico

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/5.png)

Comprobamos el login para iniciar sesión 

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/6.png)

Nos da la bienvenida 

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/7.png)

Comprobamos el formulario de registro

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/8.png)

Nos envía un correo de autentificación antes de validar el acceso 

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/9.png)

Ingresamos la contraseña para culminar nuestro registro

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/10.png)

Lugo de verificar nuestra contraseña procedemos a iniciar sesión 

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/11.png)

Y nos da la bienvenida

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/12.png)

# Recuperar contraseña

En el caso que deseemos recuperar la contraseña nuestra contraseña ingresamos damos clic en recuperar contraseña e ingresamos nuestro correo electrónico 

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/13.png)


Al enviar nos aparece el mensaje para confirmar recuperación de contraseña

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/14.png)

Nos llega una verificación a nuestro correo electrónico en la cual debemos dar aceptar

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/15.png)

Nos envía a una página donde ingresamos nuestra nueva contraseña y la ingresamos

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/16.png)

# Generar token

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/17.png)


![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/199.png)


![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/20.png)


![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/21.png)


![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/22.png)


![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/23.png)

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/24.png)

# Después del token logeo

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/25.png)

# Generar apk

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/26.png)


# Cambiar nombre

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/28.png)

login

![Calculadora](https://github.com/LizethToasa/Proyecto-Final-Topicos/blob/master/topicos/30.png)

# Funcionalidad móvil
Después de crear un usario nos logeamos en la aplicación se nos presentara las canciones que esten en tendencia

![image](https://user-images.githubusercontent.com/23488888/93938407-cf62dc00-fcee-11ea-80e1-f7b4b36f11e7.png)

En el menu podemos buscar la canción o artista deseado

![image](https://user-images.githubusercontent.com/23488888/93938608-210b6680-fcef-11ea-8d3b-d221f7b880fc.p

Tener en cuenta de permitir activar la ubiccion para poder realizar la buqueda y se guarde en la coleccion de la base de datos de firebase

![image](https://user-images.githubusercontent.com/23488888/93938756-5a43d680-fcef-11ea-82fd-7e0122ab844f.png)

# Firebase

En Firebase podemos ver que se va ir uardando los usuarios creados en este caso de tipo invitado

![image](https://user-images.githubusercontent.com/23488888/93938857-895a4800-fcef-11ea-8a06-e96c151190dc.png)

El usuario de tipo administrador

![image](https://user-images.githubusercontent.com/23488888/93938930-a55de980-fcef-11ea-8e12-b917ab574f7b.png)

Tambien podremos ver las busquedas que se realizo y dónde se lo realizo

![image](https://user-images.githubusercontent.com/23488888/93939055-d2aa9780-fcef-11ea-9871-a362d9f4bf9d.png)

Se visualiza tambien de los paises dónde se hizo la busqueda

![image](https://user-images.githubusercontent.com/23488888/93939139-f40b8380-fcef-11ea-9ab6-1678c943be7a.png)

# Funcionalidad web(Administrador)

Se ingresa el usuario administrador

![image](https://user-images.githubusercontent.com/23488888/93939243-1e5d4100-fcf0-11ea-8f0b-605492c97ab0.png)

Se podra visualizar las busqueda de los usuarios ingresados y registrados

![image](https://user-images.githubusercontent.com/23488888/93939344-46e53b00-fcf0-11ea-937d-f08980b73f10.png)

Al seleccionar algun usuario nos mostrara con mas detalle y ahi podremos modificarlo y guardar o eliminarlo

![image](https://user-images.githubusercontent.com/23488888/93939399-5ebcbf00-fcf0-11ea-914e-02a6f911c629.png)

Iremos al menú y ahora buscaremos por historial de búsqueda

![image](https://user-images.githubusercontent.com/23488888/93939550-90358a80-fcf0-11ea-8be8-a8da4bcdae35.png)

Se nos presentara todos los usuarios registrados y la cancion qu buscaron y en dónde

![image](https://user-images.githubusercontent.com/23488888/93939614-acd1c280-fcf0-11ea-90bc-b760befe3ed9.png)

Y aqui nos mostrara la busqueda por paises 

![image](https://user-images.githubusercontent.com/23488888/93939715-dab70700-fcf0-11ea-9238-eafbd355d6e5.png)


**Refrencias:**

*Tutorial en Youtube:* https://www.youtube.com/watch?v=EKjA91SmhnU&t=68s

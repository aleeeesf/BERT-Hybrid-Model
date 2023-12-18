# Análisis de Sentimientos en Redes Sociales con Modelo Híbrido BERT
Este repositorio contiene la implementación de un modelo híbrido para el análisis de sentimientos en tweets en español. El modelo combina las características textuales obtenidas mediante BERT con metadatos de las publicaciones, mejorando así la capacidad de capturar tanto información semántica como contextual.

## Estructura del Conjunto de Datos
El conjunto de datos es de uso privativo, no disponible por el momento. Este consta de 6078 registros de tweets en español. Cada registro tiene los siguientes atributos:

+ favorite_count: Número de "me gusta" que ha recibido el tweet.
+ retweet_count: Número de veces que el tweet ha sido retuiteado.
+ user_followers_count: Cantidad de seguidores del usuario que publicó el tweet.
+ user_friends_count: Cantidad de usuarios seguidos por el usuario.
+ user_favourites_count: Número de tweets marcados como favoritos por el usuario.
+ user_statuses_count: Cantidad total de tweets publicados por el usuario.
+ user_verified: Indica si el usuario está verificado o no.
+ user_has_extended_profile: Indica si el usuario tiene un perfil extendido.
+ user_default_profile: Indica si el usuario utiliza el perfil predeterminado.
+ preprocessed: Texto preprocesado del tweet.

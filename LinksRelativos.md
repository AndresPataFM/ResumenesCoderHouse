A varios les cuesta el tema de links relativos asi que les dejo una explicacion aca por si no lo entienden en su totalidad en clase. Primero las reglas básicas:

* Al utlilizar ./ te estas dentro de la misma carpeta del archivo donde escribis el link (este se puede obviar pero sirve mucho para activar el emmet y de practica, yo lo sigo usando)
* Al poner ./# (donde # es el nombre de una carpeta) te moverias dentro de una carpeta
* Al poner ../ salis de la carpeta donde estas a la carpeta que contiene la carpeta donde esta
* Al acoplar cosas, no se ponen los puntos de las reglas 1 y 2


Ahora a un par de ejemplos (vean la img), sepan que no uso extensiones en el ejemplo pero son necesarias el 99% de los casos (no voy a mostrar excepciones), visualicenlo como

Quiero linkear en el index a la img3 (imagen 2), desde index tengo que entrar a la carpeta img y el archivo donde estoy esta situado en la carpeta root, por lo tanto el link relativo seria ./img/img3
Quiero linkear img1 a gallery (imagen 3 que puse), desde gallery, tengo que salir de pages a root, entrar a img y ahi llego a img1, el link se ve ./../img/img1
Quiero linkear el index con el logo, como estan al mismo nivel es ./logo
Quiero linkear aboutUs con el index, desde aboutUS se ve ./../index pero desde index se ve ./pages/aboutUs


Se llaman links relativos porqu lo importante es la posicion relativa de un archivo con el otro
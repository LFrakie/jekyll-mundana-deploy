## Ruta absoluta
Tuvimos problemas con la ruta abusoluta y eso rompia la pagina sin mostrar las paginas, estilos, imagenes y problemas para poder
ingresar a las rutas, eso lo solucionamos con en _config.yml cambiando la base URL que no coincidia con el de github pages

#baseurl: '/mundana-theme-jekyll'

baseurl: '/jekyll-mundana-deploy'

-----

eso ayudó a solucionar el problema.

-----


## Imagen Rota en develop
Otro problemita que teniamos era que teniamos la segunda **imagen** despues de **latest** rota, por lo que decidimos modficiar un codigo en:
la linea 57 de index.html




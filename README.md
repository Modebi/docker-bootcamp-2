# Día 2 aprendiendo Docker en bootcamp

Hacer build de cada una de las imágenes:


`
docker build . -t adminserver-0.0.1
`

En nuestro docker-compose.yml tenemos configurado el bindeo de puertos y hacemos referencia a las imágenes que ya hemos construido.

Ejecutar el docker-compose:


`
docker-compose up
`

Ver que tenemos los contenedores arrancados:


`
docker ps
`

Apagar el docker-compose:


`
docker-compose down
`



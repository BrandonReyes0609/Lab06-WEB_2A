### Link del repositorio anterior:
https://github.com/BrandonReyes0609/lab_5-API-WEB.git

1. Dirigete al directorio lab06-SW y ejecuta: 

`docker build -t blog-brandon-db .`

2.  - Luego ejecuta el siguiente ejecuta:

`docker run --name brandon-db -e MYSQL_ROOT_PASSWORD=toor -e MYSQL_DATABASE=post_db -e MYSQL_USER=brandon -e MYSQL_PASSWORD=123 -p 3306:3306 -d blog-brandon-db`


3. Inicia el contendor
`docker start brandon-db`

4.  - Una vez hayas ejecutado sin errores la locationUn de docker, ejecuta:

`npm start`

5.  - Para probar el lint [Errores]
`npm run lint`

1. Detén el contenedor:

`docker stop brandon-db`

2. Elimina el contenedor:

`docker rm brandon-db`

3. Elimina la imagen:

`docker rmi blog-brandon-db`

### Link Pagina
https://heroic-malabi-23a460.netlify.app/


![menu](https://github.com/BrandonReyes0609/Lab06-WEB_2A/assets/101024720/6d807d38-55c2-4b1a-a15c-e74fa1a252ed)


## /POST

![POST](https://github.com/BrandonReyes0609/lab_5-API-WEB/assets/101024720/6f78350e-fa8c-4539-b14f-b6634c096dca)

## /GET

![GET1](https://github.com/BrandonReyes0609/lab_5-API-WEB/assets/101024720/4b7ae5fe-29d4-44c6-84c3-815a43c85cd7)

## /DELETE

![DELETE](https://github.com/BrandonReyes0609/lab_5-API-WEB/assets/101024720/061a9928-e868-4bd9-80fb-c28dfbecb431)

## /GET despues /DELETE

![GET despues DELETE](https://github.com/BrandonReyes0609/lab_5-API-WEB/assets/101024720/da3292e1-67d2-4eb1-8d29-b4789e6adc05)



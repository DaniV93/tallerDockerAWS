# tallerDockerAWS
 
Por supuesto, aquí está el resumen del taller en tercera persona:

1. **Creación de la aplicación web**: Se utilizó el micro-framework Spark Java para desarrollar una pequeña aplicación web. Este marco es ideal para crear aplicaciones rápidas y eficientes con un mínimo de configuración.
![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/426c9535-2b59-4374-afed-35ef556b2423)

Ejecutandose en local:
![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/de471bb8-d2f4-4007-bf24-fa6c1044724d)

![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/579cfb8a-7b5d-47ff-8f7b-010021b20073)

2. **Construcción del contenedor Docker**: Una vez que la aplicación estuvo lista, se procedió a construir un contenedor Docker para ella. Docker permite empaquetar una aplicación con todas sus dependencias en un contenedor, lo que garantiza que la aplicación funcionará sin problemas en cualquier entorno.
![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/4993df83-0f7c-4ddd-b532-b6800a970b55)


3. **Despliegue local del contenedor**: Se desplegó y configuró el contenedor Docker en la máquina local para probar su funcionamiento.
![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/6121105e-9121-48f4-b208-8da17e41b207)

4. **Creación del repositorio en DockerHub**: Se creó un repositorio en DockerHub, una plataforma de alojamiento de contenedores Docker. Esto permitió almacenar y compartir la imagen Docker.

![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/327ce6d7-332a-4238-88ad-37afa436a371)

5. **Subida de la imagen al repositorio**: Se subió la imagen Docker de la aplicación al repositorio creado en DockerHub. Esto permitió acceder a la imagen desde cualquier lugar y compartirla con otros.

6. **Creación de la máquina virtual en AWS**: Se creó una máquina virtual en Amazon Web Services (AWS). AWS es una plataforma de servicios en la nube que ofrece una amplia gama de productos como servidores virtuales, almacenamiento en la nube, bases de datos, etc.

7. **Instalación de Docker en la máquina virtual**: Se instaló Docker en la máquina virtual de AWS. Esto permitió desplegar contenedores Docker en la máquina.

![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/87502c45-ecef-4499-bfdd-193576d47274)


8. **Despliegue del contenedor en AWS**: Finalmente, se desplegó el contenedor Docker en la máquina virtual de AWS. Esto permitió acceder a la aplicación web desde cualquier lugar a través de la URL proporcionada por AWS.

![image](https://github.com/DaniV93/tallerDockerAWS/assets/124316934/bcdb15ff-c992-4318-8c6e-d61908c5c380)

En cuanto a la arquitectura, este taller permitió experimentar con una arquitectura basada en microservicios. En este tipo de arquitectura, las aplicaciones se dividen en componentes más pequeños e independientes (microservicios) que se ejecutan en sus propios contenedores Docker. En este caso Se creó la aplciación web y se ejecutó en la nube de aws como un microservicio.

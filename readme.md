Requisitos
Java 21 o superior
Maven 3.8.2 o superior

Instalación
Para instalar la aplicación, siga estos pasos:

Clone el repositorio de GitHub:
git clone https://github.com/soycamiloypunto/apiregistrousuarios_v3.git


2. Cambie al directorio de la aplicación:

cd apiregistrousuarios_v3


3. Ejecute el siguiente comando para compilar la aplicación:

mvn clean install


4. Ejecute el siguiente comando para iniciar la aplicación:

mvn spring-boot:run


## Uso

La aplicación proporciona las siguientes rutas HTTP:

* `/api/user/all`: Lista los usuarios
* `/api/user/createUser`: Crea un nuevo usuario
* `/api/users/{id}`: Obtiene un usuario por ID
* `/api/users/deleteUser`: Elimina un usuario

Para obtener más información sobre cómo usar la aplicación, consulte la documentación.

## Documentación

`target/generated-docs`

## Autor

Esta aplicación fue creada por Cristian Camilo Tabares V.

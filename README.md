#  Proyecto MongoDB - Gestión de Estudiantes

##  Autor

Kevin Luengas

---

##  Descripción del Proyecto

Este proyecto consiste en la creación de un sistema CRUD (Crear, Leer, Actualizar y Eliminar) para la gestión de estudiantes utilizando **Python** y **MongoDB**.

Se implementa un menú interactivo en consola que permite:

* Insertar estudiantes
* Listar estudiantes
* Actualizar la edad de un estudiante
* Eliminar estudiantes

---

##  Tecnologías utilizadas

* Python
* PyMongo
* MongoDB Atlas
* MongoDB Compass

---

##  Interacción con MongoDB Atlas

Para este proyecto se utilizó MongoDB Atlas como servicio de base de datos en la nube.

### Pasos realizados:

1. Se creó un cluster en MongoDB Atlas.
2. Se generó un usuario y contraseña para la conexión.
3. Se configuró el acceso de red (IP access) para permitir conexiones.
4. Se obtuvo la cadena de conexión (`connection string`).
5. Se conectó Python a la base de datos usando **PyMongo**:

```python
from pymongo import MongoClient
cliente = MongoClient("mongodb+srv://<usuario>:<password>@cluster.mongodb.net/")
```

6. Se creó la base de datos:

```
BD_CursoMongo
```

7. Se creó la colección:

```
Estudiantes
```

---

##  Interacción con MongoDB Compass

También se utilizó MongoDB Compass para visualizar y gestionar los datos de forma gráfica.

### Actividades realizadas:

* Conexión a la misma base de datos usando la cadena de conexión
* Visualización de la base de datos `BD_CursoMongo`
* Consulta de la colección `Estudiantes`
* Verificación de los documentos insertados desde Python
* Pruebas manuales de inserción y eliminación de datos

---

##  Ejecución del programa

El programa funciona mediante un menú interactivo en consola:

```
 MENÚ DE ESTUDIANTES 
1. Insertar estudiante
2. Listar estudiantes
3. Actualizar edad
4. Eliminar estudiante
5. Salir
```

El usuario puede ingresar datos mediante `input()` y realizar operaciones directamente en la base de datos.

---

##  Ejemplos de uso

* Se insertaron datos de compañeros como prueba
* Se listaron los estudiantes almacenados
* Se actualizó la edad de algunos registros
* Se eliminaron estudiantes específicos

---

##  Link del repositorio

(Aquí debes pegar el link de tu repositorio de GitHub)

Ejemplo:

```
https://github.com/tu-usuario/tu-repositorio
```

---

##  Conclusiones

* Se logró conectar Python con MongoDB en la nube correctamente.
* Se implementó un sistema CRUD funcional.
* Se comprendió el uso de bases de datos NoSQL.
* Se utilizó MongoDB Compass para validar visualmente los datos.

---

##  Nota de seguridad

Se recomienda no subir credenciales reales (usuario y contraseña) al repositorio público. En su lugar, usar variables de entorno.

---

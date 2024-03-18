# API de Gestión de Tareas (To-Do) utilizando JSON Server en Render.com

Este repositorio contiene un simple servidor de API construido utilizando la biblioteca JSON Server. El servidor está desplegado en Render.com, un proveedor de servicios en la nube.

## Nota Importante

La primera solicitud a la API puede tardar más tiempo de lo habitual debido a que el servidor puede estar pausado y necesita reiniciarse. Después de la primera solicitud, el servidor estará en funcionamiento y las respuestas serán más rápidas.

## Descripción

Este servidor de API proporciona un punto de acceso para gestionar tareas pendientes (To-Do). Puedes realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en las tareas a través de las solicitudes HTTP.

## Uso

Para utilizar este API endpoint, realiza solicitudes HTTP a la siguiente URL:

https://todo-server-y00c.onrender.com/todos

Esto devolverá una lista de tareas en formato JSON.

## Recursos Disponibles

Actualmente, este API endpoint proporciona acceso a los siguientes recursos:

- `/todos`: Devuelve una lista de todas las tareas pendientes.
- `/todos/{id}`: Devuelve una tarea específica según su ID.
  
  Ejemplo: `https://todo-server-y00c.onrender.com/todos/1`

## Operaciones admitidas

- **GET**: Obtener todas las tareas o una tarea específica.
- **POST**: Agregar una nueva tarea.
- **PUT**: Actualizar una tarea existente.
- **DELETE**: Eliminar una tarea.

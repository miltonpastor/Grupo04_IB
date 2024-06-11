
# Documento de Pruebas Funcionales para Notes-App--CRUD--NextJS

## 1. Introducción
Este documento describe las pruebas funcionales para el proyecto "Notes-App--CRUD--NextJS". Las pruebas funcionales se centran en verificar que el sistema cumple con los requisitos funcionales especificados.

## 2. Alcance
Las pruebas funcionales cubrirán las siguientes funcionalidades clave de la aplicación:
- Crear una nota
- Leer una nota
- Actualizar una nota
- Borrar una nota
- Listar todas las notas

## 3. Entorno de Pruebas
- **Navegador**: Microsoft Edge
- **Plataforma**: Windows 11

## 4. Casos de Prueba Funcionales

### Caso de Prueba 1: Crear una Nota
- **Descripción**: Verificar que un usuario puede crear una nueva nota.
- **Precondiciones**: El usuario está autenticado y en la página de creación de notas.
- **Entradas**: Título y contenido de la nota.
- **Pasos**:
  1. Navegar a la página de creación de notas.
  2. Introducir el título y el contenido de la nota.
  3. Hacer clic en el botón "Guardar".
- **Salidas Esperadas**: La nota se crea y se muestra en la lista de notas con un ID único.

### Caso de Prueba 2: Leer una Nota
- **Descripción**: Verificar que un usuario puede leer una nota existente.
- **Precondiciones**: Existe al menos una nota creada.
- **Entradas**: ID de la nota.
- **Pasos**:
  1. Navegar a la lista de notas.
  2. Seleccionar una nota de la lista.
- **Salidas Esperadas**: Se muestra el título y el contenido de la nota seleccionada.

### Caso de Prueba 3: Actualizar una Nota
- **Descripción**: Verificar que un usuario puede actualizar una nota existente.
- **Precondiciones**: Existe al menos una nota creada.
- **Entradas**: ID de la nota, nuevos datos de título y contenido.
- **Pasos**:
  1. Navegar a la lista de notas.
  2. Seleccionar una nota para editar.
  3. Modificar el título y/o contenido de la nota.
  4. Hacer clic en el botón "Guardar".
- **Salidas Esperadas**: La nota se actualiza con los nuevos datos.

### Caso de Prueba 4: Borrar una Nota
- **Descripción**: Verificar que un usuario puede borrar una nota existente.
- **Precondiciones**: Existe al menos una nota creada.
- **Entradas**: ID de la nota.
- **Pasos**:
  1. Navegar a la lista de notas.
  2. Seleccionar una nota para borrar.
  3. Hacer clic en el botón "Eliminar".
- **Salidas Esperadas**: La nota se elimina de la lista.

### Caso de Prueba 5: Listar Todas las Notas
- **Descripción**: Verificar que un usuario puede ver una lista de todas las notas.
- **Precondiciones**: El usuario está autenticado.
- **Entradas**: Ninguna.
- **Pasos**:
  1. Navegar a la página de lista de notas.
- **Salidas Esperadas**: Se muestra una lista con todas las notas existentes.

## 5. Procedimiento de Pruebas
1. Configurar el entorno de pruebas según las especificaciones.
2. Ejecutar cada caso de prueba siguiendo los pasos descritos.
3. Documentar los resultados de cada caso de prueba.
4. Reportar cualquier defecto encontrado durante la ejecución de las pruebas.

## 6. Criterios de Aceptación
- Todos los casos de prueba deben pasar sin errores.
- Las funcionalidades deben comportarse según lo especificado en los requisitos.
- Cualquier defecto encontrado debe ser corregido y probado nuevamente.


# Documento de Pruebas Unitarias para Notes-App--CRUD--NextJS

## 1. Introducción
Este documento describe las pruebas unitarias para el proyecto "Notes-App--CRUD--NextJS".

## 2. Alcance
Las pruebas unitarias cubrirán las funciones y componentes clave de la aplicación.

## 3. Entorno de Pruebas
- **Framework de Pruebas**: Jest.
- **Configuración**: definida en `jest.config.js`.

## 4. Casos de Prueba
1. **Función de Crear Nota**
   - **Descripción**: Verificar que una nueva nota se puede crear correctamente.
   - **Entradas**: título y contenido de la nota.
   - **Salidas Esperadas**: nota creada con ID único.

10/05/2024

![image](https://github.com/Milton599/Grupo04/assets/120606471/7c2cef5b-6aba-4fbc-9e13-5baf93a2e829)


2. **Función de Leer Lista de Notas**
   - **Descripción**: Verificar que se puede leer una nota existente en la lista de tarjetas.
   - **Entradas**: Ninguna.
   - **Salidas Esperadas**: Datos de las notas cargadas.

10/05/2024

![image](https://github.com/Milton599/Grupo04/assets/120606471/77850151-43dc-4151-a196-12929967c75e)


3. **Función de Actualizar Nota**
   - **Descripción**: Verificar que una nota existente se puede actualizar correctamente y se pueda guardar los cambios.
   - **Entradas**: Botón "Edit", cambio en título o contenido de la nota.
   - **Salidas Esperadas**: Mensaje de actualización y Datos de la nota actualizados.

10/05/2024

![image](https://github.com/Milton599/Grupo04/assets/120606471/ed054b75-67c8-4432-9830-f7209dc336e3)


4. **Función de Borrar Nota**
   - **Descripción**: Verificar que una nota existente se puede borrar correctamente.
   - **Entradas**: Botón "Delete".
   - **Salidas Esperadas**: confirmación de borrado.

10/05/2024

![image](https://github.com/Milton599/Grupo04/assets/120606471/ac32fec6-e718-428a-81f5-0e7cbdea0174)


## 5. Herramientas Utilizadas
- **Jest**: para la ejecución de pruebas.
- **Enzyme**: para pruebas de componentes React.

## 6. Ejecución de Pruebas
- Verificar que todas las pruebas pasen antes de hacer deploy a producción.

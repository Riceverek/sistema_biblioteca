PLANES DE PRUEBA – SISTEMA DE BIBLIOTECA DIGITAL

1. Plan de prueba: Registro y autenticación (RF-01)

Código: PP-01
Nombre: Verificación del registro e inicio de sesión de usuarios.
Objetivo: Comprobar que el sistema permita registrar nuevos usuarios e iniciar sesión mediante correo electrónico y contraseña.

Precondiciones:

- El usuario debe tener acceso al sistema.
- El usuario debe contar con un correo electrónico válido.
- El sistema debe estar funcionando correctamente.

Procedimiento de prueba:

1. Ingresar a la página de registro.
2. Completar los campos solicitados con nombre, correo electrónico y contraseña.
3. Presionar el botón de registrar.
4. Verificar que el usuario quede registrado.
5. Ingresar al inicio de sesión.
6. Escribir el correo y la contraseña registrados.
7. Presionar el botón de iniciar sesión.

Resultado esperado:

- El sistema debe registrar correctamente al nuevo usuario.
- Debe permitir el acceso cuando las credenciales sean correctas.
- Debe mostrar un mensaje de error cuando el correo o la contraseña sean incorrectos.
- No debe permitir el registro de un correo que ya se encuentre registrado.

---

2. Plan de prueba: Búsqueda de material (RF-02)

Código: PP-02
Nombre: Verificación del buscador de libros y documentos.
Objetivo: Comprobar que los usuarios puedan encontrar materiales digitales utilizando diferentes filtros de búsqueda.

Precondiciones:

- El sistema debe tener libros y documentos registrados en el catálogo.
- El usuario debe ingresar a la biblioteca digital.

Procedimiento de prueba:

1. Ingresar al buscador de la biblioteca.
2. Buscar un libro utilizando su título.
3. Realizar una búsqueda utilizando el nombre del autor.
4. Buscar un material por género.
5. Realizar una búsqueda mediante palabras clave.
6. Verificar los resultados obtenidos en cada búsqueda.

Resultado esperado:

- El sistema debe mostrar los libros relacionados con los criterios de búsqueda.
- Los filtros deben funcionar correctamente.
- Los resultados deben corresponder a la información ingresada.
- Si no existen coincidencias, el sistema debe mostrar un mensaje indicando que no se encontraron resultados.

---

3. Plan de prueba: Lectura y préstamo digital (RF-03)

Código: PP-03
Nombre: Verificación de lectura y solicitud de préstamos digitales.
Objetivo: Comprobar que los usuarios registrados puedan solicitar préstamos de libros digitales y acceder a su lectura en línea.

Precondiciones:

- El usuario debe estar registrado e iniciar sesión.
- Deben existir libros digitales disponibles en el catálogo.
- Los archivos deben estar cargados correctamente.

Procedimiento de prueba:

1. Iniciar sesión en la biblioteca digital.
2. Buscar un libro disponible.
3. Seleccionar el libro deseado.
4. Presionar la opción de solicitar préstamo.
5. Verificar la confirmación de la solicitud.
6. Seleccionar un libro que permita lectura en línea.
7. Abrir el documento y comprobar que se pueda visualizar su contenido.

Resultado esperado:

- El sistema debe permitir solicitar el préstamo de libros digitales.
- Debe mostrar una confirmación de la solicitud.
- El usuario debe poder abrir y leer los documentos en línea.
- Los libros deben visualizarse correctamente y sin errores de carga.

---

4. Plan de prueba: Gestión del catálogo (RF-04)

Código: PP-04
Nombre: Verificación de la administración del catálogo digital.
Objetivo: Comprobar que los administradores puedan agregar, modificar y eliminar libros o documentos de la biblioteca.

Precondiciones:

- El administrador debe contar con usuario y contraseña.
- Debe tener permisos para gestionar el catálogo.
- El sistema debe permitir cargar archivos PDF y ePub.

Procedimiento de prueba:

1. Iniciar sesión con una cuenta de administrador.
2. Ingresar al módulo de gestión del catálogo.
3. Seleccionar la opción agregar libro.
4. Ingresar título, autor, género y descripción.
5. Cargar un archivo en formato PDF o ePub.
6. Guardar la información y verificar que aparezca en el catálogo.
7. Seleccionar un libro existente y modificar sus datos.
8. Guardar los cambios y comprobar la actualización.
9. Seleccionar un libro y ejecutar la opción eliminar.

Resultado esperado:

- El administrador debe poder agregar nuevos libros.
- El sistema debe aceptar archivos PDF y ePub válidos.
- Debe permitir modificar la información de los libros.
- Debe eliminar los materiales seleccionados del catálogo.
- Los cambios deben reflejarse correctamente en la biblioteca.

---

5. Plan de prueba: Historial de usuario (RF-05)

Código: PP-05
Nombre: Verificación del historial de lectura y préstamos.
Objetivo: Comprobar que el sistema almacene y muestre correctamente el historial de libros leídos y los préstamos activos de cada usuario.

Precondiciones:

- El usuario debe estar registrado.
- Debe haber iniciado sesión.
- Debe haber realizado al menos una lectura o solicitado un préstamo.

Procedimiento de prueba:

1. Iniciar sesión con una cuenta de usuario.
2. Solicitar el préstamo de un libro digital.
3. Abrir un libro para leerlo en línea.
4. Ingresar a la sección de historial de usuario.
5. Verificar que aparezcan los libros leídos.
6. Comprobar que se muestren los préstamos activos.
7. Cerrar sesión e ingresar nuevamente.
8. Consultar el historial para verificar que la información permanezca guardada.

Resultado esperado:

- El sistema debe guardar los libros que el usuario ha leído.
- Debe mostrar los préstamos que se encuentran activos.
- El historial debe corresponder únicamente al usuario que inició sesión.
- La información debe mantenerse guardada aunque el usuario cierre sesión y vuelva a ingresar.

---

CONCLUSIÓN

Los cinco planes de prueba permiten verificar el funcionamiento de los principales módulos de la biblioteca digital. Mediante estas pruebas se busca garantizar que los usuarios puedan registrarse, iniciar sesión, buscar libros, solicitar préstamos, leer documentos en línea y consultar su historial.

También se verifica que los administradores puedan gestionar correctamente el catálogo. La ejecución de estos planes permitirá identificar errores, corregir posibles fallas y garantizar que el sistema cumpla con los requisitos funcionales establecidos.

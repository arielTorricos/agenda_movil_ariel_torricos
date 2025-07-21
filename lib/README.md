# mi_agenda_contatos

Esta aplicación Flutter permite gestionar una agenda de contactos de forma sencilla y moderna.

## Funcionamiento

- En la pantalla principal se muestra un formulario para agregar nuevos contactos con los campos: Nombre, Teléfono y Correo electrónico.
- Al completar el formulario y presionar "Agregar contacto", el usuario se añade a una lista que se muestra debajo del formulario.
- Cada contacto se visualiza en una tarjeta con su nombre, teléfono y correo electrónico.
- Para actualizar la interfaz y mostrar los nuevos contactos agregados, se utiliza la función `setState` dentro del método `_agregarUsuario`. Esto permite que la lista de contactos se actualice dinámicamente cada vez que se agrega un nuevo usuario.

## Validaciones implementadas

- **Nombre:** No puede estar vacío.
- **Teléfono:** Solo acepta números y debe tener exactamente 8 dígitos. Se valida con la expresión regular `^\d{8}$`.
- **Correo electrónico:** Debe tener un formato válido, por ejemplo usuario@dominio.com. Se valida con la expresión regular `^[\w-\.]+@[\w-]+\.[a-zA-Z]{2,}$`.

Si algún campo no cumple con la validación, se muestra un mensaje de error debajo del campo correspondiente.

## Diseño

- El formulario y la lista de contactos tienen un diseño amigable y moderno usando tarjetas, iconos y colores para facilitar la experiencia de usuario.

## Que Aprendi

- aprendi a crear formularios validados y poder agregar a una lista en un card para una mejor visualizacion de los compomentes

## Requisitos

- Flutter SDK instalado.
- Ejecuta la aplicación con `flutter run`.

---

¡Puedes personalizar la aplicación agregando más campos o funcionalidades según tus necesidades!

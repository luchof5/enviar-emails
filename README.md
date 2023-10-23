<!-- Documentación del Código -->

# 📚 Documentación del Código

Esta documentación describe la funcionalidad y el uso del código JavaScript proporcionado, que se encarga de manejar un formulario de envío de correos electrónicos. El código incluye validación y notificaciones para el usuario.

## 🧾 Descripción

Este código está diseñado para gestionar un formulario de correo electrónico. Permite a los usuarios ingresar su dirección de correo electrónico, un asunto y un mensaje. Realiza validaciones en tiempo real, muestra alertas y notifica al usuario cuando el mensaje se envía correctamente.

## 📑 Estructura del Código

- El código utiliza `DOMContentLoaded` para garantizar que se ejecute una vez que la página web esté completamente cargada.
- Se define un objeto `email` para almacenar los valores de correo electrónico, asunto y mensaje.
- Selecciona los elementos de la interfaz, como los campos de entrada, botones y el spinner.
- Asigna eventos para validar la entrada del usuario, enviar el correo electrónico y restablecer el formulario.

## 🚀 Uso

1. Ingresa tu dirección de correo electrónico, asunto y mensaje en el formulario.
2. A medida que escribes en los campos, el código valida los datos en tiempo real.
3. Si algún campo está vacío, se mostrará una alerta.
4. Si el correo electrónico no es válido, se mostrará una alerta.
5. Una vez que todos los campos están completos y válidos, el botón "Enviar" se habilitará.
6. Haz clic en "Enviar" para simular el envío del correo electrónico.
7. Se mostrará un spinner durante tres segundos.
8. Después de ese tiempo, el formulario se restablecerá y aparecerá una alerta de éxito.

## 📦 Tecnologías Utilizadas

- HTML: La estructura del formulario.
- JavaScript: La funcionalidad y la lógica del formulario.
- CSS (Clases Tailwind CSS): Estilos y diseño.
- Temporizador (setTimeout): Para simular el envío y mostrar la alerta de éxito.

## 📣 Contribuir

Si deseas contribuir a este código o mejorar su funcionalidad, puedes seguir estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama con el nombre de tu característica o corrección: `git checkout -b mi-caracteristica`.
3. Realiza tus cambios y asegúrate de seguir las mejores prácticas de codificación.
4. Realiza un commit de tus cambios: `git commit -m 'Agrega mi característica'`.
5. Sube tus cambios a tu repositorio: `git push origin mi-caracteristica`.
6. Crea un Pull Request en este repositorio.

## 📄 Licencia

Este código está disponible bajo la Licencia MIT. Consulta el archivo `LICENSE` para obtener más detalles.

## ✉️ Contacto

Si tienes preguntas o sugerencias, puedes contactarme a través de [lucho_l.@hotmail.com].

¡Gracias por utilizar este código! 🚀

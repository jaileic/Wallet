💳 Wallet Digital - Proyecto Web

Proyecto de una billetera digital básica desarrollado con HTML, CSS, Bootstrap, JavaScript y jQuery, que permite simular operaciones comunes de una wallet como inicio de sesión, depósitos, envíos de dinero y visualización de movimientos.

📌 Características principales

🔐 Inicio de sesión con validación

💰 Visualización de saldo en tiempo real

➕ Depósito de dinero

💸 Envío de dinero a contactos

👥 Gestión de contactos (agenda)

📄 Visualización de últimos movimientos

💾 Persistencia de datos usando Local Storage

🎨 Interfaz responsive con Bootstrap

🛠️ Tecnologías utilizadas

HTML5, CSS3, Bootstrap 4, JavaScript, jQuery 3.6 y Local Storage.

📁 Estructura del proyecto

/
index.html → Pantalla de inicio de sesión
menu.html → Menú principal
deposit.html → Pantalla de depósito
sendmoney.html → Envío de dinero y contactos
transactions.html → Últimos movimientos

🔐 Inicio de sesión

Credenciales de prueba:
Email: admin@wallet.com

Contraseña: 123456

Al iniciar sesión correctamente, el usuario es redirigido automáticamente al menú principal.

🧩 Funcionalidades por pantalla
Login (index.html)

Uso de selectores jQuery para capturar los datos del formulario, manejo del evento submit con jQuery, validación de credenciales, uso de alertas Bootstrap para mostrar mensajes de éxito o error y redirección automática al menú principal.

Menú Principal (menu.html)

Muestra el saldo actual obtenido desde Local Storage, contiene botones para Depositar, Enviar Dinero y Últimos Movimientos, y utiliza JavaScript para manejar los eventos y redirecciones entre pantallas.

Depósito (deposit.html)

Visualización del saldo actual antes de realizar el depósito, validación del monto ingresado, actualización del saldo en Local Storage, mensaje de éxito utilizando alertas Bootstrap y redirección automática al menú principal luego de un retraso de 2 segundos.

Enviar Dinero (sendmoney.html)

Permite gestionar una agenda de contactos, agregar nuevos contactos mediante un formulario con validación, buscar contactos por nombre o alias, seleccionar un contacto para habilitar el botón de envío y mostrar un mensaje de confirmación al finalizar la transferencia.

Últimos Movimientos (transactions.html)

Visualización dinámica de una lista ficticia de transacciones, preparada para ser reemplazada por datos reales, mostrando el tipo de movimiento y el monto correspondiente.

💾 Persistencia de datos

El proyecto utiliza Local Storage para almacenar el saldo de la billetera, los contactos agregados y la información necesaria para mantener los datos aun cuando se recarga la página.

📱 Diseño Responsive

La interfaz está desarrollada con Bootstrap, lo que permite que la aplicación se adapte correctamente a distintos tamaños de pantalla como escritorio, tablets y dispositivos móviles.

🚀 Cómo ejecutar el proyecto

Clonar el repositorio con git clone https://github.com/tu-usuario/wallet-digital.git
 o descargar los archivos y abrir el archivo index.html directamente en el navegador. No requiere servidor ni instalación adicional.

📌 Notas finales

Este proyecto fue desarrollado con fines educativos, aplicando buenas prácticas de desarrollo web, manipulación del DOM, uso de jQuery, interactividad con JavaScript y diseño de interfaces con Bootstrap.

✨ Autor

Javiera L.
Proyecto académico – Desarrollo Web

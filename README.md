# EventHub
## 📂 Estructura del Proyecto (Primera Revisión - Frontend)

Para esta primera iteración, hemos desarrollado la interfaz gráfica (HTML/CSS) simulando el comportamiento de la aplicación web. La navegación entre pantallas está implementada mediante enlaces estáticos para demostrar el flujo completo.

eventhub/
├── index.html              
├── registro.html           
├── eventos.html            
├── crear-evento.html       
├── evento-detalle.html     
├── actividad-detalle.html  
├── css/
│   └── style.css           
└── img/

📄 Descripción de las Vistas y Funcionalidades

Hemos dividido las vistas según el nivel de acceso (público vs. autenticado) y los roles (usuario vs. organizador), cubriendo todas las funcionalidades requeridas (F1-F13):

    index.html: Pantalla de inicio de la aplicación. Contiene el formulario de Autenticación (F2). Es la puerta de entrada y pertenece a la zona pública.

    registro.html: Formulario de Registro (F1) para nuevos usuarios. Permite introducir alias, contraseña y email.

    eventos.html: Panel principal post-login. Muestra el Listado de eventos (F3) creados en la plataforma. Desde aquí se puede acceder a la creación de nuevos eventos.

    crear-evento.html: Formulario para Crear evento (F4). Al completarlo, el usuario se convierte lógicamente en el organizador de dicho evento.

    evento-detalle.html: Panel de control de un evento concreto (F5).

        Vista de Usuario: Muestra la información general y lista sus actividades.

        Vista de Organizador: Incluye los controles para Editar evento (F7), Eliminar evento (F8) y el formulario para Crear actividad (F9).

    actividad-detalle.html: Vista detallada de una actividad (F6).

        Vista de Usuario: Muestra el aforo, lista de inscritos y los botones para Inscribirse (F12) o Cancelar inscripción (F13).

        Vista de Organizador: Incluye los controles de gestión para Editar actividad (F10) y Eliminar actividad (F11).

🎨 Estilos y Recursos

    css/style.css: Hoja de estilos principal. Contiene variables de color, tipografía y la maquetación común (navbar, footers, tarjetas de eventos) para mantener consistencia en todas las vistas.

    img/: Directorio para recursos gráficos estáticos como el logotipo de EventHub.
1. Título: RayoCinema, Descripción: Es un sitio de peliculas y series que contiene los títulos de todas tus plataformas favoritas, Objetivo: Migración o implementacion de angular 18 usando TypeScript y concluyendo las funcionalidades pendientes.

2. Pedro Mauricio Godinez Ortiz

3. Screenshots: 
<img width="1438" alt="Captura de pantalla 2025-04-22 a la(s) 3 15 13 a m" src="https://github.com/user-attachments/assets/96f8685f-f8f5-4b53-b90a-f9c691fe1d84" />
<img width="1438" alt="Captura de pantalla 2025-04-22 a la(s) 3 15 25 a m" src="https://github.com/user-attachments/assets/d8381233-e94e-4585-8fa2-98646fad4507" />
<img width="1438" alt="Captura de pantalla 2025-04-22 a la(s) 3 15 37 a m" src="https://github.com/user-attachments/assets/1b0a71be-a085-4692-af07-8da8434c72c0" />
<img width="1438" alt="Captura de pantalla 2025-04-22 a la(s) 3 15 47 a m" src="https://github.com/user-attachments/assets/63e8288d-3f75-437d-9436-6c57602b9f3a" />
<img width="1438" alt="Captura de pantalla 2025-04-22 a la(s) 3 15 56 a m" src="https://github.com/user-attachments/assets/d6034198-7b88-4c0d-a5af-e529b7dfc948" />


4. Como utilizar el sitio: una vez descargado el repositorio deberas ingresar a la carpeta del proyecto mediante la terminal, después deberás iniciar el servidor de desarrollo local con el comendo ng serve para que te permita ver el proyecto, una vez ejecutado el comando se deberá lanzar una pestaña web con la vista inicial del proyecto o si no lo hace simplemente copias y pegar el url que te arroja la terminal (ejemplo: http://localhost:4200/), una vez que ya te cargó el proyecto te mostrará el archivo principal.html ahí te mostrará un vistazo previo al sitio, para ingresar deberás dar click en iniciar sesión para dirigirte al login, en el login introducirás tus datos (inventados por ahora) al dar click en iniciar sesión te redigirá a la pantalla principal dónde estan todos los títulos disponibles, si das click en ver te despliegará a una página donde te mostrará una algunos detalles del título, en la pestaña de favoritos se muestran los títulos que marcaste como favoritos, en la pestaña de series se muestran solo las series disponibles así como en la pestaña de películas y en cada pestaña encontrarás un botón para cerrar sesión que te redirigirá al login..

5. Dependencias o bibliotecas utilizadas:
@angular/common, @angular/compiler, @angular/core, @angular/forms,@angular/platform-browser,@angular/platform-browser-dynamic, @angular/platform-server, @angular/router, @angular/ssr.

@fortawesome/fontawesome-free – íconos, bootstrap – estilos y componentes visuales, rxjs – programación reactiva, swiper – carruseles/galerías deslizables, tslib – helpers de TypeScript, zone.js – necesario para el cambio de detección de Angular

6. Como lo hice: Primero cree el proyecto con la terminal, posteriormente con el proyecto creado y ya dentro de la ruta del mismo procedí a crear los respectivos componentes para cada una de las pestañas, ya con la estructura mejor definida del proyecto comencé a migrar pestaña por pestaña a cada uno de los componentes con su respectivos códigos, además de configurar sus rutas, estilos y funcionalidades con TypeScript, y así como la resolución de problemas sencillos que iban surgiendo.

7. Problemas conocidos: El apartado de favoritos no pude lograr que fuera dinámico, recordar hasta el último momento que lo mejor en angular es crear componentes reutilizables para evitar repetir código en los html, así como los servicios para tener ya un catálogo bien definido de los recursos a utilizar (en este caso las películas y series).

8. Retrospectiva:
    Que hice bien? Empezar por buscar documentación y definir la mejor manera para empezar a migrar el sitio parte por parte, guiarme con los videos del curso y del challenger para tener una referencia, no rendirme. 
   Que hice mal? No revisar que todo lo que hacia fuera la mejor manera de hacerlo, no mantener mi enfoque durante el desarrollo del sprint y no terminar de completar la funcionalidad de la página de favoritos.
   Que puedo hacer diferente? Seguir aprendiendo en cada sprint como organizar las tareas a desarrollar, medir mis tiempos para evitar la acumulación de tareas.

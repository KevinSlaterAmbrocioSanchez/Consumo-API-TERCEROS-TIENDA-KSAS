# Proyecto Angular: *Gestión de Negocios*

## Descripción del Proyecto
Este proyecto es una aplicación web diseñada para facilitar la administración y gestión de un negocio mediante herramientas digitales. Implementa diversas funcionalidades como manejo de perfiles de usuario, inicio de sesión, y la visualización de información en tablas y paneles. Está desarrollado con Angular, lo que permite modularidad, escalabilidad y una experiencia de usuario eficiente.

## Propósito
El propósito del proyecto es ofrecer una herramienta intuitiva y personalizable para gestionar actividades clave en un negocio, como:
- Inicio de sesión seguro.
- Visualización de datos del usuario en su perfil.
- Uso de datos de una Api y motrarlas en tablas dinámicas para organizar y manejar la información.

---

## Estructura del Código

### 1. *Main Application*
El archivo principal de la aplicación es main.ts, que inicializa la aplicación Angular. Este archivo trabaja en conjunto con index.html, la plantilla HTML base de la app.

### 2. *Módulos y Componentes Clave*

#### Módulo de Negocios (bussiness)
Contiene componentes específicos para funcionalidades relacionadas con el negocio:

- *login*: Implementa el formulario de autenticación para que los usuarios accedan al sistema.
- *dashboard*: Es la pantalla principal que muestra información general del negocio.
- *perfil*: Permite a los usuarios visualizar su información personal, como nombre, correo, y más.
- *tablas*: Maneja la visualización y manejo de datos en formato tabular, facilitando su consulta y análisis.

#### Módulo Compartido (shared)
Incluye componentes reutilizables para crear una interfaz consistente:
- *menu*: Un menú horizontal ubicado en la parte superior para facilitar la navegación.
- *sidebar*: Una barra lateral que incluye opciones de navegación para acceder a las diferentes secciones de la aplicación.

### 3. *Enrutamiento*
El archivo app.routes.ts define las rutas principales de la aplicación, conectando cada ruta con su componente respectivo. Ejemplo:
typescript
{ path: 'login', component: LoginComponent },
{ path: 'dashboard', component: DashboardComponent },
`
-------------------------------------------------------------------------

###4. Estilos
El archivo principal de estilos styles.css, y el tema personalizado en custom-theme.scsscontrolan el diseño visual de la aplicación.

##Funcionalidades del Proyecto
####Acceso
- Página inicial que permite autenticar a los usuarios.
- Verificación de credenciales.

####Panel de control (Dashboard)
- Permite acceso rápido a las principales funcionalidades.
  <img width="1470" alt="Captura de pantalla 2024-11-25 a la(s) 1 18 37 a m" src="https://github.com/user-attachments/assets/64498dc4-fabf-47c8-9e8d-ec4f6eb785ab">


####Gestión de perfiles
- Visualización personalizada de datos.

####Tablas dinámicas
- Visualización y manejo de grandes volúmenes de datos de la API implementada.
![image](https://github.com/user-attachments/assets/91104dee-949e-4d38-9d0b-b8c3ef9bd90c)



####Navegación intuitiva
- Menú : Acceso rápido a funciones principales.
- Barra lateral : Navegación estructurada por secciones.

####Requisitos
- *Node.js* : Para gestionar dependencias y ejecutar el servidor.
- *Angular CLI* : herramienta para compilar y ejecutar el proyecto.

####Instalación y ejecución
1. Clonar el repositorio:



git clone <url-del-repositorio>

 2.Instalar dependencias:

npm install


3.Ejecutar la aplicación:

ng serve


4.Acceda a la aplicación desde su navegador en http://localhost:4200.



------------

Realizado por: *Ambrocio Sánchez Kevin Slater*


###End

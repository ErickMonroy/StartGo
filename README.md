<div align="center">
<h1 align="center">START & GO</h1>   
<h3>Sistema de gestión para escuelas de manejo </h3>

<img src="https://img.shields.io/badge/Lenguaje-PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="Lenguaje PHP">
<img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
<img src="https://img.shields.io/badge/Versión-1.0.0-yellow?style=for-the-badge" alt="Versión">

<p align="right"><br>Fecha: 12 de julio de 2025</p>
</div>

### Descripción
<div align=justify>

**START & GO** es un sistema web desarrollado para **centralizar, automatizar y optimizar** la gestión administrativa de una escuela de manejo.  
El sistema reduce procesos manuales, mejora el control de horarios y permite una mejor toma de decisiones mediante reportes visuales y estados de cuenta automatizados.

Está diseñado con un enfoque práctico, escalable y orientado a resolver necesidades reales del entorno administrativo.
</div>

--- 

### Funcionalidades principales
- Inicio de sesión y control de acceso por rol.
- Gestión de empleados (CRUD)
- Gestión de clientes (CRUD).
- Agenda: programación y consulta de horarios para las clases (CRUD).
- Registro de paquete contratado por los clientes. 
- Generación de estados de cuenta en PDF.
- Generación de gráficas de reportes de clases y exámenes.
- Modo claro/oscuro adaptable a preferencias del usuario.
- Sistema de ayuda.
---

## Tecnologías Utilizadas  

- **Backend:** PHP  
- **Base de datos:** MySQL  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Servidor:** IIS (Internet Information Services)  
- **Herramientas:** MySQL Workbench 8.0  

## Requisitos del Sistema

**Software necesario:**
- PHP (recomendación v.8.4.4)
- MySQL Workbench 8.0
- Navegador moderno (Chrome, Firefox, Edge)
- Servidor local (recomendado el servidor IIS de Windows)


## Configuraciones necesarias:
- Configuración en `php.ini`:

> Estas extensiones son necesarias para la conexión del sistema con la base de datos desarrollada en MySQL.
```ini
extension=pdo_mysql
extension=mysqli
```

> Estas extensiones son necesarias para la generación de PDFs y el manejo correcto de caracteres especiales.

```ini
extension=php_gd2.dll
extension=php_mbstring.dll
```

## Instalación básica
1. Clonar el repositorio
2. Configurar el proyecto en IIS
3. Importar la base de datos
4. Ajustar credenciales de conexión
5. Acceder desde `http://localhost/StartGo`

---

<h2 align="center"> Desarrolladores</h2><br>
<table align="center">
  <tr>
    <td align="center">
      <a href="https://github.com/ErickMonroy">
        <img src="https://avatars.githubusercontent.com/ErickMonroy" width="100px;" alt="Erick Monroy"/><br />
        <sub><b>Erick Monroy</b></sub>
      </a>
      <p>Backend</p>
    </td>
    <td align="center">
      <a href="https://github.com/MichelIvette">
        <img src="https://avatars.githubusercontent.com/MichelIvette" width="100px;" alt="Michel Ivette"/><br />
        <sub><b>Michel Ivette</b></sub>
      </a>
      <p>Frontend</p>
    </td>
    <td align="center">
      <a href="https://github.com/ZeroZX935">
        <img src="https://avatars.githubusercontent.com/ZeroZX935" width="100px;" alt="Cesar"/><br />
        <sub><b>Cesar</b></sub>
      </a>
      <p>Backend</p>
    </td>
  </tr>
  <tr>
     <td> <p></p>
     </td>
     <td>
     </td>
     <td>
     </td>
  </tr>
</table>
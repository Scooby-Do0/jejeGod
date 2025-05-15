# ODSALos4Vientos

Este proyecto es una **plataforma de gestión de iniciativas del centro educativo Cuatrovientos**, con el objetivo de fomentar el cumplimiento de los **Objetivos de Desarrollo Sostenible (ODS)**. La solución cuenta con una API central, una aplicación web y una aplicación móvil.

Desarrollado por Aitor del Cerro, Eduardo Fontsere, Ganix Gorosabel, Inazio Astigarraga y Julen Medina.

---

## ¿Cómo empezar?

Clona este repositorio o descárgalo como ZIP para empezar a trabajar con el proyecto:

```
git clone https://github.com/JulenMO/ODSALos4Vientos.git
```

> [!TIP]
> También puedes usar el botón `Code > Download ZIP` directamente desde la [página del repositorio](https://github.com/JulenMO/ODSALos4Vientos).

---

## Requisitos para ejecutar la API

- [Visual Studio 2022 (actualizado)](https://visualstudio.microsoft.com/es/downloads/)
- Apache + MySQL (recomendado: [XAMPP](https://www.apachefriends.org/download.html?pubDate=20250331))

---

## Configuración de la Base de Datos

1. Abre tu entorno de base de datos (por ejemplo, MySQL desde XAMPP).
2. Crea una base de datos vacía con el nombre:

```
proyecto4vods
```

3. Ejecuta el script de creación de la base de datos desde este archivo: GenerarBD/MYSQL/[proyecto4vods.sql](https://github.com/JulenMO/ODSALos4Vientos/blob/main/GenerarBD/MySQL/proyecto4vods.sql)

4. Para añadir datos de prueba, ejecuta el siguiente script adicional: GenerarBD/MYSQL/[Datos4vOds.sql](https://github.com/JulenMO/ODSALos4Vientos/blob/main/GenerarBD/MySQL/Datos4vOds.sql)

---

## Cómo ejecutar el backend

1. Asegúrate de que Apache y MySQL están encendidos (por ejemplo, con XAMPP).
2. Abre Visual Studio 2022.
3. Abre la solución ubicada en: Backend/ods_4Vientos.Sln/[ods_4Vientos.sln](https://github.com/JulenMO/ODSALos4Vientos/tree/main/Backend/ods_4Vientos.Sln)
4. Ejecuta el proyecto en modo `https`.

---

## Tecnologías utilizadas (Backend)

- .NET 9.0  
- C#  
- Entity Framework Core  
- ASP.NET

---

## Interfaces del proyecto

Este proyecto cuenta con dos interfaces principales:

### 🌐 Versión Web

Aplicación desarrollada en Angular 19.
> [!NOTE]
> Puedes consultar cómo instalar y ejecutar la versión web en su README específico: [Instrucciones WebAngular](https://github.com/JulenMO/ODSALos4Vientos/tree/main/frontend/WebAngular#readme)

---

### 📱 Aplicación Móvil

Aplicación desarrollada en React Native con Expo.
> [!NOTE]
> Puedes consultar cómo instalarla, ejecutarla en emulador o dispositivo físico, y generar un APK en su README: [Instrucciones App4VODS](https://github.com/JulenMO/ODSALos4Vientos/tree/main/frontend/AppMovil/App4VODS#readme)

---

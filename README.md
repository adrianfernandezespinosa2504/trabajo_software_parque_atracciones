# 🎢 Aplicación para la gestión de un parque de atracciones

### Ingeniería del Software

![Java](https://img.shields.io/badge/Language-Java-orange?style=flat&logo=java)
![Jakarta](https://img.shields.io/badge/Technology-Jakarta%20Servlets-red?style=flat)
![JPA](https://img.shields.io/badge/Persistence-JPA-blue?style=flat)
![EclipseLink](https://img.shields.io/badge/ORM-EclipseLink-lightgrey?style=flat)
![Architecture](https://img.shields.io/badge/Architecture-MVC-purple?style=flat)
![Web](https://img.shields.io/badge/Platform-Web-green?style=flat)

## 📌 Descripción

Proyecto de Ingeniería del Software centrado en el análisis, diseño y especificación de una aplicación web para la gestión de un parque de atracciones.

La solución, denominada **enjoyUS**, plantea una plataforma SaaS destinada a centralizar la información del parque y digitalizar diferentes procesos operativos, mejorando la organización de las instalaciones y la experiencia de los visitantes.

El proyecto aborda el ciclo de análisis y diseño del sistema, desde la identificación de las necesidades del negocio hasta la definición de requisitos funcionales y no funcionales, casos de uso, restricciones técnicas y requisitos de integración.

## 🎯 Objetivos

- **Centralización de la información:** unificar los datos del parque mediante un sistema de persistencia centralizado.
- **Digitalización de procesos:** sustituir procedimientos manuales por funcionalidades accesibles desde una aplicación web.
- **Gestión independiente de áreas:** organizar las distintas áreas operativas en módulos desacoplados.
- **Diseño modular:** definir una arquitectura que facilite el mantenimiento y la reutilización de componentes.
- **Experiencia del usuario:** proporcionar información actualizada sobre las instalaciones, atracciones y espectáculos.

## ⚙️ Funcionalidades principales

La especificación contempla diferentes áreas funcionales para la gestión del parque:

| Área | Funcionalidades |
|---|---|
| **Accesos** | Validación de entradas mediante códigos QR y registro de entradas y salidas. |
| **Operaciones** | Consulta de tiempos de espera, disponibilidad y afluencia de atracciones. |
| **Entretenimiento** | Consulta de horarios, ubicación y aforo de espectáculos. |
| **Gestión de clientes** | Registro y autenticación de usuarios. |
| **Ventas** | Compra online y gestión de entradas. |

La primera versión del sistema se centra especialmente en las áreas de **Accesos, Operaciones y Entretenimiento**.

## 🏗️ Arquitectura del sistema

Se plantea una arquitectura basada en el patrón **Modelo-Vista-Controlador (MVC)**, utilizando componentes independientes para separar la presentación, la lógica de negocio y el acceso a los datos.

- **Modelo:** representación de las entidades del dominio y gestión de la persistencia mediante JPA.
- **Vista:** interfaz web con la que interactúan clientes y empleados.
- **Controlador:** Servlets encargados de recibir las peticiones y coordinar la lógica del sistema.

Esta organización permite desacoplar las distintas áreas funcionales y facilitar futuras ampliaciones.

## 🛠️ Tecnologías y herramientas

Las tecnologías definidas para la solución incluyen:

- **Java y Jakarta Servlets:** desarrollo de la lógica del servidor y gestión de peticiones HTTP.
- **JPA (EclipseLink):** persistencia y gestión de entidades mediante `EntityManager` y `EntityManagerFactory`.
- **Arquitectura MVC:** separación de responsabilidades y organización modular.
- **AJAX:** comunicación asíncrona entre el navegador y el servidor.
- **Google Maps API:** representación gráfica del mapa del parque.
- **HTML5 Geolocation API:** obtención de la ubicación del cliente.
- **Stripe:** integración prevista para el procesamiento de pagos.

## 📋 Ingeniería del Software

El trabajo incluye la elaboración de una Especificación de Requisitos del Sistema (ERS), que recoge:

- Identificación de actores y necesidades de negocio.
- Análisis de la situación de partida.
- Definición de requisitos generales.
- Especificación de casos de uso.
- Requisitos funcionales de información, reglas de negocio y conducta.
- Requisitos no funcionales de fiabilidad, usabilidad, eficiencia, mantenibilidad, portabilidad y seguridad.
- Restricciones técnicas y requisitos de integración.
- Diagramas de casos de uso y despliegue.

## 📚 Documentación

El proyecto dispone de documentación técnica orientada a describir el dominio del problema, justificar las decisiones de diseño y especificar el comportamiento esperado del sistema.

---

*Proyecto académico desarrollado en el marco de la asignatura de Ingeniería del Software de la Universidad de Sevilla.*

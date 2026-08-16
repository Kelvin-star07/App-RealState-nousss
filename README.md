# Real Estate App – Plataforma Inmobiliaria

Aplicación web full-stack para la gestión y comercialización de propiedades inmobiliarias (venta y alquiler).  
Desarrollada con **ASP.NET Core** (MVC + Web API), **Entity Framework Core**, **SQL Server** y **SignalR**.

---

## Descripción

Plataforma que permite a administradores, agentes inmobiliarios y clientes interactuar de forma completa:

- Los **agentes** publican y administran propiedades (venta o alquiler).
- Los **clientes** exploran propiedades, las marcan como favoritas, realizan ofertas y se comunican en tiempo real con los agentes mediante chat.
- Los **administradores** gestionan usuarios, roles y el sistema en general.

El sistema maneja roles diferenciados, autenticación, chat en tiempo real y flujos de ofertas sobre propiedades disponibles.

---

## Características principales

- Registro, login y recuperación de contraseña
- Roles: Administrador, Agente y Cliente
- Publicación y administración de propiedades (venta / alquiler)
- Sistema de favoritos (me gusta) – implementado por mí
- Chat en tiempo real con SignalR entre clientes y agentes – parte cliente implementada por mí
- Sistema de ofertas con precio sobre propiedades disponibles – implementado por mí
- Gestión de propiedades favoritas por parte del cliente
- Comunicación y proceso de compra/alquiler a través del chat
- Autenticación y autorización basada en roles con ASP.NET Identity

---

## Tecnologías

| Tecnología              | Uso                              |
|-------------------------|----------------------------------|
| ASP.NET Core MVC        | Aplicación web principal         |
| ASP.NET Core Web API    | Servicios REST                   |
| Entity Framework Core   | ORM y acceso a datos             |
| SQL Server              | Base de datos                    |
| ASP.NET Identity        | Autenticación y roles            |
| SignalR                 | Chat en tiempo real              |
| Bootstrap / HTML / CSS  | Interfaz de usuario              |
| Git / GitHub            | Control de versiones             |

---

## Arquitectura

El proyecto sigue una arquitectura por capas (Clean / Onion inspirada):

- **Domain** → Entidades y reglas de negocio
- **Application** → Servicios, DTOs y lógica de aplicación
- **Infrastructure** → Persistencia (EF Core), Identity y repositorios
- **Presentation** → MVC + Web API

---

## Roles del sistema

| Rol           | Descripción                                      |
|---------------|--------------------------------------------------|
| Administrador | Gestión completa de usuarios, roles y sistema    |
| Agente        | Publicación y administración de propiedades      |
| Cliente       | Exploración, favoritos, ofertas y chat con agentes |

---

## Funcionalidades destacadas (mi contribución)

- Implementación del sistema de **favoritos** (dar me gusta a propiedades y sección de administración de favoritos)
- Implementación del **chat en tiempo real** (lado cliente) con SignalR
- Desarrollo del flujo de **ofertas** (hacer oferta con precio sobre propiedades de venta disponibles)
- Integración de estas funcionalidades con el flujo de compra/alquiler a través del chat

---

## Estructura del repositorio

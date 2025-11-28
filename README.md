# ⚙️ SyncUp-Backend | Logica de negocio y Algoritmos Avanzados

Finalizado (Proyecto Académico - 2025) con opción de escalabilidad
Materia: Estructura de Datos

**Núcleo de la plataforma SyncUp** desarrollado para gestionar la lógica de negocio, la persistencia de datos y la inteligencia algorítmica. Este módulo se enfocó en la integración de **Estructuras de Datos No Lineales Avanzadas** para optimizar el rendimiento y la complejidad de las recomendaciones.

---

## 🎯 Enfoque y Logros Clave (BACKEND)

El backend cumple con la función de un sistema escalable y sin estado:

**Algoritmos de Recomendación:** Implementación del **Algoritmo de Dijkstra** (con PriorityQueue) en el **Grafo de Similitud** para generar listas de reproducción por afinidad musical ("Radio Automática").
**Búsqueda de Alto Rendimiento:** Desarrollo de un **Árbol Trie** (Prefix Tree) que permite el **autocompletado instantáneo** de canciones con una complejidad O(L), superando la lentitud de las búsquedas SQL tradicionales.
**Seguridad y Escalabilidad:** Uso de **JAVA 21** con **Spring Boot 3.5.6** y seguridad basada en **Tokens JWT** (sin sesiones en el servidor), lo que permite atender a miles de usuarios concurrentes.
**Análisis de Datos:** Manejo de **Consultas JPQL optimizadas** (GROUP BY) en el *MetricsService* para generar reportes y el **Dashboard Administrativo** sin saturar la memoria del servidor.

## 🛠️ Tecnologías Utilizadas

### Core & Frameworks
- **Lenguaje:** **JAVA 21** 
- **Framework:** **Spring Boot 3.5.6** (para API RESTful y ORM)
- **Gestión de Dependencias:** Maven
- **Seguridad:** JSON Web Tokens (JWT), OAuth2: Autenticacion con Google

### Estructuras de Datos Avanzadas
- **Grafo de Similitud:** Implementado con Lista de Adyacencia y **Dijkstra**.
- **Grafo Social:** Implementado con un **Grafo No Ponderado** y **BFS** para sugerencia de amigos.
- **Búsqueda:** **Árbol Trie** (Prefix Tree) para autocompletado.

---

## ✨ Colaboración y Módulos Clave

Este proyecto fue desarrollado en colaboración académica entre **Daniel Cifuentes Blandon (Backend)** y **Miguel Angel Villegas (Frontend)**.

* **Rol Principal del Módulo:** Arquitectura de los servicios, implementación de los algoritmos de Grafos y Tries, y seguridad de la API.

## ⚙️ Instrucciones para Ejecutar (Setup)

*(Mantén las instrucciones para ejecutar el servidor Spring Boot, que típicamente involucra Maven o un IDE como IntelliJ.)*

## 🔗 Colaboración y Repositorios Relacionados

* **Módulo Frontend (Angular):** [https://github.com/MAngel4311/syncup-frontend]
* **Perfiles de autores:** @DanielCifuentes1997, @MAngel4311

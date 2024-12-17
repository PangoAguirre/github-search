# Buscador Inteligente de Repositorios de GitHub

## **Objetivo**
Crear una aplicación funcional que permita a los usuarios buscar y explorar repositorios de GitHub, con funcionalidades avanzadas como filtros dinámicos, favoritos persistentes y un diseño atractivo.

---

## **Requerimientos Funcionales**

1. **Búsqueda de repositorios:**
   - Implementar una barra de búsqueda donde el usuario pueda ingresar palabras clave.
   - Al realizar una búsqueda, consultar la API de GitHub y mostrar los resultados.

2. **Visualización de resultados:**
   - Mostrar los repositorios en un formato de lista con la siguiente información:
     - Nombre del repositorio.
     - Descripción.
     - Número de estrellas.
     - Lenguaje principal.
     - Número de forks.

3. **Favoritos:**
   - Permitir al usuario marcar repositorios como favoritos.
   - Mostrar una lista separada de repositorios marcados como favoritos.
   - Los favoritos deben persistir entre recargas de la página.

4. **Filtros dinámicos:**
   - Implementar filtros para refinar los resultados:
     - Por lenguaje de programación.
     - Por número de estrellas (e.g., más de X estrellas).
   - Los filtros deben ser combinables (e.g., aplicar varios al mismo tiempo).

5. **Manejo de estados:**
   - Mostrar un indicador de carga mientras se obtienen los resultados de la búsqueda.
   - Manejar errores en caso de que la API no responda o falle.
   - Mostrar un mensaje si no se encuentran resultados.

---

## **Requerimientos No Funcionales**

1. **Diseño:**
   - La aplicación debe ser responsiva y adaptarse a diferentes tamaños de pantalla.
   - El diseño debe ser limpio, moderno y profesional.

2. **Optimización:**
   - Garantizar una buena experiencia de usuario minimizando el tiempo de carga.
   - Evitar re-renderizados innecesarios para mejorar el rendimiento.

3. **Persistencia:**
   - Usar `localStorage` o un mecanismo similar para guardar los favoritos.

4. **Accesibilidad:**
   - La interfaz debe ser accesible para usuarios con necesidades especiales (e.g., soporte para teclado y lectores de pantalla).

---

## **Criterios de Evaluación**

1. **Funcionalidad:**
   - La aplicación cumple con todos los requerimientos funcionales.
2. **Diseño:**
   - La interfaz es atractiva, responsiva y profesional.
3. **Optimización:**
   - Se minimizan los tiempos de carga y se garantiza un rendimiento eficiente.
4. **Accesibilidad:**
   - La aplicación es usable para todos los usuarios, incluidos aquellos con necesidades especiales.
5. **Código:**
   - El código es legible, modular y sigue buenas prácticas de desarrollo.

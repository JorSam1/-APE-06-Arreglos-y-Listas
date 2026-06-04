# APE-06: Arreglos y Listas 🚀

![Estructuras de Datos](https://img.shields.io/badge/Asignatura-Estructuras%20de%20Datos-blue?style=for-the-badge)
![Universidad](https://img.shields.io/badge/Universidad-UTA-red?style=for-the-badge)
![Lenguajes](https://img.shields.io/badge/Lenguajes-Java%20%7C%20C%2B%2B%20%7C%20PSeInt-orange?style=for-the-badge)

Este repositorio contiene la resolución e implementación de la guía práctica **APE-06 (Aprendizaje Práctico Experimental)** centrada en el análisis, diseño y evaluación de rendimiento de estructuras de datos lineales fijas y dinámicas.

---

## 📋 Descripción del Proyecto

El objetivo principal de esta práctica es contrastar las diferencias mecánicas y estructurales entre la **memoria estática** (arreglos fijos) y la **memoria dinámica** (colecciones redimensionables y listas enlazadas), evaluando su impacto en la memoria RAM del sistema y su complejidad algorítmica ($O$).

El proyecto aborda la abstracción de soluciones lógicas mediante tres entornos distintos:
*   **PSeInt:** Diseño lógico fundamental y diagramación estructurada.
*   **Java:** Implementación orientada a objetos analizando colecciones indexadas (`ArrayList`) y manejo de wrappers/autoboxing.
*   **C++:** Gestión eficiente de memoria contigua (`std::vector`) y estructuras dispersas basadas en nodos y punteros (`std::list`).

---

## 🛠️ Contenido de la Práctica (10 Ejercicios)

El repositorio se divide en tres bloques analíticos fundamentales:

### Parte 1: Colecciones Indexadas Dinámicas I (ArrayList I)
*   **Ejercicio 1:** Inicialización y recorrido lineal de colecciones secuenciales ($O(n)$).
*   **Ejercicio 2:** Tratamiento numérico y cálculo aritmético de datos reales.
*   **Ejercicio 3:** Implementación y métricas del algoritmo de **Búsqueda Secuencial** en el peor caso ($O(n)$).

### Parte 2: Operaciones Transaccionales Complejas (ArrayList II)
*   **Ejercicio 4:** Simulación y lógica interna de un menú transaccional **CRUD** (Análisis de corrimiento físico de memoria).
*   **Ejercicio 5:** Vinculación acoplada y manejo de estructuras/objetos compuestos para registros de entidades.
*   **Ejercicio 6:** Procesamiento lineal acumulativo de inventarios comerciales.

### Parte 3: Evaluación Estructural y Estructuras Enlazadas
*   **Ejercicio 7:** Demostración empírica de mutabilidad: Arreglos estáticos vs. Colecciones dinámicas.
*   **Ejercicio 8:** Simulación en bajo nivel del impacto computacional del desplazamiento de bytes (*Shifting*).
*   **Ejercicio 9:** Migración estructural hacia listas doblemente enlazadas (`LinkedList`) para inserciones en tiempo constante ($O(1)$).
*   **Ejercicio 10:** Modelado abstracto de una estructura de datos de tipo **Cola** bajo la estricta política **FIFO** (First In, First Out).

---

## 📊 Conclusiones del Análisis de Rendimiento

1. **Acceso Indexado ($O(1)$):** Las estructuras contiguas (`std::vector` / `ArrayList`) son idóneas para consultas rápidas por índice, pero penalizan drásticamente el rendimiento con costos de $O(n)$ al realizar inserciones o eliminaciones intermedias debido al desplazamiento físico de bits en memoria.
2. **Modificaciones Eficientes ($O(1)$):** Las listas enlazadas (`LinkedList` / `std::list`) eliminan la necesidad de reordenar bytes en memoria mediante el enlace dinámico de nodos por punteros, optimizando las operaciones en los extremos a costa de sacrificar el acceso directo.

---

## ✒️ Autor

*   **J. S. Bravo López** - *Desarrollo e Implementación* - [JorSam1](https://github.com/JorSam1)
*   **Institución:** Universidad Técnica de Ambato (UTA)
*   **Carrera:** Ingeniería de Software
*   **Año:** 2026

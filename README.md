# Traductor Automático de Código Fortran a Python

Este repositorio contiene el desarrollo de un traductor automático capaz de convertir programas escritos en **Fortran** a código equivalente en **Python**. La herramienta ha sido diseñada para facilitar la modernización de software científico legado, permitiendo ejecutar código antiguo en entornos modernos de desarrollo.

## 🛠️ Tecnologías Utilizadas

- **Flex** – Para el análisis léxico
- **Bison** – Para el análisis sintáctico
- **C++** – Para compilar y generar el ejecutable final

## 🧠 ¿Qué puede traducir este compilador?

La herramienta soporta actualmente:

- Declaraciones de variables: `INTEGER`, `REAL`, `CHARACTER`
- Estructuras condicionales: `IF - THEN - ELSE - ENDIF` (incluyendo anidadas)
- Bucles `DO` (indexados, condicionales, infinitos)
- Funciones con y sin parámetros
- Recursividad
- Expresiones aritméticas y operaciones lógicas
- Entrada/Salida: `WRITE`, `READ`
- Llamadas a procedimientos (`CALL`)
- Comentarios (`!`) que se traducen a `#` en Python

## 🧪 Casos de prueba

Incluye varios ejemplos reales de conversión, como:

- Cálculo del factorial con recursividad
- Estructuras condicionales anidadas
- Prueba computacional basada en el Último Teorema de Fermat

Todos los programas generados en Python son funcionales, legibles y mantienen la lógica del código original en Fortran.

## 📂 Estructura del proyecto


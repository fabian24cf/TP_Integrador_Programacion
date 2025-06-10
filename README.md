# Algoritmos de Búsqueda y Ordenamiento en Python

## 📋 Descripción del Proyecto

Este proyecto implementa y analiza diversos algoritmos de búsqueda y ordenamiento aplicados a un sistema simulado de paradas de transporte público. Desarrollado como trabajo integrador para la materia Programación I de la UTN.

## 👥 Autores

- **Lautaro Ariel Cejas** - [lauti217@live.com](mailto:lauti217@live.com)
- **Fabián Ignacio Cardozo** - [fabian21cf@gmail.com](mailto:fabian21cf@gmail.com)

**Materia:** Programación I  
**Profesor:** Ariel Enferrel  
**Comisión:** 11  
**Fecha de entrega:** 09/05/2025

## 🎯 Objetivos

- Implementar y comparar algoritmos de búsqueda: lineal, binaria, interpolación y hash
- Analizar el algoritmo de ordenamiento burbuja (bubble sort)
- Evaluar el rendimiento y eficiencia computacional de cada algoritmo
- Aplicar los conceptos teóricos en un caso práctico real

## 🚌 Caso de Estudio

El sistema simula la gestión de paradas de transporte público, donde cada parada se caracteriza por:
- **Nombre**: Identificador textual de la parada
- **Distancia**: Distancia numérica desde un punto de origen

## 🔧 Algoritmos Implementados

### Algoritmos de Búsqueda

#### 1. Búsqueda Lineal
- **Complejidad:** O(n)
- **Requiere orden:** No
- **Características:** Recorre secuencialmente hasta encontrar el elemento

#### 2. Búsqueda Binaria
- **Complejidad:** O(log n)
- **Requiere orden:** Sí
- **Características:** Divide el conjunto ordenado por la mitad en cada iteración

#### 3. Búsqueda por Interpolación
- **Complejidad:** O(log log n) promedio, O(n) peor caso
- **Requiere orden:** Sí
- **Características:** Estima la posición del elemento basándose en su valor

#### 4. Búsqueda Hash
- **Complejidad:** O(1) promedio, O(n) peor caso
- **Requiere orden:** No
- **Características:** Acceso directo mediante tabla hash (diccionario)

### Algoritmo de Ordenamiento

#### Bubble Sort (Ordenamiento por Burbuja)
- **Complejidad:** O(n²)
- **Estabilidad:** Sí
- **Implementado para:** Ordenamiento alfabético (por nombre) y numérico (por distancia)

## 📊 Resultados Principales

### Tiempos de Ejecución (para 5 paradas)
- **Búsqueda Hash:** ~0.005 ms (más eficiente)
- **Búsqueda Lineal:** ~0.007 ms
- **Búsqueda Binaria:** ~0.022 ms (incluye ordenamiento)
- **Búsqueda Interpolación:** ~0.007 ms (incluye ordenamiento)

### Comparación: Listas Ordenadas vs Desordenadas
- **Búsqueda Lineal:** Sin diferencia significativa
- **Búsqueda Binaria:** Mejor rendimiento con listas pre-ordenadas
- **Búsqueda Hash:** Sin diferencia (no depende del orden)

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Python 3.13.3
- **Entorno de Desarrollo:** Visual Studio Code
- **Control de Versiones:** GitHub
- **Medición de Tiempos:** Librería `time`
- **Edición de Video:** OBS Studio, Shotcut

## 🚀 Cómo Ejecutar el Proyecto

1. **Clonar el repositorio:**
```bash
git clone https://github.com/Lautaro-Cejas/tp-integrador-byo
cd algoritmos-busqueda-ordenamiento
```

2. **Ejecutar el programa principal:**
```bash
cd src
python busqueda_paradas.py
```

3. **Navegar por el menú interactivo** para probar diferentes algoritmos

## 📁 Estructura del Proyecto

```
proyecto/
├── src/
    └── busqueda_paradas.py    # Código
├── README.md                  # Este archivo
├── docs/
    └── Trabajo Integrador - 
    Búsqueda y ordenamiento - 
    Fabian Cardozo, Lautaro Cejas - 
    COM 11.pdf                 # Documentación completa

```

## 🔍 Funcionalidades

- **Búsqueda por nombre de parada**
- **Búsqueda por distancia**
- **Ordenamiento de paradas** (alfabético y numérico)
- **Medición de tiempos de ejecución**
- **Comparación de rendimiento** entre algoritmos
- **Interfaz de consola interactiva**

## 📈 Casos de Uso

### Casos Favorables
- **Búsqueda Lineal:** Elemento al inicio de la lista
- **Búsqueda Binaria:** Elemento en el medio de la lista ordenada
- **Búsqueda Hash:** Cualquier elemento existente
- **Interpolación:** Datos uniformemente distribuidos

### Casos Desfavorables
- **Búsqueda Lineal:** Elemento al final o inexistente
- **Búsqueda Binaria:** Elemento inexistente (máximo número de divisiones)
- **Búsqueda Hash:** Múltiples colisiones
- **Interpolación:** Datos mal distribuidos

## 💡 Recomendaciones de Uso

### Para Sistemas de Transporte
- **Consultas frecuentes:** Usar búsqueda hash
- **Listas pequeñas (<10 elementos):** Búsqueda lineal
- **Listas grandes pre-ordenadas:** Búsqueda binaria
- **Datos uniformes:** Búsqueda por interpolación

## 🔧 Posibles Mejoras

- **Estructuras más eficientes:** Árboles AVL, Árboles Rojo-Negro
- **Estructuras híbridas:** Combinación de hash y árboles
- **Optimización para datasets grandes:** Implementación de algoritmos más avanzados

## 📚 Referencias

- Downey, A. (2015). *Think Python (2nd ed.)*. O'Reilly Media
- Sweigart, A. (2020). *Automate the Boring Stuff with Python (2nd ed.)*. No Starch Press
- Cormen, T. H. et al. (2009). *Introduction to Algorithms (3rd ed.)*. MIT Press

## 🎥 Material Complementario

- **Video Explicativo:** [Ver en YouTube](https://www.youtube.com/watch?v=sP-I6tHQFGI)
- **Documentación Completa:** Disponible en el archivo PDF del proyecto

## 📧 Contacto

Para consultas o colaboraciones, contactar a los autores:
- Lautaro Cejas: [lauti217@live.com](mailto:lauti217@live.com)
- Fabián Cardozo: [fabian21cf@gmail.com](mailto:fabian21cf@gmail.com)
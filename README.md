# Cobertura-indoor-de-campus

Adaptar el ejercicio de penetración indoor a un edificio real donde interesa que funcionen voz, mensajería y acceso a plataformas digitales.

## Descripción

Este proyecto simula y analiza la cobertura indoor en un edificio multi-planta utilizando herramientas open source como Python y Jupyter. El objetivo es determinar si la cobertura exterior es suficiente o si se requieren soluciones de refuerzo como DAS, repetidores o small cells.

## Estructura del Proyecto

- `ejercicio_cobertura_indoor.ipynb`: Notebook principal con el ejercicio completo, incluyendo cálculos, visualizaciones y recomendaciones.

## Requisitos

- Python 3.x
- Librerías: numpy, pandas, matplotlib, geopandas

Instalar dependencias:
```
pip install numpy pandas matplotlib geopandas
```

## Uso

Ejecutar el notebook en Jupyter para realizar los cálculos y visualizar los resultados.

## Conceptos Cubiertos

- Pérdida outdoor-to-indoor
- Penetración por fachada, paredes y forjados
- Interpolación
- Presupuesto de enlace

## Datos de Partida

- Portadora LTE 1800 MHz o UMTS 2100 MHz
- Antena exterior a 20-25 m
- Pérdidas típicas: fachada 12-18 dB, pared interior 3-5 dB, forjado 12-18 dB

## Tareas

- Definir puntos de usuario: entrada, aula segunda planta, semisótano
- Calcular pérdidas totales
- Verificar umbrales para voz y datos
- Proponer soluciones de mejora
- Crear tabla y croquis
- Comparar con otras frecuencias (opcional) 
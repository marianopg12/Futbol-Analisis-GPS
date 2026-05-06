# ⚽ Performance Hub V2.0 - GPS & Athletic Analytics

**Performance Hub V2.0** es una aplicación interactiva desarrollada con **Streamlit** diseñada para cuerpos técnicos, preparadores físicos y analistas de rendimiento deportivo. La plataforma centraliza datos provenientes de dispositivos GPS y evaluaciones físicas (fuerza y salto) para visualizar el perfil atlético de los futbolistas de forma clara y profesional.
A modo de testeo, con GPS ActionTracer, fabricacion en china. 
---

## 🚀 Características Principales

*   **Visualización Multidimensional**: Análisis de métricas clave como Velocidad Máxima, Distancia Total, Sprints y Aceleración.
*   **Perfil Atlético (Radar)**: Comparativa visual directa entre el rendimiento del jugador seleccionado y el promedio del plantel.
*   **Análisis de Alta Intensidad**: Pestaña dedicada a la potencia de sprint y eficiencia mecánica (metros recorridos por sprint).
*   **Modo Reporte**: Capacidad de generar perfiles de todos los jugadores simultáneamente para revisión rápida.
*   **Exportación Inteligente**: Botón de impresión optimizado con reglas CSS para exportar a PDF sin cortes de página y ocultando elementos de navegación.
*   **Leaderboard Dinámico**: Ranking automático del equipo basado en diferentes variables de rendimiento.

---

## 🛠️ Tecnologías Utilizadas

*   **Lenguaje**: Python 3.x
*   **Framework Web**: [Streamlit](https://streamlit.io/)
*   **Visualización**: [Plotly Graph Objects](https://plotly.com/python/) & [Express](https://plotly.com/python/plotly-express/)
*   **Procesamiento de Datos**: [Pandas](https://pandas.pydata.org/) & [NumPy](https://numpy.org/)
*   **Lectura de Archivos**: `xlrd` / `openpyxl` para soporte de Excel (.xls).

---

## 📋 Requisitos Previos

Asegúrate de tener instaladas las dependencias necesarias. Puedes instalarlas ejecutando:
```bash
pip install streamlit pandas numpy plotly xlrd openpyxl

# 📊 Monitoreo Diario de Redes Sociales

Este repositorio alberga el tablero ejecutivo interactivo para la visualización y análisis del rendimiento digital diario de la **Secretaría de Igualdad e Inclusión** y **Félix Arratia**. 

El sistema está diseñado para funcionar de manera completamente autónoma mediante **GitHub Pages**, consumiendo datos estructurados directamente desde un libro de trabajo en Excel (`Redes.xlsx`) y desplegándolos en un reporte ejecutivo optimizado para escritorio y dispositivos móviles.

---

## 🚀 Características Principales

* **Carga Automática de Datos:** Lee dinámicamente las hojas del archivo `Redes.xlsx` al cargar la página sin requerir intervención manual del usuario.
* **Resumen Ejecutivo por Cuenta:** Muestra el total de seguidores acumulados, publicaciones realizdas y KPIs principales (reacciones, comentarios, reposts y visualizaciones).
* **Gráficos Comparativos por Red Social:** Integración con **Chart.js** para comparar de forma clara el volumen de *Publicaciones* y *Reacciones* entre Facebook e Instagram para cada perfil.
* **Publicaciones Destacadas:** Tarjetas con diseño limpio y adaptable para exponer hasta 2 notas clave con su motivo de selección, métricas individuales e imagen asociada.
* **Tabla de Actividad Detallada:** Desglose completo de todas las publicaciones del periodo con enlaces directos al contenido original.
* **Modo Impresión / PDF:** Botón listo para generar reportes físicos o exportaciones a PDF con estilos optimizados para impresión.

---

## 📁 Estructura del Repositorio

```text
monitoreo-redes/
├── index.html          # Interfaz y lógica del tablero (HTML, CSS y JavaScript)
├── Redes.xlsx          # Base de datos en Excel con los cortes de información
├── Logo.png            # Avatar predeterminado para la Secretaría de Igualdad e Inclusión
├── Felix.png           # Avatar predeterminado para Félix Arratia
└── imagenes/           # Carpeta con las capturas/imágenes de las notas destacadas
    ├── 27082026_101.png
    └── 27082026_102.png

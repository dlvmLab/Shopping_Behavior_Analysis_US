```markdown
# 📊 Análisis de Comportamiento de Compra en EE.UU. _ esto es provisional- y este también- probando-


## 📖 Descripción
**Análisis Exploratorio de Datos (EDA)** sobre el comportamiento de compras en Estados Unidos, basado en transacciones con categoría, monto, fecha, canal y demografía (edad y género).

- **Limpieza**: eliminación de duplicados, manejo de valores faltantes, estandarización de formatos.
- **Transformación**: extracción de componentes de fecha, creación de variables derivadas (ej. ticket promedio).
- **Análisis descriptivo**: estadísticas por categoría/canal, tendencias temporales, relaciones entre variables.
- **Visualizaciones**: tablas dinámicas, top 5 y bottom 5 con mapas, gráficos de dona para accesorios, dashboard interactivo con movimiento estacional de compras e ingresos.
- **Informe**: resumen de patrones y hallazgos clave.

> **Objetivo**: Determinar la influencia de la demografía (jóvenes, adultos, adultos mayores; hombres y mujeres) en la estacionalidad de compras, método de pago preferido, envío a domicilio, demanda por estado (alta/baja), y distribución de productos (equitativa en prendas; menor en calzado y ropa exterior).

---

## 🗂 Estructura del Proyecto
```
├── data/
│   ├── raw/
│   │   └── shopping_behaviour.csv              # Datos crudos originales
│   └── processed/
│       └── Shopping_Analysis.xlsx              # Libro Excel con macros VBA:
│                                           # • shopping_behavior_updated (datos limpios, transformados y con verificación de outliers)
│                                           # • Verifications (verificación exclusiva de duplicados y valores nulos)
│                                           # • Outliers (análisis dedicado a detección y tratamiento de valores atípicos)
│                                           # • Exploratory_Analysis (verificación de suposiciones mediante tablas dinámicas y gráficos)
│                                           # • Dashboard (informe interactivo final con filtros y conclusiones clave)
├── results/
│   ├── figuras/                                # Gráficos exportados
│   └── shopping_report.pdf                     # Informe final en PDF (en inglés)
└── README.md
```

> **Nota**: Todo el procesamiento, análisis y visualización se realiza **100% en Excel con macros VBA**.  
> **Idioma del proyecto**: Los datos fueron obtenidos originalmente en **inglés**, por lo que se mantiene fielmente el idioma en nombres de pestañas, etiquetas y código para preservar la esencia y consistencia del dataset. Esta es la versión en **español** del README — también existe una versión en **inglés** en el repositorio.

---

## 🛠 Instalación y Requisitos
**No requiere instalación de software adicional.**

| Herramienta         | Versión recomendada          | Uso |
|---------------------|------------------------------|-----|
| **Microsoft Excel** | 2016 o superior (macros habilitadas) | Limpieza, transformación, análisis, tablas dinámicas, dashboard interactivo |
| **Lector de CSV**   | Cualquier (Excel, Bloc de notas) | Visualización de datos crudos |

### Pasos para ejecutar:
1. **Clonar repositorio**
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   cd nombre_del_proyecto
   ```
2. **Abrir** `data/processed/Shopping_Analysis.xlsx`
3. **Habilitar macros** → "Habilitar contenido"
4. **Explorar pestañas**:
   - `shopping_behavior_updated`: Datos limpios, transformados y verificados (incluye detección de outliers).
   - `Verifications`: Verificación exclusiva de **duplicados** y **valores nulos**.
   - `Outliers`: Análisis específico de valores atípicos (detección, impacto y decisiones).
   - `Exploratory_Analysis`: Verificación de suposiciones mediante tablas dinámicas y gráficos cuando es necesario.
   - `Dashboard`: Informe interactivo final con filtros, conclusiones clave y visualizaciones dinámicas.
5. **Generar informe** → Exportar a PDF desde la pestaña `Dashboard` (ver instrucciones abajo).

---

## 📄 Informe Final (PDF)
- **Archivo**: `results/shopping_report.pdf` *(nombre en inglés para mantener consistencia con el dataset original)*
- **Contenido**: Resumen ejecutivo, hallazgos clave, gráficos destacados y recomendaciones.

### 📑 Instrucciones de Impresión Recomendadas:
1. Abrir el PDF en **Adobe Acrobat Reader** (o similar).
2. Ir a **Archivo > Imprimir**.
3. Configuración sugerida:
   - **Tamaño**: A4
   - **Orientación**: **Horizontal** (para mejor visualización de dashboards y gráficos)
   - **Escala**: "Ajustar a página" o **100%** según prefieras mantener proporciones exactas
   - **Color**: **A color** (imprescindible para gráficos)
   - **Imprimir por ambas caras**: Opcional
4. **Revisar vista previa** antes de imprimir para evitar cortes en elementos visuales.

---

## 📊 Resultados y Conclusiones
- **Demografía y decisiones**:
  - Análisis por bloques etarios (jóvenes, adultos, adultos mayores) y género.
  - Influencia clara en estacionalidad, método de pago y preferencia de envío.

- **Distribución geográfica**:
  - Tablas top 5 / bottom 5 con mapas gráficos.
  - Identificación de estados con mayor y menor demanda.

- **Productos**:
  - Demanda equitativa entre prendas.
  - Accesorios (gráfico de dona): **calzado** y **ropa exterior** con menor demanda.

- **Tendencias temporales**:
  - Dashboard muestra **picos de mayor venta** claramente correlacionados con el **revenue generado**.
  - Se observan **máximos estacionales en invierno y primavera**, con mayor volumen de transacciones e ingresos en estas estaciones.

---

## 🔄 Próximos Pasos
- Incorporar datos externos (clima, eventos) para enriquecer análisis estacional.
- Segmentación más fina por canal de compra y frecuencia.
- Automatización de exportación del dashboard a PowerPoint/PDF.

---

## 🤝 Contribuciones
Bienvenidas. Abre un *issue* o *pull request* para mejoras.

---

## ✒ Autora
**Dayana Valdés**  
📧 [dlvm.focus@gmail.com](mailto:dlvm.focus@gmail.com)  
🔗 [linkedin.com/in/dayanavm](https://linkedin.com/in/dayanavm) | [github.com/dlvmLab](https://github.com/dlvmLab)

- Análisis realizado con Excel VBA y visualizaciones interactivas.
- Contribuciones técnicas: **macros VBA**, **dashboard interactivo** y **procesamiento automatizado de datos**.

---

> **Proyecto desarrollado como parte del Máster en Data & Analytics V3 de The PowerMBA**  
> *Última actualización: 30 de octubre de 2025*
```
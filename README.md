```markdown
# 📊 Análisis de Comportamiento de Compra en EE.UU.
**Dashboard interactivo 100% en Excel con VBA**
> **Hallazgo clave**: La gráfica comparativa **Compras vs Ingresos** refleja cómo responden **volumen de ventas** y **rentabilidad** a cada filtro — ideal para identificar segmentos de alto valor.
---
## 📖 Descripción del Proyecto
Análisis Exploratorio de Datos (EDA) sobre transacciones de compras en Estados Unidos.
**Variables clave**:
- Categorías de prendas
- Estación del año
- Demografía (edad, género, ubicación)
- Estado de suscripción
- Uso de código promocional
- Descuento aplicado
- Tipo de envío preferido
- Método de pago preferido
**Proceso realizado**:
- **Limpieza**: eliminación de duplicados, tratamiento de nulos, corrección de formatos
- **Transformación**: no fue necesario modificar la estructura de los datos
- **Visualizaciones**: tablas dinámicas + gráficos interactivos → **dashboard**
- **Informe**: PDF con insights accionables y recomendaciones.
---
## 🗂 Estructura del Repositorio
```
├── data/
│   ├── raw/shopping_behaviour.csv
│   └── processed/Shopping_Behavior_Analysis_US ← Archivo principal con VBA
│       ├── shopping_behavior_updated → datos limpios + outliers tratados
│       ├── Verifications → validación de duplicados y nulos
│       ├── Outliers → detección y manejo de valores atípicos
│       ├── Exploratory_Analysis → tablas y gráficos exploratorios
│       └── Dashboard → **interfaz interactiva con 5 filtros exclusivos**
├── results/
│   └── shopping_report.pdf → informe final en PDF
└── README.md
```
> **Idioma del dataset**: Inglés (original)
> **Idioma del Excel**: Inglés (nombres de pestañas y variables)
> **Idioma del README**: Español
---
## 🛠 Requisitos y Ejecución
| Herramienta | Requisito |
|-------------------|----------------------------------------|
| **Excel** | Versión 2016 o superior + **macros habilitadas** |
| **Visor CSV** | Cualquier (para ver datos crudos) |
### Pasos para usar el dashboard:
1. Clonar el repositorio
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   cd nombre-del-proyecto
   ```
2. Abrir el archivo:
   `data/processed/Shopping_Behavior_Analysis_US`
3. **Habilitar macros** al abrir (esencial para el funcionamiento)
4. Ir a la pestaña **`Dashboard`**
5. **Aplicar los 5 filtros dinámicos**:
   - Estado de suscripción (Sí/No)
   - Uso de código promocional (Sí/No)
   - Descuento aplicado (Sí/No)
   - Grupo etario (Jóvenes / Adultos / Adultos mayores)
   - Género (Hombre / Mujer)
---
## 📊 Dashboard Interactivo (`Dashboard`)
- **Gráfica estrella**: **Compras vs Ingresos**
  → Actualización al filtrar. Permite ver cómo varían **volumen** y **ganancia** por segmento.
- **5 Filtros exclusivos y dinámicos**:
1. **Suscripción**
2. **Código promocional usado**
3. **Descuento aplicado**
4. **Edad** (Jóvenes: 18-35 | Adultos: 36-55 | Mayores: 56+)
5. **Género**
- **Análisis interactivo inmediato**:
- Efecto de promociones en volumen vs margen
- Diferencias entre suscriptores y no suscriptores
- Rentabilidad por demografía y estación
- Segmentos de mayor valor comercial
---
## 📄 Informe Final
- **Archivo**: `results/shopping_report.pdf`
- **Formato de impresión recomendado**:
  A4 | **Horizontal** | **A color** | Escala 100% o ajustar a página
---
## 🔍 Conclusiones Clave
- **Mujeres**: compran más en **otoño** y **primavera**
- **Hombres**: lideran en **primavera** e **invierno**
- **Invierno**: alta actividad general, **excepto en mayores de 56 años** (¿relacionado con clima?)
- **Promociones y descuentos**: más usados por **no suscriptores** → posible vía de captación
- **Categorías menos vendidas**: **ropa de exterior (outerwear)** y **calzado**, a pesar de que los estados líderes (Wisconsin, Arizona, Rhode Island, Delaware, Ohio) tienen climas variados
- **Categorías top**: **accesorios** y **ropa general**
- **Primavera** → mayor volumen de compras
- **Otoño** → mayor **ingreso neto** (mayor ticket promedio)
---
## 🚀 Mejoras Pendientes y Futuras
| Estado | Mejora |
|--------------|------------------------------------------------------------------------|
| ⏳ **Pendiente** | **Traducir este README al inglés** (idioma original del dataset) |
| ✅ Completado | Dashboard interactivo con VBA |
| ✅ Completado | Informe PDF con insights accionables |
| 🔄 Futura | Añadir segmentación por estado |
---
## 🤝 Contribuciones
¡Toda mejora es bienvenida!
- Abre un **issue** para reportar errores o sugerir ideas
- Envía un **Pull Request** con mejoras (ej: traducción, nuevas visualizaciones, optimización de código VBA)
---
## ✒ Autora
**Dayana Valdés**
📧 [dlvm.focus@gmail.com](mailto:dlvm.focus@gmail.com)
🔗 [linkedin.com/in/dayanavm](https://linkedin.com/in/dayanavm) | [github.com/dlvmLab](https://github.com/dlvmLab)
> **Proyecto como parte del módulo DASHBOARD & ANÁLISIS DE DATOS – Máster en Data & Analytics V3 – The PowerMBA**
*Actualizado: 2 de noviembre de 2025*
```
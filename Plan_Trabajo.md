## Plan de Trabajo: Proyecto de Análisis de Datos con Amazon Sales Dataset

### 🏆 Objetivo General
Dominar herramientas y técnicas clave para el análisis de datos, aplicando SQL, Python, Power BI, y Git/GitHub, mientras desarrollas habilidades de análisis de negocios, limpieza de datos, visualización y storytelling.

---

### 🚀 Buenas Prácticas de Git

- **Commits claros y concisos:** Utilizar el formato `tipo: descripción`, donde el tipo puede ser:
  - `feat`: Nueva característica o funcionalidad.
  - `fix`: Corrección de errores.
  - `docs`: Cambios en la documentación.
  - `refactor`: Reestructuración de código sin cambiar su funcionalidad.
  - `test`: Agregar o modificar pruebas.
  - `chore`: Actualizaciones menores o tareas de mantenimiento.
  - `style`: Cambios de formato, comas, espacios, etc.
  - `ci`: Cambios relacionados con la integración continua.
- **Ramas organizadas:** Crear ramas específicas para cada fase o tarea importante siguiendo una convención clara, por ejemplo:
  - `fase1-comprension-negocio`
  - `exploracion-datos`
  - `EDA`
  - `visualizacion-datos`
  - `storytelling`
- **Pull Requests (PR):** Realizar PR después de completar tareas importantes, agregando descripciones claras sobre lo que se implementó.
- **.gitignore personalizado:** Incluir un archivo `.gitignore` para excluir archivos temporales, datasets crudos o credenciales.
- **Revisiones colaborativas:** Aunque trabajes solo, acostumbrarse a revisar los cambios antes de hacer un merge.
- **Documentación continua:** Actualizar el `README.md` con cada avance importante del proyecto.

---

### 1️⃣ Fase 1: Comprensión del Negocio
**Objetivo:** Definir las metas del análisis y las preguntas clave.

- **Habilidades a desarrollar:**
  - Pensamiento crítico para identificar problemas de negocio.
  - Enfoque estratégico para formular preguntas clave.
  - Documentación clara para guiar el análisis.
  - Gestión de ramas en Git.

- **Objetivo principal:** Realizar un análisis robusto que combine varios enfoques para obtener una visión integral del marketplace de Amazon.
- **Enfoques a combinar:**
  1. **Optimización de ventas:** Identificar productos, categorías y vendedores clave para aumentar ingresos.
  2. **Análisis de clientes:** Detectar patrones de compra, preferencias y calificaciones de los clientes.
  3. **Eficiencia operativa:** Evaluar cómo los descuentos, envíos y precios afectan las ventas y los márgenes de ganancia.

- **Preguntas de negocio:**
  - **Ventas:** ¿Cuáles son las categorías de productos más y menos rentables?
  - **Vendedores:** ¿Qué vendedores generan más ingresos y cuáles tienen márgenes bajos?
  - **Clientes:** ¿Qué patrones de compra muestran los clientes más frecuentes?
  - **Descuentos:** ¿Cómo afectan los descuentos y las promociones al volumen de ventas?
  - **Calificaciones:** ¿Existe una relación entre las calificaciones de los productos y sus ventas?
  - **Tendencias:** ¿Cómo varían las ventas a lo largo del tiempo y existen patrones estacionales?

- **Git:**
  - Crear la rama `fase1-comprension-negocio`.
  - Hacer commits después de definir objetivos, enfoques y preguntas clave.
  - Actualizar el `README.md` con las metas y objetivos del proyecto.

---

### 2️⃣ Fase 2: Exploración y Preparación de Datos
**Objetivo:** Realizar un análisis inicial de los datos y prepararlos para el análisis.

- **Habilidades a desarrollar:**
  - SQL para exploración de bases de datos.
  - Python para manipulación de datos.
  - Técnicas de limpieza y transformación de datos.
  - Control de versiones con Git.

- **SQL:**
  - Inspeccionar las tablas: columnas, tipos de datos y relaciones.
  - Identificar valores nulos, duplicados o inconsistencias.
- **Python:**
  - Importar datos y crear un DataFrame.
  - Explorar estadísticas descriptivas (media, mediana, moda).
- **Tareas de limpieza:**
  - Eliminar duplicados.
  - Corregir formatos de fecha, moneda y categorías.
  - Rellenar o eliminar valores nulos según el contexto.
  - Unificar nombres de productos y vendedores.
- **Git:**
  - Crear la rama `exploracion-datos`.
  - Hacer commits después de cada proceso importante (inspección, limpieza, unificación).
  - Añadir un archivo `.gitignore` para excluir archivos temporales.

---

### 3️⃣ Fase 3: Análisis Exploratorio de Datos (EDA)
**Objetivo:** Descubrir patrones, correlaciones y tendencias.

- **Habilidades a desarrollar:**
  - Análisis estadístico descriptivo.
  - Consultas avanzadas con SQL.
  - Visualización exploratoria con Python.
  - Buenas prácticas de Git.

- **SQL:**
  - Análisis de ventas por categoría, subcategoría y vendedor.
  - Clientes con mayor volumen de compras.
  - Productos con mayores y menores márgenes de ganancia.
  - Evaluar el impacto de los descuentos en las ventas.
  - Análisis de productos según calificación promedio.
- **Python:**
  - Visualizaciones básicas con Matplotlib y Seaborn.
  - Análisis de correlación entre ventas, precios, descuentos y calificaciones.
  - Detección de tendencias temporales y estacionales.
- **Git:**
  - Crear la rama `EDA`.
  - Hacer commits después de cada análisis clave.
  - Abrir un Pull Request para fusionar hallazgos significativos en la rama principal.

---


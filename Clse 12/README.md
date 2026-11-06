# 📚 Clase 12: Lenguaje SQL y Modelado de Procesos

---

## 📌 Resumen de la Clase

En esta sesión se abordaron los fundamentos del **lenguaje SQL** como estándar de consulta universal para bases de datos relacionales, su utilidad práctica como anexo técnico en el proyecto final (TFC), y metodologías de modelado de procesos industriales mediante diagramas funcionales estructurados.

---

## 🗄️ Lenguaje SQL

* **Definición:** Lenguaje de consulta estructurado, válido y estandarizado para interactuar con prácticamente cualquier sistema de gestión de bases de datos relacionales.
* **Aplicación en el Proyecto Final (TFC):** 
  * Puede incorporarse como anexo técnico para respaldar la gestión de datos.
  * Implica el diseño previo de un **Diagrama Entidad-Relación (DER)**.
  * *Nota de rol:* Aunque tradicionalmente esta tarea suele ser delegada al especialista en informática, representa una competencia clave dentro de las funciones de análisis y organización de procesos del ingeniero industrial.

---

## ⚙️ Modelado de Procesos (Metodología de Cajas)

Para estructurar la información y construir el marco de datos de la empresa, se utiliza una representación gráfica jerárquica:

1. **La Caja Negra (Enfoque de Sistemas):**
   * **Izquierda:** Entradas (*Inputs*).
   * **Derecha:** Salidas (*Outputs*).
   * **Arriba:** Marcos de referencia / restricciones.
   * **Abajo:** Información / mecanismos de control.

2. **Desglose Jerárquico:**
   * La caja principal se descompone en subprocesos (subcajas internas), las cuales a su vez pueden contener más niveles de detalle de forma sucesiva.

3. **Conectores y Relaciones:**
   * Cada línea que vincula un componente o "ladrillo" con otro debe etiquetarse con un **verbo** que describa explícitamente la acción o transformación que se lleva a cabo entre ambos procesos.

---

## 💻 Herramientas y Tecnologías de Software

* **SAP:** Sistema ERP de gestión empresarial para la integración de datos y recursos a gran escala.
* **MySQL Workbench:** Entorno visual de diseño, administración y consulta para bases de datos MySQL.
* **Power BI:** Herramienta de inteligencia de negocios (*Business Intelligence*) orientada a la visualización de datos y generación de reportes interactivos.

# Laboratorio #1: Fundamentos de Programación Web

Este repositorio contiene la solución al **Laboratorio #1** del curso **EIF428O - Fundamentos de Programación Web** de la Universidad Nacional (UNA). El proyecto consiste en la personalización y adaptación de una plantilla de Bootstrap para una pequeña empresa de elementos naturales.

---

## 🏛️ Información Institucional

* **Institución:** Universidad Nacional (UNA)
* **Facultad:** Ciencias Exactas y Naturales
* **Escuela:** Escuela de Informática
* **Carrera:** Bachillerato en Ingeniería en Sistemas de Información (BA-INFORM)
* **Curso:** EIF428O - Fundamentos de programación web
* **Docente:** M.Sc. Olivier Blanco Sandí

---

## 🌿 Descripción del Proyecto

El objetivo principal es transformar una plantilla gratuita de Bootstrap en un sitio web funcional de tres secciones para una microempresa dedicada a la venta de elementos de la naturaleza (piedras, hojas de árboles, flores y ramitas secas).

### Secciones Implementadas
* **Inicio:** Presentación del negocio con los valores y concepto de la marca.
* **Productos:** Grilla de *cards* que muestra el catálogo de elementos (imagen, nombre y precio ficticio).
* **Contacto:** Formulario básico de comunicación.

---

## 🛠️ Requerimientos Técnicos Cumplidos

1. **Adaptación de Plantilla:** Se seleccionó una plantilla Bootstrap limpia, eliminando todo el código, menús, botones y secciones innecesarias para cumplir estrictamente con las 3 secciones solicitadas.
2. **Personalización de Colores (CSS Propio):** Se sobreescribieron los estilos por defecto utilizando un archivo CSS independiente (`custom.css` / `estilos.css`) aplicando la paleta institucional de la UNA:
   * 🔴 **Rojo UNA:** `#CD1719`
   * 🔵 **Azul UNA:** `#034991`
   * ⚪ **Gris UNA:** `#A7A7A9`
3. **Fotografías Propias:** Todas las imágenes de los productos y elementos del sitio fueron tomadas por el equipo dentro de las instalaciones del campus de la UNA, garantizando la autoría del contenido visual.
4. **Diseño Responsivo:** Uso de la grilla nativa de Bootstrap (`row`, `col`) para asegurar que el catálogo de productos sea completamente adaptable a dispositivos móviles y escritorio.

---

## 📁 Estructura del Proyecto

```text
EIF428O_Lab1_Grupo#/
│
├── css/
│   ├── bootstrap.min.css    # Estilos nativos de la plantilla
│   └── personalizado.css    # CSS propio con los colores UNA (#CD1719, #034991, #A7A7A9)
│
├── js/                      # Archivos JavaScript de Bootstrap
│
├── assets/img/              # Fotografías propias tomadas en el campus
│   ├── productos/           # Piedras, hojas, flores y ramas secas
│   └── diseño/              # Banners o fondos de la plantilla
│
├── index.html               # Archivo principal estructurado con las 3 secciones
└── README.md                # Documentación del laboratorio
```



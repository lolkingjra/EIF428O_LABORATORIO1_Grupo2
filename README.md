# Laboratorio #1: Fundamentos de Programación Web

Este repositorio contiene la solución al **Laboratorio #1** del curso **EIF428O - Fundamentos de Programación Web** de la Universidad Nacional (UNA). El proyecto consiste en la personalización y adaptación de una plantilla de Bootstrap (StartBootstrap Grayscale) para una pequeña empresa de elementos naturales recolectados en el campus.

---

## 🏛️ Información Institucional

* **Institución:** Universidad Nacional (UNA)
* **Facultad:** Ciencias Exactas y Naturales
* **Escuela:** Escuela de Informática
* **Carrera:** Bachillerato en Ingeniería en Sistemas de Información (BA-INFORM)
* **Curso:** EIF428O - Fundamentos de programación web
* **Docente:** M.Sc. Olivier Blanco Sandí
* **Grupo:** Grupo 2

**Integrantes:**
* Justin Moreira Matarrita
* Luis Rosales Vargas
* José Rodríguez Arias

---

## 🌿 Descripción del Proyecto

El objetivo principal es adaptar una plantilla gratuita de Bootstrap en un sitio web de 3 secciones para una microempresa dedicada a la venta de elementos de la naturaleza (**piedras, hojas de árboles, flores y ramitas secas**).

### Secciones Implementadas
1. **Inicio (`#inicio`):** Presentación del negocio con los valores y concepto de la marca.
2. **Productos (`#productos`):** Grilla de *cards* responsivas mostrando el catálogo de elementos (imagen de cada tipo de producto, nombre y precio ficticio).
3. **Contacto (`#contacto`):** Formulario básico de comunicación e información institucional.

---

## 🛠️ Requerimientos Técnicos Cumplidos

1. **Adaptación de Plantilla:** Se seleccionó la plantilla Bootstrap Grayscale, eliminando secciones no requeridas para dejar estrictamente las 3 secciones solicitadas.
2. **Personalización de Colores (CSS Propio):** Se creó el archivo `web/css/custom.css` con la paleta de colores institucional de la Universidad Nacional (UNA):
   * 🔴 **Rojo UNA:** `#CD1719`
   * 🔵 **Azul UNA:** `#034991`
   * ⚪ **Gris UNA:** `#A7A7A9`
3. **Fotografías del Campus:** Se integraron fotos de los 4 productos (**piedras, hojas, flores y ramitas secas**) organizadas en `web/assets/img/productos/`.
4. **Grilla Responsiva:** Implementación con clases nativas de Bootstrap (`row-cols-1 row-cols-md-2 row-cols-lg-4 g-4`).

---

## 📁 Estructura del Proyecto (`web/`)

```text
EIF428O_LABORATORIO1_Grupo2/
│
├── README.md                          # Documentación del laboratorio
└── web/                               # Raíz de la solución web
    ├── index.html                     # Archivo principal estructurado (3 secciones)
    ├── css/
    │   ├── styles.css                 # Estilos base de la plantilla
    │   └── custom.css                 # CSS propio con los colores UNA (#CD1719, #034991, #A7A7A9)
    ├── js/
    │   └── scripts.js                 # Lógica de navegación y formulario
    └── assets/
        ├── favicon.ico
        └── img/
            ├── background.png
            └── productos/             # Fotografías del campus
                ├── piedras.jpg
                ├── hojas.jpg
                ├── flores.jpg
                └── ramitas.jpg
```

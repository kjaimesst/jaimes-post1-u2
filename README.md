# Proyecto: Fundamentos de la Web – Unidad 2 (Post 1)

## Descripción

Este proyecto consiste en la creación de una página web básica en HTML como parte de la Unidad 2.

El objetivo es comprender los fundamentos del desarrollo web, incluyendo la estructura de una página, el uso de etiquetas HTML y la introducción al control de versiones con Git y GitHub.

---

## Objetivos de aprendizaje

* Comprender la estructura básica de un documento HTML
* Utilizar etiquetas como `<h1>`, `<p>`, `<ul>` y `<li>`
* Identificar conceptos clave de la web
* Aplicar control de versiones usando Git
* Manejar ramas y resolución de conflictos

---

## Tecnologías utilizadas

* HTML5
* CSS (archivo externo `styles.css`)
* Git
* GitHub

---

## Estructura del proyecto

```
/
 ├── index.html
 └── styles.css
```

---

## Contenido de la página

La página incluye:

* Un título principal sobre fundamentos de la web
* Un párrafo introductorio
* Una lista de temas importantes:

  * Evolución de la Web
  * Arquitectura Cliente-Servidor
  * Protocolos HTTP y HTTPS
  * Git y GitHub

---

## Nota sobre control de versiones

En el archivo `index.html` se evidencia un conflicto de fusión (merge conflict) generado por Git:

```
<<<<<<< HEAD
<h1>Fundamentos de la Web | Web Development Fundamentals</h1>
=======
<h1>Web Development Fundamentals - Edición B</h1>
>>>>>>> rama-titulo-b
```

Esto ocurre cuando dos ramas modifican la misma línea de código.
Para solucionarlo, se debe elegir una versión o combinar ambas y eliminar las marcas (`<<<<<<<`, `=======`, `>>>>>>>`).

---

## Cómo visualizar el proyecto

1. Clonar el repositorio:

```
git clone https://github.com/kjaimesst/jaimes-post1-u2.git
```

2. Abrir el archivo `index.html` en cualquier navegador web.

---

## Características

* Página web estática
* Uso de HTML básico
* Introducción al uso de CSS
* Manejo de Git y ramas
* Ejemplo de conflicto de versiones

---

## Autor

Proyecto desarrollado por **Oriana Jaimes**
Estudiante de Ingeniería de Sistemas


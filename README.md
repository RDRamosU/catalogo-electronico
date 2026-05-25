# TechStore — Catálogo de Electrónicos

Catálogo web de productos electrónicos construido con HTML y CSS puro. Desarrollado para practicar y demostrar el uso de Flexbox para crear layouts responsivos sin depender de frameworks externos.

---

## ¿Qué es?

TechStore es una página web estática que simula el catálogo de una tienda de electrónicos en línea. Muestra tarjetas de productos organizadas con Flexbox e incluye un sistema de filtros por categoría implementado con JavaScript vanilla.

---

## ¿Cómo funciona?

```
Usuario abre la página
        ↓
Se muestran todas las tarjetas de productos organizadas con Flexbox
        ↓
Usuario selecciona una categoría en los filtros
        ↓
JavaScript oculta las tarjetas que no corresponden a la categoría
        ↓
El layout se reorganiza automáticamente gracias a Flexbox
```

---

## Estructura del proyecto

```
catalogo-electronico/
├── index.html       # Estructura y contenido de la página
├── style.css        # Estilos y layout con Flexbox
└── README.md
```

---

## Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura semántica de la página |
| CSS3 / Flexbox | Layout responsivo y diseño de tarjetas |
| JavaScript | Filtros de productos por categoría |
| Google Fonts | Tipografía Inter |

---

## Conceptos de Flexbox practicados

- `display: flex` para el grid de productos
- `flex-wrap: wrap` para que las tarjetas se ajusten al ancho disponible
- `flex: 1 1 calc(25% - 1.5rem)` para controlar el tamaño de cada tarjeta
- `flex-direction: column` dentro de cada tarjeta para organizar su contenido verticalmente
- `justify-content` y `align-items` para alinear elementos dentro de las tarjetas

---

## Categorías disponibles

- Laptops
- Smartphones
- Audio
- Accesorios

---

## Instalación

No requiere instalación ni dependencias. Simplemente se clona el repositorio y abre el archivo `index.html` en tu navegador:

```bash
git clone https://github.com/RDRamosU/catalogo-electronico.git
cd catalogo-electronico
```

Abre `index.html` en el navegador (favorito).

---

## Autor

Ruben Dario — [rubendario.dev](https://rubendario.dev)

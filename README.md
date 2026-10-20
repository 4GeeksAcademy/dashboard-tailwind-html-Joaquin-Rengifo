# Auralcance — Influencer Analytics Dashboard

## Descripción

**Auralcance** es un dashboard responsivo diseñado para ayudar a creadores de contenido e influencers a visualizar el rendimiento de sus campañas, ventas y comisiones a través de distintas plataformas digitales.

Desarrollado como proyecto académico del programa **AI Engineering de 4Geeks Academy**, aplicando HTML5 y Tailwind CSS v4.

## Objetivo

Centralizar visualmente los principales indicadores de negocio para facilitar la interpretación de resultados y la identificación de oportunidades de mejora.

El proyecto utiliza datos ficticios de demostración y no realiza consultas a APIs externas.

## Tecnologías utilizadas

- HTML5 semántico.
- Tailwind CSS v4 mediante CDN.
- Flexbox y CSS Grid.
- Diseño responsive con enfoque mobile-first.

No se utilizan React, Vue ni JavaScript personalizado para la lógica del dashboard.

## Estructura del dashboard

### 1. Indicadores principales (KPI)

- Comisiones totales: 1.170 €.
- Ventas generadas: 100.
- Tasa de conversión sobre alcance agregado: 0,20 %.

### 2. Factores de rendimiento (Drivers)

- Comparación de comisiones entre Instagram, TikTok y YouTube.
- Rendimiento de los tres productos promocionados.
- Embudo de conversión: alcance, clics y ventas.

### 3. Detalles operacionales

- Tabla de ventas y comisiones por producto.
- Tarjetas adaptadas a dispositivos móviles.
- Alertas y oportunidades de mejora basadas en los datos simulados.

## Modelo de negocio

La influencer promociona tres productos y recibe una comisión del 15 % por venta.

| Producto | Precio | Ventas | Comisiones |
|---|---:|---:|---:|
| Producto A | 50 € | 40 | 300 € |
| Producto B | 120 € | 25 | 450 € |
| Producto C | 80 € | 35 | 420 € |
| **Total** | | **100** | **1.170 €** |

## Diseño responsive

La interfaz utiliza utilidades responsivas de Tailwind CSS v4:

- `sm:` — desde 640 px.
- `md:` — desde 768 px.
- `lg:` — desde 1024 px.
- `xl:` — desde 1280 px.

En móviles se utiliza navegación superior, componentes apilados y tarjetas operacionales.

En pantallas grandes se muestra una barra lateral y una tabla de productos.

## Accesibilidad y semántica

- Uso de etiquetas `header`, `nav`, `main`, `section` y `article`.
- Tabla semántica con encabezados y totales.
- Información textual que acompaña los indicadores visuales.
- Uso de atributos ARIA donde corresponde.

## Validación

El documento HTML fue comprobado mediante W3C Nu HTML Checker.

**Resultado:** sin errores ni advertencias.

Se realizaron revisiones visuales del diseño en escritorio, tablet y móvil.

## Ejecución

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto.
3. Ejecutar un servidor local:

`python3 -m http.server 3000`

4. Abrir `http://localhost:3000` en el navegador.

Se necesita conexión a internet para cargar Tailwind CSS v4 desde el CDN.

## Consideraciones

Este dashboard es un prototipo académico estático. Las estadísticas son simuladas y no se actualizan automáticamente.

## Autor

**Joaquín Rengifo**

AI Engineering — 4Geeks Academy.
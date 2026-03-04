# Frontend Mentor - Recipe Page Solution

Esta es mi solución al [desafío de Recipe Page en Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor ayuda a mejorar habilidades de codificación construyendo proyectos realistas.

## Tabla de contenidos

- [Resumen](#resumen)
  - [El desafío](#el-desafío)
  - [Captura de pantalla](#captura-de-pantalla)
- [Mi proceso](#mi-proceso)
  - [Construido con](#construido-con)
  - [Lo que aprendí](#lo-que-aprendí)
- [Autor](#autor)

## Resumen

### El desafío

El objetivo era construir una página de receta que se vea lo más parecida posible al diseño proporcionado, usando HTML y CSS.

### Captura de pantalla

![](./design/desktop-design.jpg)

## Mi proceso

### Construido con

- HTML5 semántico
- CSS personalizado
- Flexbox para el layout
- Diseño responsive
- Fuentes de Google Fonts:
  - Young Serif (para títulos)
  - Outfit (para el cuerpo del texto)

### Lo que aprendí

Este proyecto me ayudó a practicar:

1. **Estructura HTML semántica**: Usar elementos como `<section>`, `<main>`, y listas apropiadas para organizar el contenido.

2. **Estilizado de listas personalizadas**: Crear numeración personalizada para las instrucciones con `::before` y counter.

3. **Diseño de tablas**: Formatear la tabla de nutrición con bordes y espaciado apropiado.

4. **Paleta de colores**: Trabajar con una guía de estilo específica y aplicar colores consistentes en todo el proyecto.

5. **Tipografía**: Combinar diferentes familias de fuentes para títulos y texto del cuerpo.

### Fragmentos de código destacados

Estilizado personalizado de listas numeradas:

```css
.instructions li::before {
  content: counter(item) ".";
  counter-increment: item;
  position: absolute;
  left: 0;
  font-weight: 700;
  color: hsl(14, 45%, 36%);
}
```

Sección de tiempo de preparación con fondo especial:

```css
.prep-time {
  background-color: hsl(330, 100%, 98%);
  padding: 20px;
  border-radius: 12px;
  margin: 30px 0;
}
```

## Autor

- GitHub - [Diego](https://github.com/DiegoRuiz8)


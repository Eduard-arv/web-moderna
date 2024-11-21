# Web Moderna

## Autor

- **Nombre completo:** Eduard rivas
- **Curso:** CODE-201
- **email:** eduard62691@gmail.com
- **Fecha de creación:** 19/11/2024

---
## Sobre el Proyecto

En “La Web Moderna” podrás leer los conceptos clave que todo Desarrollador de Software debe saber para crear aplicaciones web.

---
## eslintrc

Este código es un archivo de configuración para ESLint, una herramienta de linting de JavaScript. Acá la explicación de cada línea de código:

1. `env`:

- `browser`: **true:** Indica que el código se ejecutará en un navegador web. Esto permite a ESLint aplicar reglas específicas para el entorno del navegador.

- `es2021`: **true:** Habilita el soporte para las características de JavaScript. 

- `es2021`: **true:** Habilita el soporte para las características de JavaScript ES2021, como las expresiones dinámicas de importación y las promesas asíncronas.

2. `extends`:

- `eslint:recommended`: Extiende la configuración de ESLint con las reglas recomendadas por el equipo de ESLint. Estas reglas cubren una amplia gama de buenas prácticas de codificación.

3. `parserOptions`:

`ecmaVersion`: **"latest"`**: Especifica que el analizador de código debe utilizar la última versión de ECMAScript para analizar el código.

`sourceType`: **"module"`**: Indica que el código fuente está escrito en formato de módulos ES6, lo que permite la importación y exportación de módulos.

4. `rules`:

- `indent`**: ["error", 2]`**: Establece que la indentación del código debe ser de 2 espacios y que se trata de una regla obligatoria.

- `linebreak-style: **["error", "unix"]`**: Especifica que el estilo de salto de línea debe ser Unix (LF) y que es una regla obligatoria.

- `quotes`: **["error", "single"]`**: Establece que se deben usar comillas simples para las cadenas de texto y que es una regla obligatoria.

- `semi`: **["error", "always"]`**: Especifica que se debe usar punto y coma al final de cada instrucción y que es una regla obligatoria.

- `no-unused-vars`: **"warn"`**: Advierte sobre variables declaradas pero no utilizadas.

- `no-console`: **"warn"`**: Advierte sobre el uso de la consola para depuración, ya que esto puede afectar el rendimiento en producción.

## Despliegue

- [Repositorio Web-moderna en GitHub:](eduard-arv.github.io/web-moderna/) 
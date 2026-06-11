# Desarrollo de una API REST para gestión de productos

La empresa necesita una API REST que gestione productos con nombre, precio, stock y categoría. Los productos no pueden tener precios negativos ni nombres duplicados. La API debe registrar cada producto y manejar los errores de validación adecuadamente. El dominio es una tienda online que requiere alta disponibilidad y consistencia en la gestión de productos.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Java Spring Boot REST API |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 8 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: JDK 17+, Maven 3.9+, IDE con soporte Java.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `mvn compile` en la raíz. Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Registro básico de productos

**Objetivo:** Implementar la funcionalidad mínima para registrar productos con validación de precio y nombre.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Diseñar y registrar productos con nombre, precio, stock y categoría.
- Validar que el precio no sea negativo y que el nombre no esté duplicado.
- Manejar adecuadamente los errores de validación.

**Entregable:** API REST que registra productos con validación básica.

<details>
<summary>Pistas de conocimiento</summary>

- Considera cómo estructurar la información de los productos.
- Piensa en cómo manejar los errores de validación de forma amigable para el usuario.

</details>

### Fase 2: Gestión de stock y categoría

**Objetivo:** Extender la API para gestionar el stock y la categoría de los productos.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Añadir la gestión del stock y la categoría a la API.
- Asegurar que los productos se registren con la información completa.

**Entregable:** API REST que registra productos con nombre, precio, stock y categoría.

<details>
<summary>Pistas de conocimiento</summary>

- Piensa en cómo estructurar la información adicional.
- Considera cómo validar la información del stock y la categoría.

</details>

### Fase 3: Documentación con Swagger

**Objetivo:** Documentar la API utilizando Swagger para facilitar su uso y entendimiento.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Documentar la API utilizando Swagger.
- Asegurar que la documentación sea clara y completa.

**Entregable:** API REST documentada con Swagger.

<details>
<summary>Pistas de conocimiento</summary>

- Considera cómo hacer que la documentación sea amigable para el usuario.
- Piensa en cómo describir las operaciones y los parámetros de la API.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un producto en el contexto de esta API y cuáles son sus atributos?
- **paraQueSirve**: ¿Para qué sirve validar el precio y el nombre de un producto?
- **comoSeUsa**: ¿Cómo se usa la API para registrar un producto?
- **erroresComunes**: ¿Cuáles son los errores comunes al registrar un producto y cómo se manejan?
- **queDecisionesImplica**: ¿Qué decisiones implica la gestión del stock y la categoría de un producto?

## Criterios de Evaluacion

- Implementación de la funcionalidad mínima para registrar productos con validación de precio y nombre.
- Extensión de la API para gestionar el stock y la categoría de los productos.
- Documentación clara y completa de la API utilizando Swagger.

---

*Reto generado automaticamente por Challenge Generator - Pragma*

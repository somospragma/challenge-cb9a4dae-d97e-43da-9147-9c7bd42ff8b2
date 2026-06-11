# Implementación de una API REST con persistencia en H2 y documentación con Swagger

La empresa necesita una API REST que gestione productos en un catálogo. Los productos tienen un nombre, precio y descripción. La API debe soportar la creación, lectura, actualización y eliminación de productos. La persistencia se realizará en una base de datos H2 y la documentación se generará con Swagger. Los productos no pueden tener nombres duplicados y los precios no pueden ser negativos. La API debe manejar adecuadamente los errores y proporcionar una respuesta coherente al cliente.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Java Spring Boot REST API |
| **Nivel** | junior-l1 |
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

### Fase 1: Definición del modelo de datos

**Objetivo:** Definir el modelo de datos para los productos, asegurando que los nombres no sean duplicados y los precios no sean negativos.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Identificar los atributos necesarios para un producto.
- Establecer las restricciones para los nombres y precios de los productos.

**Entregable:** Modelo de datos para productos con restricciones de nombres y precios.

<details>
<summary>Pistas de conocimiento</summary>

- Considera cómo representar los productos en la base de datos.
- Piensa en cómo validar los nombres y precios de los productos.

</details>

### Fase 2: Implementación de endpoints REST

**Objetivo:** Implementar los endpoints REST para crear, leer, actualizar y eliminar productos.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Crear los endpoints REST necesarios para gestionar los productos.
- Asegurar que los endpoints manejen adecuadamente los errores y proporcionen respuestas coherentes al cliente.

**Entregable:** Endpoints REST funcionales para la gestión de productos.

<details>
<summary>Pistas de conocimiento</summary>

- Considera cómo estructurar los endpoints para que sean intuitivos y fáciles de usar.
- Piensa en cómo manejar los errores y proporcionar respuestas útiles al cliente.

</details>

### Fase 3: Integración con H2 y documentación con Swagger

**Objetivo:** Integrar la API con una base de datos H2 y documentar los endpoints con Swagger.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Configurar la integración con una base de datos H2.
- Generar la documentación de los endpoints con Swagger.

**Entregable:** API REST integrada con H2 y documentada con Swagger.

<details>
<summary>Pistas de conocimiento</summary>

- Considera cómo configurar la conexión con la base de datos H2.
- Piensa en cómo generar una documentación clara y útil con Swagger.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un modelo de datos y por qué es importante en una API REST?
- **paraQueSirve**: ¿Para qué sirven los endpoints REST en una API?
- **comoSeUsa**: ¿Cómo se integra una API REST con una base de datos y se documenta con Swagger?
- **erroresComunes**: ¿Cuáles son los errores comunes al implementar una API REST y cómo se pueden evitar?
- **queDecisionesImplica**: ¿Qué decisiones implica la integración de una API REST con una base de datos y la documentación con Swagger?

## Criterios de Evaluacion

- Definición del modelo de datos con restricciones de nombres y precios.
- Implementación de endpoints REST funcionales para la gestión de productos.
- Integración con una base de datos H2 y documentación con Swagger.

---

*Reto generado automaticamente por Challenge Generator - Pragma*

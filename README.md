# ChatAcad — Generador de Prompts

Herramienta interactiva para generar prompts académicos estructurados, diseñada para usarse dentro de un **iframe en ChatAcad**.

## 🛠️ Cómo funciona

El usuario selecciona **3 opciones + un tema libre opcional**:

1. **Verbo / Acción** — ¿qué quiere hacer? (Explicar / Resumir / Ejemplificar / Analizar)
2. **Área de conocimiento** — Matemáticas, Ciencias, Historia, Literatura, Programación, Filosofía
3. **Nivel educativo** — Primaria, Secundaria, Preparatoria, Universidad, General
4. **Tema específico** — texto libre; si está vacío, el prompt es genérico

El sistema combina las selecciones y genera un prompt listo para usar en ChatAcad.

## 🚀 Uso en iframe

```html
<iframe src="./prompt-generator.html" width="100%" height="700" frameborder="0"></iframe>
```

## ✨ Características

- Sin dependencias externas de lógica (solo fuentes CDN)
- Light/Dark mode automático
- Botón de copiar al portapapeles
- Diseño responsive desde 375px
- Sin uso de localStorage (seguro en iframes)

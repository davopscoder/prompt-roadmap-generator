# 📚 Guía de Uso – Prompt Templates para Roadmaps

Este repositorio contiene **plantillas de prompts** diseñadas para generar **roadmaps de aprendizaje** con doble salida:  
- **Markdown (`.md`)**: Guía visual y legible para estudiantes y equipos técnicos.  
- **Excel (`.xlsx`)**: Herramienta de seguimiento para managers y líderes de equipo.  

---

## 📂 Estructura del Repositorio

```
/
├── README.md                  # Este archivo con instrucciones de uso
├── prompt_templates/          # Carpeta que contiene las plantillas .md
│   ├── prompt_template_roadmap_md_xlsx.md
│   └── ... (otras plantillas futuras)
└── ejemplos/                  # Ejemplos de salidas generadas
    ├── roadmap_python_devops.md
    ├── roadmap_python_devops.xlsx
    └── ...
```

> **Sugerencia:** Guarda todas las plantillas en `prompt_templates/` y todos los ejemplos o salidas en `ejemplos/`.

---

## 🛠 Cómo Usar un Prompt Template

1. **Abrir la plantilla**
   - Ve a `prompt_templates/` y abre el archivo `.md` correspondiente.
   - Por ejemplo: `prompt_template_roadmap_md_xlsx.md`.

2. **Rellenar los campos**
   - Busca los campos entre corchetes `[]`.
   - Sustitúyelos con la información de tu roadmap:
     - Tecnología (ej. Python)
     - Enfoque (ej. DevOps, Data Science, etc.)
     - Número de semanas
     - Número de fases
     - Público objetivo
     - Nivel inicial y final
     - Mínimos por lista (`contenidos`, `practica`, `proyectos`)

3. **Ejecutar el prompt**
   - Copia todo el contenido de la plantilla **ya personalizada**.
   - Pégalo en tu herramienta de generación (ej. ChatGPT) e indica que deseas:
     - Salida 1: `README.md` formateado.
     - Salida 2: `.xlsx` con hojas, formato y validaciones según la especificación.

4. **Guardar resultados**
   - Coloca los archivos generados en la carpeta `ejemplos/`.

---

## 🎯 Buenas Prácticas

- Mantén **paridad exacta** entre el `.md` y el `.xlsx` (mismos textos y listas).
- Usa siempre la misma **tabla canónica** como fuente para ambos formatos.
- Actualiza la plantilla si cambian los requisitos de formato o estructura.
- Versiona las plantillas para mantener un historial claro.

---

## 📥 Ejecución Recomendada

Ejemplo de instrucción final:

> "Genera la tabla canónica y, a partir de ella, entrega: (1) `README.md` con el formato anterior y (2) Excel `.xlsx` con las tres hojas y el estilo indicado. Asegura paridad exacta de contenido entre ambos."

---

## 📌 Próximos Pasos

- Añadir más plantillas para otros tipos de documentación (guías, OKRs, planes de proyecto).
- Integrar scripts para convertir `.md` ↔ `.xlsx` automáticamente.

---

**Autor:** [Tu Nombre o Equipo]  
**Licencia:** MIT

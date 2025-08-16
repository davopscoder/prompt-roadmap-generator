# 📚 User Guide – Prompt Templates for Roadmaps

This repository contains prompt templates designed to generate learning roadmaps with dual output formats:  
- **Markdown (`.md`)**: A visual and easy-to-read guide for students and technical teams.  
- **Excel (`.xlsx`)**:  A tracking tool for managers and team leaders.  

---

## 📂 Repository Structure

```
/
├── README.md                  # This file with usage instructions
├── prompt_templates/          # Folder containing .md templates
│   ├── prompt_template_roadmap_md_xlsx.md
│   └── ... (other future templates)
└── examples/                  # Examples of generated outputs
    ├── roadmap_python_devops.md
    ├── roadmap_python_devops.xlsx
    └── ...
```




> **Tip:** Save all templates in `prompt_templates/` and all examples or outputs in `examples/`.

---

## 🛠 How to Use a Prompt Template

1. **Open the template**
   - Go to `prompt_templates/` and open the corresponding `.md` file.
   - For example: `prompt_template_roadmap.md`.

2. **Fill in the fields**
   - Look for fields enclosed in square brackets `[]`.
   - Replace them with your roadmap information:
     - Technology (e.g., Python)
     - Focus area (e.g., DevOps, Data Science, etc.)
     - Number of weeks
     - Number of phases
     - Target audience
     - Initial and final skill level
     - Minimum items per list (`content`, `practice`, `projects`)

3. **Run the prompt**
   - Copy the entire **customized** template content.  
   - Paste it into your generation tool (e.g., ChatGPT) and specify that you want:  
     - Output 1: Formatted `README.md`.
     - Output 2: `.xlsx` file with sheets, formatting, and validations as specified.

4. **Save the results**
   - Place the generated files into the `examples/` folder.

---

## 🎯 Best Practices

- Maintain **exact parity** between the `.md` and `.xlsx` (same text and lists).
- Always use the same **canonical table** as the source for both formats.
- Update the template if formatting or structure requirements change.
- Version your templates to keep a clear history.

---

## 📥 Suggested Final Execution

Example of final instruction:

> "Generate the canonical table and, based on it, provide: (1) a `README.md` file with the specified format and (2) an `.xlsx` file with three sheets and the indicated style. Ensure exact parity of content between both."

---

## 📌 Next Steps

- Add more templates for other types of documentation (guides, OKRs, project plans).
- Integrate scripts to convert `.md` ↔ `.xlsx` automatically.

---

**Author:** [Your Name or Team]  
**License:** MIT

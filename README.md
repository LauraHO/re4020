# RE4020 – Economía del Desarrollo

Materiales de seminario del curso de Maestría en Ciencias II.  
Cada seminario incluye código en **R**, **Stata** y **Python**.

## 🌐 Sitio del curso
👉 `https://TU-USUARIO.github.io/re4020`

## 📁 Estructura del repositorio

```
re4020/
├── _quarto.yml          # Configuración del sitio
├── index.qmd            # Página de inicio
├── seminarios/
│   ├── seminario_01.qmd # Datos WDI – R / Stata / Python
│   └── ...
└── docs/                # Sitio generado (no editar manualmente)
```

## 🚀 Cómo publicar cambios

```bash
quarto render       # Genera el HTML en /docs
git add .
git commit -m "actualiza seminario X"
git push
```

El sitio se actualiza automáticamente en GitHub Pages.

## 📦 Requisitos

- [Quarto](https://quarto.org) ≥ 1.4
- R con paquetes: `tidyverse`, `WDI`, `haven`, `janitor`, `scales`, `plotly`
- Python con: `pandas`, `matplotlib`, `wbgapi`, `statsmodels`
- Stata 14+ con: `wbopendata`

---

*Laura Herrera | IEEC – Tec de Monterrey*

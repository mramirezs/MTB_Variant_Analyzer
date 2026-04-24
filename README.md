# 🧬 MTB Variant Analyzer

**Análisis automatizado de variantes de resistencia en *Mycobacterium tuberculosis***

## 🎯 Descripción

Pipeline bioinformático modular para análisis de mutaciones de resistencia en proteínas MTB, con enfoque en pncA (NP_216559.1) y pknG (NP_214924.1).

## 🚀 Uso Rápido

```bash
# Análisis básico
python src/core/mtb_analyzer_core_v13_cli.py -r pncA -i data/test_sequences/samples.fasta

# Pipeline completo con HTML
python src/pipelines/mtb_pipeline_runner.py -r pncA -i data/test_sequences/samples.fasta
```

## 📁 Estructura

- **`src/`** - Código fuente principal
  - `core/` - Scripts análisis core
  - `pipelines/` - Automatización completa
  - `reports/` - Generación reportes HTML
- **`data/`** - Datos entrada y resultados
  - `test_sequences/` - Secuencias prueba
  - `references/` - Secuencias referencia
  - `results/` - Outputs análisis
- **`docs/`** - Documentación completa
- **`tools/`** - Utilidades y setup
- **`envs/`** - Ambientes virtuales

## 📖 Documentación

Ver `docs/guides/` para guías detalladas de uso.

## 🔬 Características

- ✅ CLI profesional con opciones completas
- ✅ Input flexible: archivos locales, códigos NCBI, mixto
- ✅ Análisis MDR/XDR automático
- ✅ Reportes HTML interactivos
- ✅ Pipeline modular y escalable

## 📞 Contacto

**DiverSeq Labs** - research@diverseq.org

# Data Directory

Este diretório contém os dados brutos do projeto radiogenômico:

- **TC (Tomografia Computadorizada)**: Imagens médicas em formato DICOM
- **RNA**: Dados de expressão gênica e sequenciamento de RNA
- **Meta**: Metadados e informações clínicas dos pacientes

## Estrutura Sugerida

```
data/
├── tc/          ← Imagens de TC
├── rna/         ← Dados de RNA-seq
└── meta/        ← Metadados clínicos
```

**Nota**: Dados brutos não devem ser commitados no repositório. Adicione os arquivos de dados ao `.gitignore`.

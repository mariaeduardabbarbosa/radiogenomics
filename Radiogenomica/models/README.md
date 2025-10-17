# Models Directory

Este diretório contém os modelos radiogenômicos treinados e suas configurações.

## Conteúdo

- Modelos treinados (arquivos .pkl, .h5, .pt)
- Configurações de modelos (YAML, JSON)
- Checkpoints de treinamento
- Metadados dos modelos (versões, parâmetros)

## Organização Sugerida

```
models/
├── trained/         ← Modelos finais treinados
├── checkpoints/     ← Checkpoints durante o treinamento
└── configs/         ← Arquivos de configuração
```

**Nota**: Modelos grandes podem ser armazenados usando Git LFS ou em armazenamento externo.

# Radiogenomica

Estrutura organizada para o projeto de radiogenômica - integração de TC + RNA + TME.

## Estrutura de Diretórios

```
Radiogenomica/
├── data/                  ← Dados brutos (TC, RNA, meta)
├── notebooks/             ← Jupyter notebooks e scripts Python
├── results/               ← Tabelas, plots, outputs
├── models/                ← Modelos radiogenômicos treinados
└── reports/               ← Figuras e PDFs de resultados
```

## Descrição dos Diretórios

### 📊 data/
Armazena os dados brutos do projeto:
- Imagens de tomografia computadorizada (TC)
- Dados de expressão gênica (RNA)
- Metadados clínicos e anotações

### 📓 notebooks/
Contém Jupyter notebooks e scripts Python para:
- Pré-processamento de dados
- Análise exploratória
- Desenvolvimento de modelos
- Avaliação de resultados

### 📈 results/
Armazena outputs das análises:
- Tabelas de resultados
- Gráficos e visualizações
- Métricas de desempenho

### 🤖 models/
Contém modelos radiogenômicos treinados:
- Modelos finais
- Checkpoints de treinamento
- Configurações de modelos

### 📄 reports/
Armazena documentação e figuras finais:
- Figuras para publicações
- Relatórios em PDF
- Apresentações

## Uso

Cada diretório contém seu próprio README.md com instruções específicas e sugestões de organização.

## Notas Importantes

- **Dados brutos**: Adicione arquivos de dados ao `.gitignore` para evitar commits acidentais
- **Modelos grandes**: Considere usar Git LFS ou armazenamento externo
- **Figuras**: Use formatos vetoriais (SVG, PDF) para publicações

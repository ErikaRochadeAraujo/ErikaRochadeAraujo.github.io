# github.io

# 🧠 Analisador de Ressonância Magnética com IA

Este projeto é uma aplicação web que utiliza inteligência artificial para analisar imagens de ressonância magnética em formato NIfTI (.nii/.nii.gz).

## 🚀 Funcionalidades


- **Upload de arquivos NIfTI**: Suporte para arquivos .nii e .nii.gz
- **Análise com IA**: Modelo de segmentação treinado para identificar diferentes regiões cerebrais
- **Processamento local**: Toda a análise é feita no navegador, garantindo privacidade
- **Interface moderna**: Design responsivo e intuitivo
- **Resultados detalhados**: Estatísticas de segmentação por classe

## 🛠️ Tecnologias Utilizadas

- **TensorFlow.js**: Para execução do modelo de IA no navegador
- **nifti-reader-js**: Para leitura de arquivos NIfTI
- **Pako**: Para descompressão de arquivos .nii.gz
- **HTML5/CSS3/JavaScript**: Interface web moderna

## 📁 Estrutura do Projeto

```
/
├── index.html          # Página principal da aplicação
├── modelo_web/         # Pasta contendo o modelo convertido
│   ├── model.json      # Arquitetura do modelo
│   └── group1-shard*.bin # Pesos do modelo (8 arquivos)
└── README.md           # Este arquivo
```

## 🔧 Como Usar

1. Acesse a página web
2. Aguarde o carregamento do modelo de IA
3. Clique em "Escolher Arquivo .nii"
4. Selecione um arquivo de ressonância magnética (.nii ou .nii.gz)
5. Aguarde o processamento e visualize os resultados

## 📊 Resultados da Análise

O modelo produz uma segmentação com 4 classes:
- **Background**: Fundo da imagem
- **Necrose**: Tecido necrótico
- **Edema**: Edema peritumoral
- **Tumor Realçado**: Tumor com realce

## ⚠️ Importante

Esta aplicação é destinada apenas para fins educacionais e de pesquisa. Os resultados não devem ser utilizados para diagnósticos médicos. Sempre consulte um profissional médico qualificado.

## 🌐 Deploy

Este projeto pode ser hospedado gratuitamente no GitHub Pages. Todos os arquivos necessários estão incluídos e a aplicação roda completamente no lado cliente.

## 📝 Licença

Este projeto é fornecido como está, para fins educacionais.



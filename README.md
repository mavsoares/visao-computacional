# Trabalho de Conclusão da Disciplina: Visão Computacional e Modelos Generativos

Para permitir a execução independente do modelo, foram disponibilizados os seguintes artefatos:

- **Arquivo de pesos treinados:** `best.pt`  
- **Script de inferência:** `teste_modelo_custom.ipynb`

O script permite carregar o modelo treinado e realizar a detecção de armas de fogo em novas imagens, gerando como saída as *bounding boxes* e as classes detectadas.

## Pré-requisitos

### Software necessário:
- Python 3.11.9
- Git
- VS Code (recomendado)
- Conta no GitHub

## Setup Inicial

### 1. Clone o repositório
```bash
git clone https://github.com/mavsoares/visao-computacional.git
cd visao-computacional
```

### 2. Crie o ambiente virtual (recomendado)

#### Linux/Mac
```bash
python3 -m venv venv
source venv/bin/activate
```

#### Windows
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

## Como Executar

A predição de armas em imagens pode ser realizada por meio do script no arquivo `teste_modelo_custom.ipynb`

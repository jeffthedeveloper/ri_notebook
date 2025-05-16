# README - Notebook de Recuperação de Informação

## 📚 Visão Geral
Este notebook é uma jornada prática pelos conceitos fundamentais de Recuperação de Informação (RI), desde o pré-processamento de texto até modelos avançados de ranking, com exemplos em Python e uma abordagem didática.

## 🏗️ Estrutura do Notebook

### 1. Introdução à RI
- Definição e importância
- Panorama histórico
- Aplicações modernas

### 2. Pré-processamento de Texto
- Tokenização
- Remoção de stopwords
- Stemming e lematização
  - Exemplo prático: "pedra" → "pedr" (stemming) vs "pedra" (lematização)

### 3. Indexação
- Índice invertido
- Implementação prática em Python

### 4. Modelos de Recuperação
- Modelo booleano
- Modelo vetorial (TF-IDF)
- BM25 (modelo probabilístico)

### 5. Processamento de Consultas
- Algoritmos DAAT e TAAT
- Consultas de frase e proximidade

### 6. Avaliação de Sistemas
- Métricas: Precisão, Revocação, P@k
- Exemplo simplificado:
  ```python
  # Documentos recuperados: [1, 3, 5, 2, 4]
  # Documentos relevantes: {1, 2, 6}
  # Precisão = 2/5 (40%), Revocação = 2/3 (67%), P@3 = 1/3 (33%)
  ```

### 7. Tópicos Avançados
- Expansão de consulta (Rocchio)
- PageRank simplificado
- Learning to Rank básico

## 🛠️ Como Usar
1. Clone o repositório
2. Execute o notebook célula por célula
3. Experimente modificar os parâmetros nos exemplos

## 📊 Exemplo Prático - Stemming vs Lematização
| Técnica                    | Exemplo "corredor" | Velocidade | Precisão |
| -------------------------- | ------------------ | ---------- | -------- |
| Stemming      → "corr"     | Rápido             | Baixa      |
| Lematização   → "corredor" | Lento              | Alta       |

## 🤔 Analogia Didática
Imagine a RI como uma biblioteca mágica onde:
- **Gnomos tokenizadores** quebram frases em palavras
- **Fadas das stopwords** removem palavras comuns
- **O mago stemmador** reduz palavras a suas raízes
- **Óculos da relevância** (TF-IDF/BM25) ajudam a encontrar os melhores livros

## 📦 Dependências
- Python 3.x
- NLTK
- NumPy
- scikit-learn (para exemplos de ML)

## ✨ Destaques
- Exemplos práticos com código executável
- Explicações em linguagem simples
- Comparações visuais entre técnicas
- Abordagem lúdica para conceitos complexos

## 📝 Licença
Este material está disponível para uso educacional sob licença MIT.

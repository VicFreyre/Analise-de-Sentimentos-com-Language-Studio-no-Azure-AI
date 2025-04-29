# 🧠 Language Studio - Anotações Técnicas

## ✅ Objetivo
Testar os recursos de análise de texto do Azure Language Studio, como detecção de sentimento, análise de entidade, extração de frases-chave e mais.

---

## 📌 Recursos Utilizados

- Detecção de Sentimento
- Análise de Entidades Nomeadas
- Extração de Frases-Chave
- Análise de Opinião
- Classificação de Texto

---

## 🧪 Teste 1: Análise de Sentimento

### Entrada:
> "Apesar dos atrasos, o atendimento foi excelente e a equipe muito simpática."

### Saída:
- **Sentimento Geral**: Positivo
- **Confiança**: 0.87

---

## 🧪 Teste 2: Entidades Nomeadas

### Entrada:
> "A OpenAI foi fundada em San Francisco e desenvolve modelos como o ChatGPT."

### Saída:
- Organização: OpenAI
- Localização: San Francisco
- Produto: ChatGPT

---

## 🧪 Teste 3: Frases-Chave

### Entrada:
> "O Azure oferece serviços em nuvem como análise de linguagem e reconhecimento de voz."

### Saída:
- Serviços em nuvem
- Análise de linguagem
- Reconhecimento de voz

---

## 🧠 Modelo Personalizado (opcional)

### Processo:
1. Criar conjunto de dados rotulado (.tsv).
2. Treinar modelo personalizado para classificação ou extração de entidade.
3. Avaliar a performance com métricas: precisão, recall, F1.

---

## 📊 Métricas e Avaliação

- Sentiment Analysis: boas taxas de acerto em português.
- Entidades Nomeadas: resultados aceitáveis, mas limitados para domínios muito técnicos sem treino.
- Frases-chave: útil para sumarização automática de documentos.

---

## 📝 Conclusão

O Language Studio fornece recursos poderosos para pré-processamento de linguagem natural e pode ser facilmente integrado com APIs. A personalização eleva a eficácia em contextos especializados.


# 🗣️ Speech Studio - Anotações Técnicas

## ✅ Objetivo
Explorar os recursos do Azure Speech Studio para conversão de fala em texto (STT), leitura em voz (TTS) e personalização de modelos de fala.

---

## 📌 Recursos Utilizados

- Speech-to-Text (Reconhecimento de Fala)
- Text-to-Speech (Leitura em Voz)
- Custom Speech (Personalização com dados específicos)

---

## 🔧 Configuração Inicial

1. Criar um recurso de **Speech** no portal Azure.
2. Anotar a **chave de API** e a **região** para uso nas ferramentas.
3. Acessar o [Speech Studio](https://speech.microsoft.com/).

---

## 🧪 Teste 1: Speech-to-Text

### Descrição:
Gravação de fala via microfone e transcrição automática.

### Parâmetros:
- Idioma: `pt-BR`
- Reconhecimento Contínuo: Ativado

### Resultados:
- Transcrição precisa para voz clara e pausada.
- Dificuldades com sotaques regionais sem customização.

---

## 🧪 Teste 2: Text-to-Speech

### Descrição:
Transformar texto escrito em áudio utilizando vozes neurais da Microsoft.

### Vozes Testadas:
- `pt-BR-AntonioNeural`
- `pt-BR-FranciscaNeural`

### Formato de Saída:
- `.mp3` e `.wav`

### Observações:
- As vozes neurais têm entonação natural.
- A pronúncia de nomes estrangeiros pode exigir ajuste no texto (ex: "ChatGPT" → "Chat-G-P-T").

---

## 🛠️ Custom Speech (opcional)

### Etapas:
1. Upload de dataset com arquivos `.wav` + transcrições `.txt`.
2. Treinamento do modelo com vocabulário específico.
3. Avaliação da performance com dados de teste.

---

## 📝 Conclusão

O Speech Studio permite aplicações robustas de transcrição e leitura de texto com grande acurácia. O diferencial está na personalização com **Custom Speech**, que melhora o desempenho em domínios específicos (ex: saúde, jurídico, técnico).

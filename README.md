# Processamento de Linguagem Natural (NLP) e LLMs

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Colab](https://img.shields.io/badge/Google%20Colab-Compatible-F9AB00.svg?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📖 Visão Geral

Aplicações de NLP moderna e modelos de linguagem baseados em Transformers: BERT (NSP e Masked LM), Sentence-BERT (SBERT), BERTScore, pipelines de Chatbots conversacionais e análise de sentimentos com LLMs.

Este repositório reúne projetos práticos desenvolvidos com foco em engenharia de dados e inteligência artificial, demonstrando desde fundamentos teóricos até implementações práticas com validação experimental e métricas salvas.

---

## 🌟 Destaques do Portfólio

### 🔹 [Análise de Sentimentos com Large Language Models (LLMs)](./01_analise_sentimento_llms.ipynb)
Classificação de polaridade e extração de sentimentos em textos utilizando LLMs e técnicas modernas de prompting e fine-tuning.

- **Stack:** `LLMs` `HuggingFace` `NLP` `Sentimento`
- **Notebook:** [`01_analise_sentimento_llms.ipynb`](./01_analise_sentimento_llms.ipynb)

### 🔹 [Sentence-BERT (SBERT) para Busca Semântica e Embeddings](./02_sentence_embeddings_sbert.ipynb)
Geração de representações vetoriais densas de sentenças para cálculo de similaridade por cosseno e agrupamento semântico.

- **Stack:** `Sentence-Transformers` `SBERT` `Embeddings`
- **Notebook:** [`02_sentence_embeddings_sbert.ipynb`](./02_sentence_embeddings_sbert.ipynb)

### 🔹 [BERT: Masked Language Modeling & Next Sentence Prediction](./03_bert_language_modeling.ipynb)
Exploração dos objetivos de pré-treino do BERT (preenchimento de máscaras e previsão da relação entre sentenças consecutivas).

- **Stack:** `BERT` `PyTorch` `Transformers` `Tokenização`
- **Notebook:** [`03_bert_language_modeling.ipynb`](./03_bert_language_modeling.ipynb)

### 🔹 [Avaliação Textual com BERTScore](./04_avaliacao_texto_bertscore.ipynb)
Uso da métrica baseada em embeddings contextuais BERTScore para avaliação de qualidade de textos gerados contra referências humanas.

- **Stack:** `BERTScore` `Métricas de NLP` `Transformers`
- **Notebook:** [`04_avaliacao_texto_bertscore.ipynb`](./04_avaliacao_texto_bertscore.ipynb)

### 🔹 [Pipeline Evolutivo de Chatbot Conversacional](./05_pipeline_chatbot_conversacional.ipynb)
Desenvolvimento e refatoração de assistente conversacional utilizando casamento de padrões, intenções, NLTK e spaCy.

- **Stack:** `NLTK` `spaCy` `Chatbot` `Expressões Regulares`
- **Notebook:** [`05_pipeline_chatbot_conversacional.ipynb`](./05_pipeline_chatbot_conversacional.ipynb)

---

## 📑 Catálogo de Projetos (33 notebooks)

| Notebook | Descrição & Objetivo | Tecnologias | Tamanho |
| :--- | :--- | :--- | :---: |
| [`01_analise_sentimento_llms.ipynb`](./01_analise_sentimento_llms.ipynb) | Classificação e análise de sentimento com Large Language Models | `Transformers, PyTorch` | 24.2 KB |
| [`01_analise_sentimento_llms.ipynb`](./01_analise_sentimento_llms.ipynb) | Classificação e análise de sentimento com Large Language Models | `Transformers, PyTorch` | 316.8 KB |
| [`02_sentence_embeddings_sbert.ipynb`](./02_sentence_embeddings_sbert.ipynb) | Sentence-BERT para embeddings densos e similaridade semântica | `Sentence-Transformers, PyTorch` | 329.7 KB |
| [`03_bert_masked_language_model_v1.ipynb`](./03_bert_masked_language_model_v1.ipynb) | Masked Language Modeling (MLM) com BERT contextual (v1) | `Transformers, PyTorch` | 115.8 KB |
| [`03_bert_masked_language_model_v1.ipynb`](./03_bert_masked_language_model_v1.ipynb) | Masked Language Modeling (MLM) com BERT contextual (v1) | `Transformers, PyTorch` | 7.6 KB |
| [`03_bert_masked_language_model_v2.ipynb`](./03_bert_masked_language_model_v2.ipynb) | Masked Language Modeling (MLM) com BERT contextual (v2) | `Transformers, PyTorch` | 99.0 KB |
| [`03_bert_next_sentence_prediction.ipynb`](./03_bert_next_sentence_prediction.ipynb) | Previsão de próxima sentença (NSP) com modelo BERT | `Transformers, PyTorch` | 119.1 KB |
| [`03_bert_next_sentence_prediction.ipynb`](./03_bert_next_sentence_prediction.ipynb) | Previsão de próxima sentença (NSP) com modelo BERT | `Transformers, PyTorch` | 88.9 KB |
| [`04_avaliacao_texto_bertscore.ipynb`](./04_avaliacao_texto_bertscore.ipynb) | Métrica BERTScore para avaliação semântica de textos gerados | `BERTScore, Transformers` | 36.4 KB |
| [`04_avaliacao_texto_bertscore.ipynb`](./04_avaliacao_texto_bertscore.ipynb) | Métrica BERTScore para avaliação semântica de textos gerados | `BERTScore, Transformers` | 282.9 KB |
| [`05_pipeline_chatbot_chatbot.ipynb`](./05_pipeline_chatbot_chatbot.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbot) | `NLTK, spaCy, Scikit-Learn` | 25.9 KB |
| [`05_pipeline_chatbot_chatbot_nltk.ipynb`](./05_pipeline_chatbot_chatbot_nltk.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbot_nltk) | `NLTK, spaCy, Scikit-Learn` | 27.0 KB |
| [`05_pipeline_chatbot_chatbot_novo.ipynb`](./05_pipeline_chatbot_chatbot_novo.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbot_novo) | `NLTK, spaCy, Scikit-Learn` | 77.0 KB |
| [`05_pipeline_chatbot_chatbot_novo.ipynb`](./05_pipeline_chatbot_chatbot_novo.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbot_novo) | `NLTK, spaCy, Scikit-Learn` | 38.2 KB |
| [`05_pipeline_chatbot_chatbotv3.ipynb`](./05_pipeline_chatbot_chatbotv3.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbotv3) | `NLTK, spaCy, Scikit-Learn` | 48.4 KB |
| [`05_pipeline_chatbot_chatbotv4.ipynb`](./05_pipeline_chatbot_chatbotv4.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbotv4) | `NLTK, spaCy, Scikit-Learn` | 46.1 KB |
| [`05_pipeline_chatbot_chatbotv5.ipynb`](./05_pipeline_chatbot_chatbotv5.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbotv5) | `NLTK, spaCy, Scikit-Learn` | 69.3 KB |
| [`05_pipeline_chatbot_chatbotv5.ipynb`](./05_pipeline_chatbot_chatbotv5.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbotv5) | `NLTK, spaCy, Scikit-Learn` | 0.9 KB |
| [`05_pipeline_chatbot_chatbotv6.ipynb`](./05_pipeline_chatbot_chatbotv6.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbotv6) | `NLTK, spaCy, Scikit-Learn` | 66.5 KB |
| [`05_pipeline_chatbot_chatbotv7.ipynb`](./05_pipeline_chatbot_chatbotv7.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbotv7) | `NLTK, spaCy, Scikit-Learn` | 79.4 KB |
| [`05_pipeline_chatbot_chatbotv7.ipynb`](./05_pipeline_chatbot_chatbotv7.ipynb) | Pipeline conversacional de Chatbot com NLP (chatbotv7) | `NLTK, spaCy, Scikit-Learn` | 76.9 KB |
| [`06_processamento_avancado_spacy.ipynb`](./06_processamento_avancado_spacy.ipynb) | Processamento de texto, POS-tagging e parsing com spaCy | `spaCy, Pandas` | 265.8 KB |
| [`07_modelagem_topicos_lda.ipynb`](./07_modelagem_topicos_lda.ipynb) | Modelagem de tópicos probabilística com Latent Dirichlet Allocation (LDA) | `NLTK, Pandas` | 184.6 KB |
| [`08_sumarizacao_textual_extrativa.ipynb`](./08_sumarizacao_textual_extrativa.ipynb) | Sumarização extrativa de texto baseada em frequência de termos | `NLTK` | 19.6 KB |
| [`09_similaridade_tfidf_18q-I.ipynb`](./09_similaridade_tfidf_18q-I.ipynb) | Cálculo de similaridade semântica e representação vetorial TF-IDF | `Scikit-Learn` | 4.2 KB |
| [`09_similaridade_tfidf_1KMBO.ipynb`](./09_similaridade_tfidf_1KMBO.ipynb) | Cálculo de similaridade semântica e representação vetorial TF-IDF | `Scikit-Learn` | 5.7 KB |
| [`10_modelos_linguagem_ngrams.ipynb`](./10_modelos_linguagem_ngrams.ipynb) | Modelos de linguagem probabilísticos baseados em N-Grams | `NLTK` | 2.9 KB |
| [`11_projeto_integrador_nlp_final.ipynb`](./11_projeto_integrador_nlp_final.ipynb) | Projeto Integrador de Processamento de Linguagem Natural (final) | `Transformers, PyTorch` | 46.9 KB |
| [`11_projeto_integrador_nlp_rev_16yF4.ipynb`](./11_projeto_integrador_nlp_rev_16yF4.ipynb) | Projeto Integrador de Processamento de Linguagem Natural (rev_16yF4) | `Transformers, PyTorch` | 48.6 KB |
| [`11_projeto_integrador_nlp_rev_17-sd.ipynb`](./11_projeto_integrador_nlp_rev_17-sd.ipynb) | Projeto Integrador de Processamento de Linguagem Natural (rev_17-sd) | `Transformers, PyTorch` | 91.1 KB |
| [`11_projeto_integrador_nlp_rev_1Pkfy.ipynb`](./11_projeto_integrador_nlp_rev_1Pkfy.ipynb) | Projeto Integrador de Processamento de Linguagem Natural (rev_1Pkfy) | `Transformers, PyTorch` | 788.4 KB |
| [`12_transformers_huggingface_1V0Bp.ipynb`](./12_transformers_huggingface_1V0Bp.ipynb) | Fine-tuning e inferência com Transformers HuggingFace | `Transformers, PyTorch` | 112.4 KB |
| [`12_transformers_huggingface_1pI0Z.ipynb`](./12_transformers_huggingface_1pI0Z.ipynb) | Fine-tuning e inferência com Transformers HuggingFace | `Transformers, PyTorch` | 86.8 KB |

---

## 🚀 Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/VictorSilvaCamargo/nlp-llms-portfolio.git
   cd nlp-llms-portfolio
   ```
2. **Crie e ative um ambiente virtual:**
   ```bash
   python -m venv venv
   # Windows:
   .\venv\Scripts\activate
   # Linux/macOS:
   source venv/bin/activate
   ```
3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Inicie o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

---

## 👨‍💻 Autor

**Victor Silva Camargo**  

Cientista da Computação | Desenvolvedor FullStack | Engenheiro de Machine Learning  

GitHub: [@VictorSilvaCamargo](https://github.com/VictorSilvaCamargo)


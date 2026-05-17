# Trabalho Prático: PLN e Visão Computacional

Repositório dedicado à entrega da atividade prática de Processamento de Linguagem Natural e Visão Computacional, desenvolvida em Python no Google Colab.

---

## 🛠️ Exemplo 1: PLN (NER e Sentimentos)
* **Técnicas:** Reconhecimento de Entidades Nomeadas (NER) e Análise de Sentimentos.
* **Bibliotecas:** `spaCy` (modelo `pt_core_news_sm`) e `TextBlob`.
* **Resultado:** Identificação de organizações/locais e classificação da polaridade do texto.

### Evidência:
<img width="1218" height="262" alt="Captura de tela 2026-05-17 112352" src="https://github.com/user-attachments/assets/e04b9f1a-8be9-42fd-b737-1bae98cb01c6" />


---

## 📸 Exemplo 2: Visão Computacional (Otsu)
* **Técnica:** Segmentação por Limiarização (Método de Otsu).
* **Bibliotecas:** `OpenCV` e `scikit-image`.
* **Resultado:** Binarização automática de imagem em tons de cinza para preto e branco puro.

### Evidência:
<img width="815" height="390" alt="Captura de tela 2026-05-17 112526" src="https://github.com/user-attachments/assets/aee3a9c2-1d3b-4cd2-8a00-781dddc270fd" />

---

## 🚀 Como Rodar
```bash
pip install opencv-python numpy spacy textblob scikit-image
python -m spacy download pt_core_news_sm

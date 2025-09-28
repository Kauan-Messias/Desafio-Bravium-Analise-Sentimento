# Desafio de Estágio em IA - Análise de Sentimentos Olist

Este repositório contém a solução para o Desafio de Estágio em Inteligência Artificial da Bravium. O objetivo foi desenvolver um modelo de **classificação binária** capaz de identificar o sentimento das avaliações dos clientes da Olist (Positiva ou Negativa).

---

## Solução

O projeto completo, incluindo código, pré-processamento, treino e avaliação, está disponível no notebook abaixo.

| Plataformas | Link |
| :--- | :--- |
| **Notebook Completo (Google Colab)** | **[NOTEBOOK NO COLAB](https://colab.research.google.com/drive/19xa4bDiOyBAmDuHP-eQfQ9Tp91rfNbax?usp=sharing)** |
| **Repositório GitHub** | **[PÁGINA PRINCIPAL DESTE REPOSITÓRIO](https://github.com/Kauan-Messias/Desafio-Bravium-Analise-Sentimento)** |

---

## Metodo

O modelo foi construído com foco na **interpretação** e na Classificação.

* **Variável Alvo:** Reviews com `score` **4 ou 5** foram definidas como **Positivas**, e **1 ou 2** como **Negativas**. O `score` 3 (neutro) foi removido.
* **Pipeline:** Foi utilizado o **TF-IDF** para vetorização e **Regressão Logística** como algoritmo de classificação, escolhido por fornecer os **coeficientes (pesos)** para justificar a importância das palavras.

---

### Desempenho do Modelo

Conjunto de testes:

| Métrica | Valor |
| :--- | :--- |
| **Acurácia** | **91,76%** |
| **F1-Score (Negativo)** | **86%** |
| **F1-Score (Positivo)** | **94%** |

### Interpretabilidade

O modelo identificou as palavras que mais influenciam a classificação.

| Palavras Chave **POSITIVAS** | Palavras Chave **NEGATIVAS** |
| :--- | :--- |
| **excelente, ótimo, bom, super, rápido, adorei, recomendo...** | **pessima, pessimo, atraso, cancelar, reclamação, horrível, decepção...** |

---

### Contato

Obrigado pela oportunidade e pelo desafio. Estou à disposição para aprofundar as justificativas na próxima etapa.

* Kauan Messias
* [LinkedIn](https://www.linkedin.com/in/kauan-messias/)
* [GitHub](https://github.com/Kauan-Messias)

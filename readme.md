# Análise de Sentimentos com Azure AI Language Studio

Este projeto tem como objetivo analisar comentários de usuários utilizando o recurso de **Sentiment and Opinion Mining** do [Azure AI Language Studio](https://language.cognitive.azure.com/).

## 📌 Descrição

Foram utilizados diversos comentários reais ou simulados sobre produtos e serviços. O Azure AI foi empregado para classificar os comentários em três categorias de sentimento:

- **Positivo**
- **Negativo**
- **Neutro**

A análise é realizada com base nas frases inseridas em um arquivo de texto, e os resultados incluem pontuações de confiança e segmentação por sentença.

---

## 📂 Exemplos

### 📝 Entrada: Comentários

Input e evolução do Projeto:

![Comentários - Parte 1](./checkpoint%20(1).png)
![Comentários - Parte 2](./checkpoint%20(2).png)
![Comentários - Parte 3](./checkpoint%20(3).png)
![Comentários - Parte 4](./checkpoint%20(4).png)
![Comentários - Parte 5](./checkpoint%20(5).png)

---

### 🧠 Saída: Análise de Sentimentos

Através da interface do **Azure AI Language Studio**, os comentários foram processados, retornando uma análise detalhada do sentimento de cada frase, incluindo os níveis de confiança.

#### Exemplo de Saída:

```json
{
    "sentiment": "negative",
    "confidenceScores": {
        "positive": 0.01,
        "neutral": 0.13,
        "negative": 0.87
    },
    "text": "Tive que repetir meu problema várias vezes, uma perda de tempo."
}
```

---

## 🛠️ Tecnologias Utilizadas

- **Azure AI Language Studio**
- **Windows Bloco de Notas**
- **Captura de tela no Windows**

---

## ✅ Conclusão

A análise de sentimentos utilizando o Azure AI Language Studio demonstrou-se eficaz para classificar feedbacks textuais com precisão e confiabilidade. Essa abordagem pode ser extremamente útil para empresas que desejam compreender a opinião de seus clientes de maneira automatizada.

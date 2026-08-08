# 🕵️‍♂️ Miniguia de Estudos: O Universo de Sherlock Holmes com NotebookLM

Repositório desenvolvido como parte do desafio prático da **DIO**, aplicando Inteligência Artificial (NotebookLM) como ferramenta de aprendizagem ativa e curadoria de conhecimento.
> 🔗 **Acesso ao Notebook:** [Clique aqui para acessar o meu Caderno Temático no NotebookLM](https://notebook.google.com/notebook/b17da5d6-2642-4539-94c4-2763c95d5394)
---

## 🎯 Contexto e Objetivos
* **Tema Escolhido:** O método dedutivo, a investigação e os personagens das obras clássicas de Sherlock Holmes.
* **Objetivo:** Utilizar o NotebookLM para centralizar obras clássicas em domínio público, extrair padrões analíticos, gerar resumos estruturados e construir um miniguia de estudos de referência rápida.

---

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM, foram selecionadas 4 obras originais em domínio público disponíveis no *Project Gutenberg*:

1. [A Study in Scarlet (Um Estudo em Vermelho)](https://www.gutenberg.org/cache/epub/244/pg244-images.html)
2. [The Adventures of Sherlock Holmes (As Aventuras de Sherlock Holmes)](https://www.gutenberg.org/cache/epub/1661/pg1661-images.html)
3. [The Hound of the Baskervilles (O Cão dos Baskervilles)](https://www.gutenberg.org/cache/epub/2852/pg2852-images.html)
4. [The Memoirs of Sherlock Holmes (As Memórias de Sherlock Holmes)](https://www.gutenberg.org/cache/epub/834/pg834-images.html)

---

## ⚙️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

* **Contexto Inicial Fornecido à IA:** 
  > *"Estou construindo um caderno temático de estudos para o portfólio da DIO com foco nas obras originais de Sherlock Holmes."*
* **Estratégia de Prompt (Encadeamento):** Em vez de pedir um resumo geral, utilizei uma técnica de perguntas sequenciais e investigativas (*"Qual a história de origem?", "Quem foi a vítima?", "Quem era o cúmplice?"*) para forçar a IA a mergulhar profundamente nos detalhes do livro "Um Estudo em Vermelho".
* **Resultado (Cicatriz/Aprendizado):** Percebi que fazer perguntas diretas e sequenciais sobre eventos específicos da trama evita que a IA alucine ou traga informações de filmes, mantendo a resposta focada puramente nos textos dos livros.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados: O Cúmplice de Jefferson Hope
Durante a análise da obra, o NotebookLM estruturou o seguinte resumo sobre os bastidores da investigação em *Um Estudo em Vermelho*:

* **A Existência do Cúmplice:** Jefferson Hope tinha um amigo em Londres que o auxiliava, descrito por Holmes como tão astuto quanto o próprio assassino. Seu nome nunca foi revelado nas fontes, mas sua atuação foi crucial.
* **O Disfarce:** Para recuperar um anel de casamento usado como isca por Holmes em um anúncio, o cúmplice foi ao 221B disfarçado de uma velha senhora trôpega (alegando que o anel era de sua filha, Sally). O disfarce foi tão perfeito que enganou Holmes e Watson.
* **A Fuga e Habilidades:** Após pegar o anel falso, o cúmplice despistou Holmes saltando de uma carruagem em movimento. Holmes deduziu tratar-se de um jovem ativo e ator incomparável.
* **Lealdade:** Ao ser capturado, Hope reconheceu a astúcia do amigo, mas recusou-se a entregar seu nome, protegendo-o.

### 2. Glossário Técnico e de Personagens
* **221B Baker Street:** O endereço icônico e ponto central onde Holmes e Watson recebem clientes e armam armadilhas (como o anúncio do anel).
* **Método de Observação:** A capacidade de deduzir a verdade, mesmo quando falha (como no caso em que o cúmplice enganou Holmes com um disfarce impecável).
* **Jefferson Hope:** O antagonista central do primeiro romance de Holmes, impulsionado por vingança e auxiliado por comparsas habilidosos.

### 3. Prompts Reutilizáveis para Futuras Revisões
Com base nas interações documentadas, os seguintes prompts podem ser reutilizados para estudos futuros no caderno:
* *"Qual é a história de origem de Watson e como ocorreu seu primeiro encontro com Sherlock Holmes?"*
* *"Como Sherlock Holmes capturou o assassino Jefferson Hope?"*
* *"Quem foi a vítima do assassinato no 221B e quais as pistas deixadas no local?"*

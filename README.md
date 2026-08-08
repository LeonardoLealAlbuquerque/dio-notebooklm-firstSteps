# 🕵️‍♂️ Miniguia de Estudos: O Universo de Sherlock Holmes com NotebookLM

Repositório desenvolvido como parte do desafio prático da **DIO**, aplicando Inteligência Artificial (NotebookLM) como ferramenta de aprendizagem ativa e curadoria de conhecimento.

---

## 🎯 Contexto e Objetivos
* **Tema Escolhido:** O método dedutivo, a psicologia investigativa e a estrutura narrativa das obras clássicas de Sherlock Holmes criadas por Sir Arthur Conan Doyle.
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

* **Tentativa Inicial (Prompt Genérico):** 
  > *"Resuma os casos de Sherlock Holmes."*
  * **Dificuldade (Cicatriz):** A IA gerou respostas superficiais misturando livros originais com adaptações modernas de filmes e séries de TV, fugindo do escopo literário.
* **Ajuste e Solução (Prompt Estruturado):** 
  > *"Atue como um analista literário. Utilizando **estritamente** as fontes cadastradas do Project Gutenberg, explique apenas os métodos de observação e dedução lógica descritos nos textos originais de Conan Doyle."*
  * **Resultado:** O modelo passou a entregar análises precisas, fiéis aos textos originais e livres de interferências externas.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
* **O Método de Observação:** Baseia-se na atenção meticulosa a detalhes físicos minúsculos (como marcas de lama, cinza de charuto ou vestimentas) que passam despercebidos por observadores comuns e policiais tradicionais.
* **A Lógica Dedutiva:** Consiste em eliminar sistematicamente o impossível; o que restar, por mais improvável que pareça, deve ser a verdade.
* **A Parceria com Watson:** Atua como um contraste analítico e um mecanismo narrativo para registrar os casos sob a perspectiva de um observador impressionado, mas racional.

### 2. Glossário Técnico
* **Método Científico de Dedução:** Abordagem investigativa fundamentada em evidências empíricas e raciocínio lógico rigoroso.
* **O "Sótão do Cérebro":** Metáfora de Holmes para a curadoria consciente da mente, armazenando apenas conhecimentos úteis à investigação e descartando dados irrelevantes.
* **Baker Street 221B:** O endereço icônico e ponto central de partida para as investigações do detetive.

### 3. Prompts Reutilizáveis para Futuras Revisões
* *"Quais são os principais traços psicológicos que definem a personalidade de Sherlock Holmes nos contos originais?"*
* *"Liste as principais críticas que Sherlock Holmes faz aos métodos da Scotland Yard nas fontes carregadas."*

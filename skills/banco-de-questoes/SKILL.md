---
name: banco-de-questoes
description: Gera questões de avaliação a partir de um conteúdo — objetivas com 4 ou 5 alternativas, discursivas e estudos de caso — com gabarito comentado, nível de dificuldade e objetivo avaliado. Use para montar provas, quizzes e listas de revisão.
---

# Banco de questões

## Entrada
- Conteúdo de referência (texto, e-book, plano de ensino)
- Quantidade e tipos de questão desejados
- Objetivos de aprendizagem (se houver)

## Regras
1. **Toda questão nasce do conteúdo fornecido.** Nada de fato externo não verificado.
2. **Distratores plausíveis**: erros comuns de quem estudou pouco, nunca absurdos.
3. Evitar "todas as anteriores", "nenhuma das anteriores" e pegadinhas de leitura.
4. Equilíbrio: ~30% fácil, ~50% média, ~20% difícil.
5. Alternativa correta distribuída (não deixar sempre a mesma letra).

## Formato de cada questão
```
Q[n] · [objetiva|discursiva|caso] · nível [fácil|médio|difícil] · objetivo: [qual]
Enunciado
a) … b) … c) … d) … (e) …)
Gabarito: [letra]
Comentário: por que a correta está certa e por que cada distrator está errado.
```
Para discursivas: **resposta esperada** + **critérios de correção** em tópicos.

## Revisão final
Confira: alguma questão pode ter duas respostas certas? Algum enunciado entrega a resposta? Corrija antes de entregar.

## Como usar fora do Claude
Cole este arquivo e depois: *"Conteúdo: … Quero 10 objetivas e 2 discursivas."*

---
name: aula-para-ebook
description: Transforma a transcrição de uma aula gravada (Zoom, Meet, presencial) em um e-book didático organizado por unidades, com objetivos, conceitos-chave, exemplos, quadros-resumo e questões de revisão. Use quando o professor tiver a transcrição de uma aula e quiser um material de leitura para os alunos.
---

# Aula → E-book didático

## Quando usar
Você tem a transcrição de uma aula (texto bruto, com repetições, pausas e conversa paralela) e quer um material de leitura limpo para a turma.

## Entrada
- Transcrição da aula (texto)
- Nome da disciplina e do professor
- Público (ex.: pós-graduação em saúde, ensino médio)

## Regras
1. **Fidelidade:** use só o que foi dito na aula. Se completar com conhecimento geral, marque como *"Complemento"*. Nunca invente estudo, número ou citação.
2. **Sem relatos pessoais:** histórias íntimas de alunos ou do professor ficam fora. Fica a **lição**, não a confissão. O e-book é reutilizado por outras turmas.
3. **Sem dados de alunos:** nenhum nome, e-mail ou situação de aluno.
4. **Linguagem do público:** frases curtas, termos técnicos explicados na primeira vez.

## Passos
1. Leia a transcrição inteira e liste os **temas** na ordem em que aparecem.
2. Agrupe em **3 a 6 unidades**.
3. Para cada unidade escreva:
   - **Objetivos de aprendizagem** (2–3, com verbos da Taxonomia de Bloom: explicar, aplicar, comparar…)
   - **Texto principal** (reescrito, sem marcas de fala)
   - **Conceitos-chave** (glossário curto)
   - **Exemplo prático** tirado da aula
   - **Quadro-resumo** (5 linhas no máximo)
   - **3 questões de revisão** (1 de lembrar, 1 de aplicar, 1 de refletir)
4. Abra o e-book com **apresentação** (o que o aluno vai aprender) e feche com **síntese geral** + **referências citadas na aula**.
5. Revise: existe alguma frase que não veio da aula e não está marcada como complemento? Corrija.

## Saída
Markdown pronto para virar PDF, com sumário no topo.

## Como usar fora do Claude (ChatGPT, Gemini…)
Cole este arquivo inteiro como primeira mensagem e, em seguida: *"Aqui está a transcrição da aula de [disciplina] para [público]:"* + o texto.

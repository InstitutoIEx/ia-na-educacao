# IA na Educação — skills e prompts em português

Ferramentas abertas de inteligência artificial para **professores, coordenadores e instituições de ensino**, mantidas pelo **[Instituto IEX](https://institutoiex.com)**.

Cada pasta em `skills/` é uma **skill** pronta para o Claude (formato `SKILL.md`) **e** um prompt que funciona em qualquer assistente (ChatGPT, Gemini, Copilot…): é só copiar o arquivo e colar.

## O que tem aqui

| Skill | Para que serve |
|---|---|
| [aula-para-ebook](skills/aula-para-ebook/SKILL.md) | Transcrição de aula gravada → e-book didático por unidades |
| [plano-de-ensino](skills/plano-de-ensino/SKILL.md) | Ementa + carga horária → plano de ensino coerente (objetivos, cronograma, avaliação) |
| [trilha-de-estudo](skills/trilha-de-estudo/SKILL.md) | Material da unidade → trilha autoguiada com checkpoints |
| [banco-de-questoes](skills/banco-de-questoes/SKILL.md) | Conteúdo → questões com gabarito comentado e nível |
| [rubrica-de-avaliacao](skills/rubrica-de-avaliacao/SKILL.md) | Rubricas de correção + devolutiva ao aluno |
| [tutor-socratico](skills/tutor-socratico/SKILL.md) | Prompt de sistema para tutor de IA que ensina perguntando |
| [roteiro-video-resumo](skills/roteiro-video-resumo/SKILL.md) | Unidade → roteiro de vídeo de 60–120 s |
| [carrossel-mito-ciencia](skills/carrossel-mito-ciencia/SKILL.md) | Carrossel de divulgação científica com fontes reais |
| [comunicados-academicos](skills/comunicados-academicos/SKILL.md) | Convocações, avisos e lembretes em e-mail e WhatsApp |
| [projeto-final-guiado](skills/projeto-final-guiado/SKILL.md) | IA conduz o aluno no projeto final aplicado à profissão |

## Como usar

**No Claude (Claude Code ou app com skills):** copie a pasta da skill para `~/.claude/skills/` e peça normalmente ("transforme esta transcrição em e-book").

**Em qualquer outro assistente:** abra o `SKILL.md`, copie tudo, cole como primeira mensagem e envie seu material em seguida.

## Princípios
1. **Fidelidade à fonte**: as skills mandam a IA usar só o material fornecido e marcar o que for complemento.
2. **Privacidade**: nunca coloque dados pessoais de alunos (nome, nota, saúde, finanças) nos prompts.
3. **O professor decide**: a IA prepara rascunhos; a revisão e a palavra final são humanas.
4. **Sem atalhos na avaliação**: as skills de tutoria não entregam resposta de prova.

## Contribua
Usou, adaptou ou criou uma skill nova para a sua realidade? Veja o [guia de contribuição](CONTRIBUTING.md). Relatos de uso em sala também são muito bem-vindos nas *Issues*.

## Licença
- Código e estrutura: **MIT** ([LICENSE](LICENSE))
- Textos dos prompts e skills: **Creative Commons Atribuição 4.0 (CC BY 4.0)** ([LICENSE-CONTEUDO](LICENSE-CONTEUDO)) — use, adapte e compartilhe citando o Instituto IEX.

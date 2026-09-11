# insta-copy

Skill do Claude que escreve copy de carrossel de Instagram slide a slide, mais a legenda, sempre depois de um briefing curto e de uma pesquisa na web sobre assuntos em alta, ganchos que estão performando e referências do nicho.

O fluxo tem três fases, nesta ordem: briefing, pesquisa, escrita. A entrega é texto, no chat ou em arquivo. Para a arte final em PNG, use a skill de design de carrossel.

## Conteúdo

```
skills/insta-copy/
  SKILL.md
```

## Como instalar

Clone o repositório e copie a pasta da skill para o diretório de skills do Claude:

```bash
git clone https://github.com/Guilherme-C-Gomes/skill-insta-copy.git
cp -r skill-insta-copy/skills/insta-copy ~/.claude/skills/
```

Depois é só chamar `/insta-copy` numa sessão do Claude.

## Quando a skill dispara

Pedidos de copy para Instagram, carrossel, slides, roteiro de post, gancho, headline de capa, legenda, CTA e storytelling para post. Também dispara quando a pessoa só descreve o que quer ("faz um carrossel sobre X", "melhora essa legenda", "refaz o slide 3") e para revisar copy que ela colar no chat.

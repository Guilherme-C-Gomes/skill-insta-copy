---
name: insta-copy
description: "Escreve copy de carrossel de Instagram slide a slide mais a legenda, sempre depois de um briefing curto com o usuário e de uma pesquisa na web sobre assuntos em alta, ganchos que estão performando e referências do nicho. Use SEMPRE que aparecer copy para Instagram, carrossel, slides, roteiro de post, texto de post, gancho, headline de capa, legenda, caption, CTA, chamada, storytelling para post, ou pedido de conteúdo para Instagram. Use também quando a pessoa só descreve o que quer (\"faz um carrossel sobre X\", \"preciso de conteúdo pro insta\", \"me dá ideia de post\", \"transforma isso num carrossel\", \"quero um post que viralize\", \"o que eu posto essa semana\", \"melhora essa legenda\", \"refaz o slide 3\"), e para revisar ou reescrever copy de carrossel que ela colar no chat. Esta skill entrega texto, no chat ou em arquivo quando pedido. Se a pessoa quiser a arte final em PNG, faça a copy aqui e depois passe para a skill de design de carrossel."
---

# insta-copy

Copy de carrossel de Instagram com pesquisa de tendência antes da escrita.

O nicho muda a cada pedido. Nunca assuma o nicho, o público ou a oferta de conversas anteriores sem confirmar.

O fluxo tem três fases, nesta ordem: **briefing**, **pesquisa**, **escrita**. Pular a pesquisa é o erro mais comum e o mais caro, porque é ela que separa um carrossel genérico de um que conversa com o que o nicho está discutindo agora.

O defeito que mais reprova entrega não é falta de informação, é falta de fio condutor. Leia a seção **Fio condutor** antes de escrever o primeiro slide.

---

## Fase 1: Briefing

Antes de qualquer coisa, colete o que falta. Não repita perguntas cuja resposta já está clara no que a pessoa escreveu.

**Essencial, sempre confirme:**
1. Nicho e perfil (quem posta, o que vende)
2. Tema ou ângulo do carrossel, se já houver um
3. Objetivo do post: salvamento, compartilhamento, comentário, clique na bio, venda direta ou autoridade
4. Público: quem lê e em que estágio de consciência está

**Bom saber, pergunte só se for relevante:**
5. Oferta ou CTA final (link, DM, comentar palavra-chave, nada)
6. Tom de voz e exemplos de posts que a pessoa gosta
7. Número de slides, se houver preferência
8. O que não pode aparecer: promessas, números, termos proibidos, compliance
9. Se quer arquivo no fim, e em que formato

Use a ferramenta de pergunta de múltipla escolha do ambiente (`AskUserQuestion`, `ask_user_input_v0` ou equivalente) para as perguntas de escolha, com no máximo três por rodada. É mais rápido de responder no celular do que digitar. Perguntas abertas vão em texto normal.

Se a pessoa mandar tudo mastigado em um parágrafo só, não invente rodada de perguntas. Confirme o que entendeu em duas linhas e siga.

**Padrões quando ela não especificar:** 7 slides, objetivo de salvamento, tom direto e conversado, CTA no último slide.

---

## Fase 2: Pesquisa

Nunca escreva a copy direto do conhecimento interno. Pesquise, sempre, nestes eixos. Use de 6 a 10 buscas, mais se o nicho for técnico ou mudar rápido.

**Eixo 1, assuntos em alta no nicho.** O que está sendo discutido agora, mudanças recentes, polêmicas, dados novos, sazonalidade. Buscas: `[nicho] tendências [ano atual]`, `[nicho] notícias`, `[nicho] o que mudou`. Inclua o ano atual nas buscas, resultado velho envenena o ângulo.

**Eixo 2, ganchos e formatos que estão performando.** Estruturas de carrossel com tração, tipos de gancho, formatos de capa, tamanho ideal. Buscas: `carrossel instagram [nicho] engajamento`, `hooks instagram [nicho]`, `instagram carousel hooks that convert`. Busque em português e em inglês, o inglês costuma trazer o estudo de dados e o português traz o jeito de falar.

**Eixo 3, referências e concorrentes.** Quem é referência no nicho, que ângulos já estão saturados, que dor ninguém está cobrindo. Buscas: `melhores perfis instagram [nicho]`, `[nicho] influenciadores instagram`, `[concorrente citado] instagram`.

**Eixo 4, posts reais, quando der.** Ver o post de verdade vale mais que ler artigo sobre post. O instagram.com exige login: sem sessão ativa, perfil público mostra só nome, bio e contagem de seguidores, e nenhuma legenda ou texto de slide. Se houver navegador com sessão logada, abra 3 a 5 posts do nicho e extraia o padrão: quantos slides, o que a capa promete, como o slide 2 continua a capa, onde está o payoff, qual o pedido final. Se não houver, diga isso à pessoa em uma linha e siga pelos eixos 1 a 3, sem fingir que olhou.

**Ao usar o que achou:** parafraseie sempre. Nunca reproduza copy de concorrente literalmente, nem legenda, nem headline. Extraia o padrão, não o texto. Se citar um dado ou número, ele precisa vir de fonte real da pesquisa, com a fonte nomeada. Dado inventado é o pior defeito possível num post de autoridade.

### Gate antes de escrever

Entregue um resumo curto, no máximo 10 linhas, com:
- 3 a 4 achados da pesquisa que mudam a escrita, cada um em uma linha
- **3 ângulos candidatos**, cada um com o gancho de capa já escrito, para a pessoa sentir o tom

Pergunte qual ângulo seguir. Se ela responder "escolhe o melhor" ou algo assim, escolha e siga sem nova pergunta. Se ela já tiver dado o ângulo fechado no briefing, ainda assim mostre os achados, mas siga direto para a escrita.

---

## Fio condutor

Um carrossel é uma história contada em pedaços, não uma lista de fatos numerados. Sete afirmações verdadeiras e desconexas produzem exatamente a sensação de "está jogando informação", e a pessoa sai no slide 3.

**A regra:** cada slide começa de onde o anterior parou. Se der para trocar a ordem de dois slides sem prejuízo, não existe fio, existe lista.

Três ferramentas para amarrar:

1. **Um exemplo só, do começo ao fim.** Escolha um número, um caso ou um personagem no slide 1 e leve até o CTA. Números que se repetem costuram sozinhos: se a capa diz 300 leads e 6 clientes, os slides seguintes falam dos 294 e dos 6, nunca de um exemplo novo.
2. **Cadeia de causa e efeito.** A sequência que funciona quase sempre: cena → virada → causa → consequência → conserto → pedido. Cada slide responde à pergunta que o anterior deixou no ar.
3. **Costura verbal.** Comece slides com "desses 300", "então", "por isso", "quem sabe disso é". Palavra de ligação explícita obriga a leitura a continuar.

**Onde o fio quebra, e é sempre nos mesmos lugares:**
- Dado solto no meio. Uma estatística que chega sem ser pedida pelo slide anterior derruba o ritmo, por mais forte que seja. Se o número não nasce da história, mande para a legenda.
- Guinada técnica perto do fim. Detalhe de implementação num slide de história muda o registro e perde o leitor. Legenda.
- Slide que repete o anterior com outras palavras. Corte.

**Teste das headlines.** Leia só as headlines, na ordem, sem os apoios. Elas precisam formar um parágrafo que se entende sozinho. Se virar uma lista de tópicos sem conexão, reescreva antes de mostrar para a pessoa.

---

## O que faz um post converter

Conversão aqui não é curtida. O que distribui o post em 2026 é, nesta ordem: tempo de visualização, envios por alcance (compartilhamento no direct) e curtidas por alcance, confirmado por Adam Mosseri. Envio no direct vale de 3 a 5 vezes mais que curtida para alcançar quem não segue. Salvamento é o sinal mais forte de que o conteúdo tem valor de referência.

O que isso muda na escrita:

- **Escreva para ser mandado a uma pessoa específica.** O post de alta conversão é aquele que alguém encaminha para o sócio, o gestor ou o colega com "olha isso". Conteúdo que nomeia uma tensão que duas pessoas já discutiram é encaminhável. Conteúdo genérico não é.
- **O maior payoff fica no último slide, não no meio.** Completar o carrossel é o que sinaliza valor. Se a melhor informação está no slide 3, a pessoa sai antes do fim.
- **O slide 2 é o ponto de maior abandono.** A passagem da capa para o 2 é o atrito principal. O slide 2 nunca resume a capa: ele continua a frase que a capa começou, ou entrega o primeiro pedaço da resposta prometida.
- **Volte à capa no último slide.** Retomar a promessa da capa no CTA dá sensação de fechamento e puxa releitura.
- **Um pedido só.** Salvar, comentar ou clicar, nunca os três. Pedido duplo derruba os dois.

**Números de referência:** 7 a 10 slides é a faixa de melhor retenção; acima de 12 a taxa de conclusão cai cerca de 40%. Meta de conclusão acima de 55% e taxa de swipe acima de 65%. Taxa de salvamento acima de 3% indica conteúdo de referência. Carrossel gera cerca de 3,4 vezes mais salvamentos e 2,1 vezes mais compartilhamentos que imagem única.

Esses números orientam a decisão de formato. Não os coloque dentro da copy, a não ser que o post seja sobre Instagram.

---

## Fase 3: Escrita

### Arquitetura do carrossel

- **Slide 1, capa:** promessa ou tensão. É o slide que decide se o resto existe. Precisa parar o dedo sozinho e deixar uma pergunta aberta.
- **Slide 2, continuação:** entrega o primeiro pedaço do que a capa prometeu. Não resume, não repete, não se apresenta.
- **Slides 3 até N-2, desenvolvimento:** uma ideia por slide, nunca duas. Cada slide fecha um pensamento e abre o próximo.
- **Slide N-1, virada:** o insight principal, a prova, o número, o contraintuitivo. É o slide que a pessoa printa e manda no direct.
- **Slide N, CTA:** um pedido só, específico, retomando a promessa da capa.

### Limites de texto por slide

Slide de Instagram é pequeno e a arte vai ocupar espaço. Estoure isso e a copy não cabe no layout.

- Headline: até 60 caracteres, idealmente até 45
- Apoio: até 140 caracteres, 2 linhas
- Capa: headline mais curta ainda, até 40 caracteres, porque o corpo da fonte é maior

Conte os caracteres de verdade antes de entregar. Se passou, corte.

### Legenda

- **Primeira linha:** gancho próprio, nunca a repetição da capa. É o que aparece no feed antes do "mais".
- **Corpo:** 3 a 6 parágrafos de uma ou duas linhas, com quebra de linha entre eles. Expande o que não coube no carrossel. É aqui que vai o detalhe técnico, a ressalva e o número que quebraria o ritmo dos slides.
- **CTA:** um pedido explícito, alinhado ao objetivo do briefing.
- **Pergunta final:** uma pergunta fácil de responder, que puxa comentário. Pergunta difícil mata o engajamento.
- **Hashtags:** 8 a 15, no final, misturando volume alto, médio e de nicho. Nada de bloco de 30 hashtags genéricas.

### Formato de entrega

Entregue no chat, porque a pessoa vai iterar slide a slide. Use exatamente este formato:

```
## Carrossel: [tema] | [N] slides
Ângulo: [uma linha]

---
**SLIDE 1 (capa)**
Headline: [texto]
Apoio: [texto ou "sem apoio"]

**SLIDE 2**
Headline: [texto]
Apoio: [texto]

[...]

**SLIDE [N] (CTA)**
Headline: [texto]
Apoio: [texto]

---
## Variações de capa
1. [headline alternativa]
2. [headline alternativa]
3. [headline alternativa]

---
## Legenda
[legenda completa]

**Hashtags:** [8 a 15]
```

Depois do bloco, ofereça em uma linha só: ajustar algum slide, ou gerar a arte com a skill de carrossel. Sem parágrafo de despedida.

**Se a pessoa pedir arquivo,** entregue também no chat e gere o documento com as mesmas seções, mais briefing no topo, contagem de caracteres por headline e uma seção de fontes dos dados citados. Respeite o padrão visual da organização quando houver um. Em revisão posterior, regenere o arquivo junto com a copy, para não ficarem versões diferentes circulando.

---

## Regras de escrita

Escreva como uma pessoa que entende do assunto falando com outra, não como marca institucional.

**Nunca use travessão.** Use vírgula, dois pontos ou ponto final. Vale para slides e legenda, sem exceção.

**Linguagem simples é requisito, não estilo.** O leitor está no celular, na fila, com meio segundo de atenção por slide. Nomeie as coisas como a pessoa nomeia: "o Facebook", "quem preencheu o formulário", "quem assinou contrato". Sigla e termo de ofício só quando o público usa aquilo todo dia, e no máximo um por carrossel. Se um slide precisa de uma definição para ser entendido, ele está no lugar errado.

**Evite:**
- "não é X, é Y" como estrutura de frase
- frases de efeito vazias: "e a verdade é que", "vale lembrar", "no fim das contas", "a real é que"
- adjetivo empilhado: "estratégia poderosa, transformadora e definitiva"
- metáfora no lugar do fato. "Trabalha no escuro" é mais fraco que "nunca soube quem fechou"
- promessa que o nicho não sustenta, principalmente saúde, finanças e emagrecimento
- emoji como bengala de ritmo. No máximo 3 na legenda inteira, zero nos slides, a não ser que o briefing peça
- pergunta retórica na capa quando a resposta óbvia é "não"

**Busque:**
- verbo no presente e voz ativa
- número concreto no lugar de vago: "cai 40%" e não "cai bastante"
- segunda pessoa, fale com uma pessoa só
- frase curta. Se passou de 20 palavras, quebre

### Checagem antes de entregar

Rode esta lista e conserte o que falhar:

1. Lendo só as headlines em ordem, sai um parágrafo que se entende sozinho?
2. Dá para trocar dois slides de lugar sem estragar nada? Se dá, falta fio.
3. A capa funciona sozinha e deixa uma pergunta aberta?
4. O slide 2 continua a capa, em vez de repetir ou resumir?
5. O maior payoff está no fim, e não no meio?
6. Cada slide tem uma ideia só?
7. Algum slide pode ser deletado sem perda? Delete.
8. Tem número ou fato específico vindo da pesquisa em pelo menos um slide, nascido da história e não colado nela?
9. Todo slide está dentro do limite de caracteres, contado de verdade?
10. O CTA pede uma ação só e retoma a promessa da capa?
11. A primeira linha da legenda é diferente da capa?
12. Um leigo no assunto entende cada slide sem precisar de definição?
13. Tem travessão em algum lugar? Tire.

---

## Casos que não são carrossel do zero

**"Melhora essa legenda" ou "refaz o slide 3":** não rode o fluxo inteiro. Peça o contexto mínimo que falta, entregue a revisão, mostre o antes e o depois do trecho alterado. Depois confira se o slide novo ainda amarra com o anterior e com o seguinte.

**"O que eu posto essa semana":** rode a pesquisa e entregue 5 a 7 ideias de carrossel, cada uma com tema, ângulo e gancho de capa. Só escreva o carrossel completo do que ela escolher.

**"Transforma esse texto em carrossel":** o texto dado substitui a fase de briefing de conteúdo, mas ainda faça a pesquisa dos eixos 2 e 3, porque o formato e o gancho continuam sendo decisão sua. O texto original quase sempre vem em ordem de documento, não em ordem de história: reordene pela cadeia causal antes de cortar em slides.

**"Não gostei":** pergunte o que falhou antes de reescrever, com opções concretas (ângulo, capa, tom, clareza). Reescrever no escuro costuma errar de novo no mesmo ponto.

---

## Exemplos

**Capa.** Tema: contabilidade para prestadores de serviço. Objetivo: salvamento.

Fraca: "Dicas de contabilidade para o seu negócio"
Forte: "Você paga 11% de imposto. Podia pagar 6%."

A segunda tem número, tensão e uma promessa verificável. A primeira podia estar em qualquer perfil de contabilidade do país.

**Fio condutor.** Tema: por que o anúncio não mostra se está dando certo.

Sem fio, cada slide é um fato solto:
1. Seu gestor de tráfego trabalha cego
2. Ele vê o lead entrar e nunca vê fechar
3. Sem retorno, a plataforma otimiza por formulário
4. 79% dos dados de venda nunca chegam ao CRM
5. Feche o circuito devolvendo o evento

Com fio, um exemplo atravessa e cada slide puxa o próximo:
1. R$ 45 o lead. R$ 2.250 o cliente.
2. O relatório dizia que estava ótimo: 300 leads a R$ 45
3. Desses 300, seis viraram cliente
4. O Facebook nunca soube disso, ele só viu os formulários
5. Então ele foi buscar mais dos 294
6. Quem sabe quem fechou é o seu CRM
7. Salve e leve essa conta para a reunião

A segunda versão tem menos informação e converte mais. O dado dos 79% não sumiu, foi para a legenda, onde não quebra o ritmo.
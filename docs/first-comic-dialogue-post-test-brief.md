# Primeiro teste — Post em quadrinhos Ana + Sr. Santos

Status: pronto para geração visual, mas **não publicar** e **não mover para posts/approved** até aprovação explícita de Erberson.

## Objetivo do teste

Validar o novo padrão oficial de post da Carreira em Destaque:

- formato vertical/mobile;
- diálogo em quadrinhos entre Ana e Sr. Santos;
- visual premium preto/dourado;
- personagens coerentes com o Brand Book;
- balões de fala legíveis;
- PT-BR correto;
- sem logo inventada.

## Formato recomendado

- Feed/carrossel: 1080x1350 (4:5) como objetivo final.
- No `image_generate`, usar `aspect_ratio: portrait` com OpenAI `gpt-image-2-high`.
- Se necessário, ajustar/cortar depois para 4:5 mantendo área segura.

## Tema do primeiro teste

**Você trabalha muito, mas não é reconhecida?**

Esse tema foi escolhido porque aparece no Brand Book como exemplo e conecta diretamente com a dor central da persona.

## Roteiro do diálogo

Manter curto para aumentar chance de acerto do texto pela IA.

```text
ANA: Eu me esforço todo dia... mas parece que ninguém percebe.

SR. SANTOS: Ana, o problema não é o seu esforço.

SR. SANTOS: É a forma como você mostra o valor do que faz.

ANA: Então eu preciso fazer meu trabalho ser visto e entendido?
```

CTA opcional, se couber:

```text
SALVE ESTE CONTEÚDO
```

Se a IA errar texto com CTA, remover CTA na próxima rodada.

## Prompt base para OpenAI gpt-image-2-high

```text
Criar um post vertical premium estilo quadrinhos corporativo para Instagram da marca Carreira em Destaque.
Formato mobile/feed vertical, visual HQ semi-realista premium, cinematográfico, preto profundo e dourado, ambiente corporativo noturno, bordas finas douradas.

Criar UMA cena/página em quadrinhos com 4 painéis ou composição sequencial clara, usando os personagens oficiais Ana e Sr. Santos.

ANA: mulher de 28 a 35 anos, cabelo castanho escuro na altura do ombro com franja, camisa preta, calça bege, expressão humana, preocupada e profissional. Representa a assistente financeira/administrativa em evolução para analista.

SR. SANTOS: homem maduro de 50 a 60 anos, cabelo grisalho curto, barba curta, camisa/terno preto, postura calma e estratégica. Representa o mentor.

Texto em português do Brasil, em balões de diálogo grandes, legíveis e dentro da área segura. Escrever exatamente:

ANA: “Eu me esforço todo dia... mas parece que ninguém percebe.”
SR. SANTOS: “Ana, o problema não é o seu esforço.”
SR. SANTOS: “É a forma como você mostra o valor do que faz.”
ANA: “Então eu preciso fazer meu trabalho ser visto e entendido?”

Não adicionar outras palavras. Não usar inglês. Não criar pseudo-texto em notebook, dashboard, caneca, parede ou objetos. Não criar logotipo inventado. Não escrever a marca “Carreira em Destaque”. A logo oficial será aplicada depois, se necessário.

Paleta: preto #0A0A0A, grafite #1C1C1E, dourado #D4AF37, branco #FFFFFF, off-white #F5F5F5.
Visual premium, consultoria corporativa, iluminação dramática, sombras profundas, personagens expressivos, balões brancos com texto preto, detalhes dourados.
```

## Gate de validação

- [ ] Diálogo entre Ana e Sr. Santos.
- [ ] Personagens parecidos com Brand Book.
- [ ] Texto exatamente correto.
- [ ] Sem pseudo-texto.
- [ ] Sem logo inventada/deformada.
- [ ] Balões legíveis no celular.
- [ ] Visual premium, preto/dourado.
- [ ] Não parece infantil/genérico.
- [ ] Área segura respeitada.

## Referências salvas

- `docs/comic-dialogue-brandbook-references/01-comic-examples-dark-light.jpg`
- `docs/comic-dialogue-brandbook-references/02-content-guide-layout-rules.jpg`
- `docs/comic-dialogue-brandbook-references/03-ana-character-sheet.jpg`
- `docs/comic-dialogue-brandbook-references/04-sr-santos-character-sheet.jpg`
- `docs/comic-dialogue-brandbook-references/05-visual-system.jpg`

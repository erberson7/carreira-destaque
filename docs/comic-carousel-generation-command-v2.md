# Comando v2 — Carrossel Ana + Sr. Santos

Status: padrão operacional atualizado após feedback de Erberson.

## Regras novas

1. **Não editar imagens geradas pela IA.**
   - Não recortar.
   - Não adaptar para 4:5 manualmente.
   - Não aplicar borda manual.
   - Não aplicar logo manualmente.
   - Não corrigir texto por script.
   - Se falhar, regenerar.

2. **Slide 1 é hook/capa estratégico.**
   - Não precisa ser diálogo.
   - Precisa parar o scroll.
   - Deve criar curiosidade para avançar o carrossel.
   - Deve ter contexto estratégico definido antes da imagem.

3. **Slides seguintes usam diálogo Ana + Sr. Santos.**
   - Ana representa a dor/dúvida da persona.
   - Sr. Santos entrega a virada prática.

4. **Balões padronizados.**
   - Fundo branco/off-white.
   - Texto preto/grafite.
   - Contorno dourado fino.
   - Fonte limpa sem serifa, estilo Montserrat.
   - No máximo 2 balões por slide.
   - Uma frase curta por balão.
   - Preferir até 8 palavras por balão.
   - Cada balão aponta claramente para o personagem.

## Contexto estratégico obrigatório do Slide 1

Antes de gerar a primeira imagem, o estrategista deve definir:

- **Dor alvo:** qual incômodo da persona será ativado?
- **Tensão visual:** que cena mostra essa dor?
- **Curiosidade:** por que a pessoa vai querer avançar?
- **Promessa implícita:** que insight vem nos próximos slides?
- **Chamada curta:** frase de impacto da capa.

Modelo:

```text
Dor alvo: [dor específica]
Tensão visual: [cena com Ana]
Curiosidade: [lacuna que faz avançar]
Promessa implícita: [o que a pessoa vai aprender]
Chamada da capa: [texto curto]
```

## Prompt mestre para Slide 1 — hook/capa

```text
Criar SLIDE 1 de um carrossel vertical premium estilo quadrinhos corporativo para Instagram da marca Carreira em Destaque.
Usar a imagem original final gerada pela IA, sem necessidade de edição posterior.

Objetivo do slide: parar o scroll e fazer o usuário avançar o carrossel.
Este slide é uma capa/hook inteligente, não precisa ser diálogo.

Contexto estratégico:
Dor alvo: [preencher]
Tensão visual: [preencher]
Curiosidade: [preencher]
Promessa implícita: [preencher]

Visual:
HQ semi-realista premium, cinematográfico, preto profundo e dourado, ambiente corporativo noturno, borda fina dourada, composição mobile-safe, personagens e texto longe das bordas.

Personagem principal:
ANA, mulher 28-35 anos, cabelo castanho escuro na altura do ombro com franja, camisa preta e calça bege, expressão [preencher emoção].

Texto da capa:
Escrever exatamente, em título grande e legível:
“[CHAMADA CURTA]”

Padronização de texto:
Texto em português do Brasil, fonte limpa sem serifa estilo Montserrat/Bebas para título, branco e dourado, muito legível no celular.

Logo:
Usar a logo oficial enviada como referência, pequena e discreta no rodapé, mantendo forma, símbolo e texto da marca o mais fiel possível.

Não adicionar outras palavras. Não usar inglês. Não criar pseudo-texto em notebook, dashboard, parede, moldura ou objetos.
Paleta: #0A0A0A, #1C1C1E, #D4AF37, #FFFFFF, #F5F5F5.
```

## Prompt mestre para slides de diálogo

```text
Criar SLIDE [n] de um carrossel vertical premium estilo quadrinhos corporativo para Instagram da marca Carreira em Destaque.
Usar a imagem original final gerada pela IA, sem necessidade de edição posterior.

Visual:
HQ semi-realista premium, cinematográfico, preto profundo e dourado, ambiente corporativo noturno, borda fina dourada, composição mobile-safe, personagens e balões longe das bordas.

Personagens oficiais:
ANA: mulher 28-35 anos, cabelo castanho escuro na altura do ombro com franja, camisa preta e calça bege, expressão [emoção].
SR. SANTOS: homem 50-60 anos, cabelo grisalho curto, barba curta, camisa/terno preto, postura calma e estratégica.

Cena:
[descrever cena]

Balões de fala padronizados:
Fundo branco/off-white, contorno dourado fino, texto preto em fonte limpa sem serifa, estilo Montserrat, muito legível no celular. No máximo dois balões. Cada balão com uma frase curta. Balões dentro da área segura, sem cobrir rostos. Cada balão aponta claramente para o personagem correto.

Escrever exatamente estes balões, sem acrescentar nenhuma outra palavra:
ANA: “[texto curto]”
SR. SANTOS: “[texto curto]”

Logo:
Usar a logo oficial enviada como referência, pequena e discreta no rodapé, mantendo forma, símbolo e texto da marca o mais fiel possível.

Não usar inglês. Não criar pseudo-texto em objetos, dashboard, notebook ou fundo.
Paleta: #0A0A0A, #1C1C1E, #D4AF37, #FFFFFF, #F5F5F5.
```

## Gate de aprovação

- [ ] Imagem é original da IA, sem edição manual.
- [ ] Slide 1 tem hook inteligente, não só diálogo genérico.
- [ ] Balões padronizados.
- [ ] Texto correto em PT-BR.
- [ ] Sem pseudo-texto.
- [ ] Logo fiel ou aceitável.
- [ ] Personagens coerentes.
- [ ] Visual premium preto/dourado.
- [ ] Usuário teria motivo para avançar o carrossel.

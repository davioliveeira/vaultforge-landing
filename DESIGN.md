---
version: alpha
name: VaultForge
description: Arquitetura da confiança — identidade visual que transforma caos operacional em clareza. Industrial quente, anti-hype, brasileiro.
colors:
  primary: "#1A1C1E"
  secondary: "#6C7278"
  tertiary: "#C2410C"
  neutral: "#FAF8F5"
  surface: "#FFFFFF"
  border: "#E5E0DA"
  success: "#166534"
  danger: "#B91C1C"
  on-primary: "#FFFFFF"
  on-tertiary: "#FFFFFF"
  muted: "#9CA3A0"
typography:
  h1:
    fontFamily: Public Sans
    fontSize: 3rem
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.025em"
  h2:
    fontFamily: Public Sans
    fontSize: 2rem
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.015em"
  h3:
    fontFamily: Public Sans
    fontSize: 1.375rem
    fontWeight: 600
    lineHeight: 1.3
  body-lg:
    fontFamily: Public Sans
    fontSize: 1.125rem
    lineHeight: 1.6
  body-md:
    fontFamily: Public Sans
    fontSize: 1rem
    lineHeight: 1.6
  body-sm:
    fontFamily: Public Sans
    fontSize: 0.875rem
    lineHeight: 1.5
  label-caps:
    fontFamily: Public Sans
    fontSize: 0.75rem
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0.08em"
    textTransform: uppercase
  mono:
    fontFamily: "JetBrains Mono"
    fontSize: 0.875rem
    lineHeight: 1.5
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 12px
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  "2xl": 80px
  "3xl": 120px
components:
  button-primary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-tertiary}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.label-caps}"
  button-primary-hover:
    backgroundColor: "#9A3408"
    textColor: "{colors.on-tertiary}"
    rounded: "{rounded.sm}"
  button-ghost:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.label-caps}"
  button-ghost-hover:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.md}"
    padding: 24px
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.sm}"
    padding: 12px
  tag:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.secondary}"
    rounded: "{rounded.full}"
    padding: 4px
    typography: "{typography.label-caps}"
  badge:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-tertiary}"
    rounded: "{rounded.full}"
    padding: 4px
    typography: "{typography.label-caps}"
---

## Overview

VaultForge é a "arquitetura da confiança" — uma identidade visual que comunica
organização, clareza e seriedade sem frieza corporativa. O design rejeita o hype
de SaaS e abraça uma estética industrial-quente: concreto, argila, tinta e papel.

A primeira impressão deve ser: *"Essas pessoas entendem de organização. Isso é
sério, mas não é rígido. É brasileiro, mas não é informal."* O tom visual é
anti-startup-sludge: sem gradientes agressivos, sem glassmorphism, sem emoji, sem
métricas falsas. Cada elemento ganha seu lugar através de hierarquia tipográfica
e whitespace generoso.

A cor terciária (argila queimada) é o único driver de interação — botões, links,
marcadores de progresso. Usada com moderação para preservar seu sinal. O
contraste é alto onde importa (headlines, CTAs) e baixo onde não (bordas, texto
de apoio, metadados).

## Colors

Paleta de 9 cores. Neutro quente (#FAF8F5) como fundo padrão — evita o branco
hospitalar. A terciária (#C2410C) é uma argila queimada brasileira: terrosa,
quente, memorável. Diferente do azul genérico de SaaS. O sucesso (#166534) e
perigo (#B91C1C) só aparecem em estados funcionais.

- **Primary ({colors.primary}):** Tinta profunda — headlines, corpo de texto,
  superfícies de alta ênfase. Quase preto, mas com calor residual.
- **Secondary ({colors.secondary}):** Texto de apoio, metadados, rótulos.
  Contraste suficiente para legibilidade, baixo o bastante para não competir.
- **Tertiary ({colors.tertiary}):** Argila queimada — único driver de interação.
  Botões, links, selecionados, marcadores de progresso. Nunca decorativa.
- **Neutral ({colors.neutral}):** Fundo de página e superfícies de baixa ênfase.
  Off-white quente — evita o branco estéril.
- **Surface ({colors.surface}):** Cards, modais, inputs. Branco puro para
  destacar do fundo neutral.
- **Border ({colors.border}):** Linhas divisoras, bordas de input. Cinza quente
  que some na percepção mas estrutura o layout.

## Typography

Public Sans para tudo — é gratuita, open-source, tem excelente renderização em
português, e carrega o tom institucional sem ser genérica (Inter) ou formal
demais (serifas). JetBrains Mono para blocos de código e dados tabulares.

Hierarquia vem de peso e escala, não de família. Títulos grandes com tracking
negativo. Corpo médio (1rem) com line-height confortável (1.6) — densidade de
leitura, não parede de texto. Labels em caps com tracking positivo para
navegação e metadados.

## Layout

Grades baseadas em 4px. Container máximo de 1200px para conteúdo legível,
1440px para dashboards. Seções respiram com `xl` (48px) de padding vertical;
seções hero com `3xl` (120px). Cards usam `md` (16px) de gap interno,
`lg` (24px) entre cards.

Layout assimétrico quando a narrativa pede (hero, cases) e simétrico quando a
função pede (tabelas, grids de features). O whitespace não é vazio — é
ferramenta de hierarquia.

## Shapes

Cantos modestos — `sm` (4px) em botões e inputs, `md` (8px) em cards,
`lg` (12px) em modais. Nada de cantos totalmente redondos (bolhas) nem
totalmente retos (brutalistas). `rounded.full` reservado para tags e badges.

## Components

- `button-primary` é o único CTA de alta ênfase por tela. Sempre na terciária.
  Hover escurece para #9A3408.
- `button-ghost` para ações secundárias. Transparente com hover em neutral.
- `card` é a superfície padrão para agrupamento. Sem sombra por padrão — a
  borda (#E5E0DA) faz a separação.
- `input` segue o mesmo rounding e borda dos botões para consistência.
- `tag` e `badge` são pills. Tag é neutra (categorização), badge é terciária
  (atenção).

## Do's and Don'ts

- **Do** usar token references (`{colors.primary}`) — nunca repetir hex.
- **Do** preservar a terciária como sinal — se tudo é laranja, nada é.
- **Do** usar whitespace como elemento de design, não como sobra.
- **Don't** introduzir cores fora da paleta. Estenda a paleta primeiro.
- **Don't** usar gradientes, glassmorphism, sombras pesadas, ou emoji.
- **Don't** aninhar variantes de componente. `button-primary-hover` é irmão,
  não filho.
- **Don't** usar azul. O mercado B2B brasileiro já está saturado de azul SaaS.

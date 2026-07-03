# VaultForge — Prompts para Geração de Imagens

## Ferramentas alvo
- **ChatGPT Image Generator (DALL-E)** — imagens conceituais, backgrounds, composições
- **Nano Banana (Midjourney-style)** — imagens com mais textura, iluminação dramática, realismo editorial

## Direção de arte
Identidade VaultForge: anti-hype, industrial-quente, confiança. Sem gradientes agressivos, sem glassmorphism, sem ilustrações corporativas genéricas. Paleta: argila queimada (#C2410C), tinta escura (#1A1C1E), off-white quente (#FAF8F5). Atmosfera: concreto, argila, papel, luz natural brasileira. Nada de azul SaaS.

---

## 1. Hero Background — "Ordem emergindo do caos"

**Uso:** Background da seção hero, atrás do headline principal.
**Estilo:** Composição abstrata, textura rica, iluminação natural.

### ChatGPT (DALL-E)
```
A warm abstract composition representing organized knowledge emerging from chaos. Layers of translucent paper, handwritten notes, and structured geometric grids overlapping in warm clay tones (#C2410C) and deep ink blacks (#1A1C1E). Natural Brazilian daylight streaming from the upper left. No text, no people, no screens. The feeling of a quiet archive at golden hour — calm, trustworthy, human. Photorealistic texture, shallow depth of field. 16:9 aspect ratio, suitable as a hero background for a B2B landing page.
```

### Nano Banana
```
editorial photograph of scattered handwritten papers and sticky notes slowly organizing themselves into clean structured grids, warm clay and deep ink palette, natural light from a large window, dust motes visible in the light beam, shallow depth of field focusing on the transition point between chaos and order, medium format kodak portra 400 film grain, brazilian modernist architecture interior, contemplative mood, anti-corporate aesthetic --ar 16:9 --style raw --v 6
```

---

## 2. Cicatriz Section — "O conhecimento que saiu pela porta"

**Uso:** Fundo da seção da cicatriz / história real de perda de conhecimento.
**Estilo:** Evocativo, melancólico, mas não depressivo. A sensação de algo que foi perdido.

### ChatGPT (DALL-E)
```
An empty desk bathed in late afternoon Brazilian light. A chair pushed back hastily. A single notebook left open, pages half-written. The wall behind has faint shadows where sticky notes used to be — now gone. Warm terracotta floor tiles. The feeling of knowledge that walked out the door. No computers, no logos, no people. Cinematic composition, natural light, 16:9.
```

### Nano Banana
```
an abandoned desk in a brazilian office, late afternoon golden light casting long shadows, a chair pushed back, scattered papers with handwritten notes half-visible, faint adhesive residue marks on the wall where sticky notes were removed, warm terracotta floor, melancholic but not sad, the feeling of institutional knowledge lost, cinematic framing, kodak portra 800, medium format --ar 16:9 --style raw --v 6
```

---

## 3. Autoavaliação Section — "Estrutura e clareza"

**Uso:** Fundo da seção de autodiagnóstico gratuito.
**Estilo:** Limpo, organizado, convidativo. Sensação de "você pode resolver isso".

### ChatGPT (DALL-E)
```
A clean, warm architectural space representing structured thinking. Concrete walls with warm undertones, natural Brazilian light casting geometric shadows. A single wooden table with a neat stack of papers and a fountain pen. The feeling of clarity, order, and possibility. No screens, no technology visible. Architectural photography style, 16:9.
```

### Nano Banana
```
architectural interior of a warm minimalist workspace, exposed concrete walls with warm clay undertones, dramatic natural light creating geometric shadow patterns on the floor, a simple wooden desk with a neat stack of cream-colored paper, brazilian modernism influence, lina bo bardi aesthetic, calm and ordered, medium format fuji provia film --ar 16:9 --style raw --v 6
```

---

## 4. Diagnóstico Section — "O produto"

**Uso:** Background sutil atrás do product card do diagnóstico (R$2.900).
**Estilo:** Profissional, tangível. A sensação de um relatório físico, bem executado.

### ChatGPT (DALL-E)
```
Top-down view of a beautifully designed printed report. The cover page shows structured data visualizations in deep ink and warm clay colors. The paper has subtle texture. A clay-colored binding thread is visible. The document sits on a warm off-white surface. Professional, tangible, premium but not glossy. Natural light, soft shadows. No screens. 16:9.
```

### Nano Banana
```
overhead flat lay photograph of a premium printed report, cream-colored paper with subtle texture, structured data visualizations in dark ink and warm terracotta tones, visible binding with clay-colored thread, soft natural light creating gentle shadows, tangible and professional, editorial design aesthetic, hasselblad medium format --ar 16:9 --style raw --v 6
```

---

## 5. Prova Social / Testimonial — "Quem confia"

**Uso:** Background texturizado sutil atrás do depoimento.
**Estilo:** Quente, humano, texturizado.

### ChatGPT (DALL-E)
```
A warm textured wall in a Brazilian office, painted in off-white with slight aging and character. Natural light falling softly. The texture has depth — you can feel the surface. No people, no furniture visible. A quiet, trustworthy backdrop. Architectural detail shot, 16:9.
```

### Nano Banana
```
close-up of a textured off-white wall in a brazilian architecture office, natural patina and subtle imperfections, warm afternoon light grazing the surface revealing the plaster texture, the feeling of something solid and trustworthy and human, architectural detail photography, shallow depth of field, leica m6 portra 400 --ar 16:9 --style raw --v 6
```

---

## 6. CTA Final — "Horizonte de possibilidade"

**Uso:** Background da seção CTA final (fundo escuro com texto claro).
**Estilo:** Abstrato, aspiracional, mas contido. A sensação de um novo começo.

### ChatGPT (DALL-E)
```
Abstract composition suggesting a horizon at dawn. Deep warm blacks at the bottom gradually transitioning to a soft warm off-white at the top. A single thin line of warm clay color crosses the horizon. Minimalist, architectural, hopeful but restrained. No gradients, no lens flares, no sky imagery. Pure abstract. 16:9.
```

### Nano Banana
```
minimalist abstract composition, deep warm black base transitioning to warm off-white horizon, a single thin terracotta line crossing the frame, dawn light quality without showing the sun, architectural minimalism, james turrell light installation aesthetic, meditative and hopeful, --ar 16:9 --style raw --v 6
```

---

## Notas de uso

- Todas as imagens devem ser usadas como **backgrounds com overlay** — o texto da landing page fica por cima com um overlay semi-transparente (ex: `linear-gradient(rgba(250,248,245,0.85), rgba(250,248,245,0.92))`) para manter legibilidade.
- As imagens devem ser geradas em **1536×864** (16:9, 2x retina para 768px de altura) ou maior.
- Preferir as versões Nano Banana para as seções emocionais (Cicatriz, Hero) e DALL-E para as seções mais estruturadas (Diagnóstico, Autoavaliação).
- Manter consistência de paleta entre todas as imagens: evitar que uma imagem puxe para azul ou verde e quebre o sistema visual.

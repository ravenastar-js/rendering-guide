> [!IMPORTANT]
> O ChatGPT é capaz de compreender a intenção por trás de diversos parâmetros, mesmo que eles não sejam oficialmente "executáveis", como ocorre no Midjourney. Isso se deve ao fato de o modelo ter sido treinado para interpretar textos de forma contextual. Assim, ao se deparar com instruções como --ar 4:5 ou --no text, ele associa essas expressões a conceitos como “formato retrato” ou “sem elementos de texto” e adapta a imagem de acordo com essa interpretação.

---

# 🎛️ Rendering Parameters Guide (ChatGPT Image Prompts)

Este guia apresenta os principais parâmetros que você pode adicionar ao final de um prompt para personalizar a geração de imagens de forma precisa e criativa.

---

## 📐 --ar (Aspect Ratio)
Define a proporção da imagem.

- `--ar 1:1` → Quadrado  
- `--ar 4:5` → Retrato vertical (ideal para personagens)  
- `--ar 3:2` → Horizontal padrão  
- `--ar 16:9` → Widescreen  

---

## 🧠 --v (Model Version)
Especifica a versão do modelo de renderização (quando suportado).

- `--v 5` → Versão mais atual e precisa  
- `--v 6` → Versão experimental com mais realismo (se disponível)  

---

## 🧼 --style
Controla o estilo aplicado à imagem gerada.

- `--style raw` → Sem estilização adicional, fiel ao prompt  
- `--style cute` → Estilo mais fofo e estilizado  
- `--style scenic` → Ideal para paisagens  

---

## 🏗️ --quality
Determina o tempo de processamento e o nível de detalhamento.

- `--quality 1` → Padrão  
- `--quality 2` → Alta qualidade (render mais lento, mas mais nítido)  
- `--quality 0.5` → Rápido, menos detalhado  

---

## 🎨 --stylize / --s
Define o nível de criatividade aplicado ao prompt.

- `--stylize 0–1000`  
  - `--stylize 100` → Visual fiel à descrição  
  - `--stylize 800` → Estilo mais artístico e livre  

---

## 🎲 --chaos
Controla a variação entre os resultados gerados.

- `--chaos 0–100`  
  - `--chaos 0` → Resultados consistentes  
  - `--chaos 30+` → Resultados mais imprevisíveis  

---

## 🧬 --seed
Usado para gerar a mesma imagem novamente com o mesmo prompt.

- Exemplo: `--seed 20250626`  

---

## ✨ --uplight
Aplica um upscaling suave.

- `--uplight` → Ideal para resultados com visual mais limpo  

---

## ♻️ --tile
Cria imagens que podem ser usadas como padrões contínuos.

- `--tile` → Ideal para texturas ou fundos que se repetem  

---

## 🚫 --no
Remove elementos indesejados da geração.

- `--no text` → Remove textos aleatórios  
- `--no logo` → Evita marcas ou logotipos  

---

## 🧪 Parâmetros Avançados

### 🔁 --repeat / --r
Gera múltiplas variações de uma mesma imagem.

- `--repeat 3` → Gera 3 variações da mesma cena  

### 🖌️ --stylize-mode
Define modos específicos de estilização.

- `--stylize-mode expressive` → Estilo mais artístico e ousado  
- `--stylize-mode natural` → Visual mais fotográfico  

### ⏱️ --fast / --slow / --relax / --turbo
Modifica o tempo de renderização.

- `--fast` → Menos precisão, mais velocidade  
- `--slow` → Render mais detalhado e demorado  
- `--relax` → Menor custo computacional, mais tempo  
- `--turbo` → Máxima velocidade (menos controle)  

### 🌈 --color-scheme
Foca na paleta de cores usada na imagem.

- `--color-scheme pastel`  
- `--color-scheme neon`  
- `--color-scheme monochrome`  

### 🪄 --focus
Dá ênfase a uma parte específica da imagem.

- `--focus foreground` → Destaca o primeiro plano  
- `--focus background` → Valoriza o plano de fundo  

### 🌀 --weird / --w
Adiciona um toque experimental e excêntrico.

- `--weird 0–3000` → Quanto maior, mais bizarro e criativo  

### 🖼️ --iw (Image Weight)
Controla o peso de uma imagem de referência no prompt.

- `--iw 0.5` → Menor influência  
- `--iw 2.0` → Forte influência da imagem  

### 🎭 --niji
Ativa o modo de renderização com estética anime.

- `--niji` → Ideal para personagens estilo anime  

---

## 🧪 Exemplo de Prompt Completo

```text
Generate image: cyberpunk female hacker portrait  
--ar 4:5 --v 6 --style raw --quality 2 --stylize 150 --chaos 20 --seed 20250626 --uplight --no text --color-scheme neon --focus foreground --weird 500 --iw 1.5 --niji
```

---

📎 _Dica_: combine esses parâmetros com descrições visuais claras e bem categorizadas para gerar imagens ainda mais alinhadas com sua visão.

---

🎨✨ Explore abaixo as galerias temáticas de arte digital criadas com inteligência artificial.

🔗 [Ver as galerias](prompts/)

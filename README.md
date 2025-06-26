# 🎛️ Rendering Parameters Guide (ChatGPT 4o Image Prompts)

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

---

## 🧼 --style
Controla o estilo aplicado à imagem gerada.

- `--style raw` → Sem estilização adicional, fiel ao prompt  

---

## 🏗️ --quality
Determina o tempo de processamento e o nível de detalhamento.

- `--quality 1` → Padrão  
- `--quality 2` → Alta qualidade (render mais lento, mas mais nítido)  

---

## 🎨 --stylize
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

## 🧪 Exemplo de Prompt Completo

```text
Generate image: cyberpunk female hacker portrait  
--ar 4:5 --v 5 --style raw --quality 2 --stylize 150 --chaos 20 --seed 20250626 --uplight --no text
```

---

📎 _Dica_: combine esses parâmetros com descrições visuais claras e bem categorizadas para gerar imagens ainda mais alinhadas com sua visão.

🛠️ Este guia é adaptável para qualquer modelo que aceite prompts no estilo Midjourney-like.

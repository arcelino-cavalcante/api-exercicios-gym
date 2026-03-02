# 🏋️ API de Exercícios - Academia (Ultra Leve)

Esta é uma API estática que fornece uma base de dados completa de exercícios físicos em formato **MP4 Ultra Leve**, ideal para Progressive Web Apps (PWA) e aplicativos mobile que buscam alta performance e baixo consumo de dados.

## 🚀 Como utilizar
A API é servida via GitHub de forma gratuita. Você só precisa fazer o fetch do arquivo JSON:

```javascript
const API_URL = "https://raw.githubusercontent.com/arcelino-cavalcante/api-exercicios-gym/main/database.json";

fetch(API_URL)
  .then(res => res.json())
  .then(data => console.log(data));
```

## 📊 Estatísticas
- **Total de Exercícios:** 963
- **Formato:** MP4 (H.264)
- **Tamanho Médio por Vídeo:** 300KB - 600KB (Redução de 90% em relação ao GIF original)
- **Aceleração:** Suporta Playback nativo com aceleração de hardware.

## 🎥 Player Sugerido
Para emular o comportamento de um GIF de forma performática:
```html
<video autoplay loop muted playsinline>
  <source src="URL_DO_VIDEO" type="video/mp4">
</video>
```

---
*Base de dados extraída e otimizada por Antigravity AI.*

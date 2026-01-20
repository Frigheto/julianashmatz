# Vídeo de Fundo do Hero

## 📹 Arquivo Necessário

Coloque seu vídeo de fundo nesta pasta com um dos seguintes nomes:

- `hero-background.mp4` (recomendado)
- `hero-background.webm` (opcional, para melhor compatibilidade)

## 🎬 Especificações Recomendadas

### Formato e Codec
- **Formato principal:** MP4 (H.264)
- **Formato alternativo:** WebM (VP9)
- **Resolução:** 1920x1080 (Full HD) ou 3840x2160 (4K)
- **Taxa de quadros:** 24-30 fps
- **Duração:** 10-30 segundos (loop automático)

### Características do Vídeo Ideal
- **Conteúdo:** Criança estudando, aprendendo, interagindo com materiais educacionais
- **Estilo:** Slow motion, close-ups, iluminação natural
- **Cores:** Tons azuis e laranjas (para combinar com a paleta do site)
- **Movimento:** Suave e não distrativo
- **Áudio:** Não necessário (o vídeo está em mute)

### Otimização
- **Tamanho do arquivo:** Máximo 10MB (idealmente 3-5MB)
- **Bitrate:** 2-4 Mbps para MP4
- **Compressão:** Use HandBrake ou similar para otimizar

## 🎨 Sugestões de Conteúdo

1. **Criança autista feliz estudando** com materiais visuais
2. **Mãos manipulando materiais educacionais** (matemática, letras)
3. **Close-up de atividades sendo completadas** com sucesso
4. **Expressões de concentração e alegria** durante aprendizado
5. **Materiais ABA em uso** (passo a passo visual)

## 🔧 Como Converter/Otimizar Seu Vídeo

### Usando FFmpeg (linha de comando):

```bash
# Converter para MP4 otimizado
ffmpeg -i seu-video.mov -c:v libx264 -crf 28 -preset slow -c:a aac -b:a 128k -vf scale=1920:1080 hero-background.mp4

# Converter para WebM otimizado
ffmpeg -i seu-video.mov -c:v libvpx-vp9 -crf 35 -b:v 0 -vf scale=1920:1080 hero-background.webm
```

### Usando HandBrake (interface gráfica):
1. Abra HandBrake
2. Carregue seu vídeo
3. Selecione preset "Web" > "Gmail Small 3 Minutes 480p30"
4. Ajuste resolução para 1920x1080
5. Salve como `hero-background.mp4`

## 📱 Bancos de Vídeo Gratuitos

Se precisar de um vídeo temporário ou de exemplo:

- **Pexels Videos:** https://www.pexels.com/pt-br/videos/
- **Pixabay Videos:** https://pixabay.com/pt/videos/
- **Coverr:** https://coverr.co/
- **Mixkit:** https://mixkit.co/free-stock-video/

**Palavras-chave de busca:**
- "child studying"
- "education learning"
- "kids classroom"
- "autism therapy"
- "visual learning"

## ⚠️ Nota Importante

O vídeo aparecerá com:
- **Opacidade:** 30% (semi-transparente)
- **Blur:** Leve desfoque para não distrair
- **Overlay:** Gradiente escuro por cima para manter legibilidade do texto

Isso significa que o vídeo deve ser visualmente interessante, mas não precisa ser perfeito, pois será usado como elemento de fundo sutil.

---

**Status atual:** Aguardando upload do vídeo.
**O site funcionará normalmente** mesmo sem o vídeo (mostrará apenas o fundo escuro).

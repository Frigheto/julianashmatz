# 🎥 Instruções para Adicionar o Vídeo de Fundo

## Localização do Arquivo

Coloque seu vídeo nesta pasta:
```
/assets/videos/hero-background.mp4
```

## Nome do Arquivo

O arquivo DEVE se chamar exatamente:
- **`hero-background.mp4`** (formato principal)
- ou **`hero-background.webm`** (formato alternativo)

⚠️ **IMPORTANTE:** O nome deve ser exatamente esse, com letras minúsculas e o hífen.

## Como Adicionar o Vídeo

### Opção 1: Via Finder (macOS)
1. Abra o Finder
2. Navegue até: `Documents/lpjulianashmatz/assets/videos/`
3. Arraste e solte seu vídeo nesta pasta
4. Renomeie o arquivo para `hero-background.mp4`

### Opção 2: Via Terminal
```bash
# Copiar o vídeo para a pasta correta
cp ~/Downloads/seu-video.mp4 ~/Documents/lpjulianashmatz/assets/videos/hero-background.mp4
```

## Especificações Ideais do Vídeo

- ✅ **Formato:** MP4 (H.264)
- ✅ **Resolução:** 1920x1080 (Full HD)
- ✅ **Duração:** 10-30 segundos
- ✅ **Tamanho:** 3-10MB
- ✅ **Conteúdo:** Criança estudando, aprendendo, materiais educacionais
- ✅ **Estilo:** Slow motion, suave, não distrativo

## Como Ficará Visualmente

O vídeo será exibido:
- ✨ Como fundo da seção hero (topo da página)
- 🌫️ Com blur leve para não distrair
- 🎨 Com overlay escuro (30% de opacidade)
- 🔁 Em loop infinito
- 🔇 Sem áudio (mudo)

## Sugestões de Conteúdo

**Ótimas opções:**
1. Criança autista feliz interagindo com materiais
2. Close-up de mãos manipulando atividades educacionais
3. Material ABA sendo usado (passo a passo visual)
4. Expressões de concentração e alegria
5. Ambiente de aprendizado acolhedor

**Evite:**
- ❌ Vídeos muito rápidos ou agitados
- ❌ Cores muito saturadas ou contrastantes
- ❌ Movimentos bruscos de câmera
- ❌ Texto ou elementos que possam confundir

## Onde Encontrar Vídeos (se não tiver um)

### Gratuitos:
- [Pexels](https://www.pexels.com/pt-br/videos/) - Busque: "child studying", "education"
- [Pixabay](https://pixabay.com/pt/videos/) - Busque: "learning", "classroom"
- [Coverr](https://coverr.co/) - Busque: "education", "kids"

### Como usar vídeos de banco de imagens:
1. Baixe o vídeo em qualidade HD
2. Renomeie para `hero-background.mp4`
3. Coloque na pasta `assets/videos/`

## Como Otimizar Seu Vídeo

Se seu vídeo estiver muito grande (>10MB):

### Online (Fácil):
- Use: https://www.freeconvert.com/video-compressor
- Upload do vídeo
- Reduza para ~5MB
- Baixe e use

### Local (Usando HandBrake - Gratuito):
1. Baixe HandBrake: https://handbrake.fr/
2. Abra seu vídeo no HandBrake
3. Preset: "Web" > "Gmail Small"
4. Ajuste resolução: 1920x1080
5. Export e salve como `hero-background.mp4`

## Verificar se Funcionou

1. Abra `index.html` no navegador
2. O vídeo deve aparecer de fundo na seção hero (topo)
3. Deve estar levemente desfocado e transparente
4. Deve rodar em loop automaticamente

## Sem Vídeo?

**Não tem problema!** O site funciona perfeitamente sem o vídeo. Neste caso:
- O fundo será o gradiente azul escuro padrão
- A página mantém toda funcionalidade e beleza
- Você pode adicionar o vídeo depois, quando quiser

---

## 🆘 Problemas Comuns

**O vídeo não aparece:**
- ✓ Verifique se o nome está correto: `hero-background.mp4`
- ✓ Verifique se está na pasta certa: `assets/videos/`
- ✓ Recarregue a página (Cmd+R ou Ctrl+R)

**O vídeo está muito lento:**
- ✓ Reduza o tamanho do arquivo (compacte)
- ✓ Use resolução 1080p em vez de 4K

**O vídeo não roda em loop:**
- ✓ Já está configurado para loop automático no código

---

**Pronto!** Seu site agora tem um design tecnológico, minimalista e com vídeo de fundo profissional! 🚀

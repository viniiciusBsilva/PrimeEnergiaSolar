# Landing page Prime Energia Solar (São Luís - MA)

Esta é a landing page da **Prime Energia Solar** ([@primeenergiasolarsaoluis](https://www.instagram.com/primeenergiasolarsaoluis/)). Ela é estática (HTML + Bootstrap 4 + jQuery) e não precisa de servidor nem de build. Para abrir, basta dar dois cliques em `index.html` ou publicar a pasta em qualquer hospedagem estática, como Netlify, Vercel, GitHub Pages ou Hostinger.

## Estrutura
- `index.html` contém a página inteira.
- `css/style.css` é o Bootstrap do template com as cores da Prime (laranja `#f08a00` e marinho `#0b1f3a`).
- `css/custom.css` tem os estilos próprios da Prime: hero, números, passos, avaliações, FAQ, WhatsApp flutuante.
- `js/main.js` controla carrosséis, rolagem suave, navbar e botão de voltar ao topo.
- `js/whatsapp-form.js` monta a mensagem do formulário de orçamento e abre o WhatsApp.
- `js/hero-video.js` carrega o vídeo de fundo do banner (versão leve no celular). Se o sistema do visitante estiver com "reduzir movimento" ativado, ele mostra só a imagem de capa.
- `video/` guarda o vídeo do banner, otimizado a partir do original 4K: `hero.mp4` em 1080p (~6 MB), `hero-mobile.mp4` em 540p (~2 MB) e `hero-poster.jpg` como capa. O arquivo original `img/12858696-uhd_3840_2160_60fps.mp4` (60 MB) **não é usado pelo site** e não precisa ir para a hospedagem.
- `img/` guarda as imagens. As atuais são **genéricas**, então troque pelas fotos reais.

## Dados usados (levantados em 03/11/2026)
| Informação | Valor | Fonte |
|---|---|---|
| Bio | "Economize até 85% na conta de energia · Energia rápida e barata · Desde 2020" | Instagram |
| WhatsApp | (98) 98403-8169 | Link do WhatsApp Business na bio do Instagram |
| Endereço | Posto Jaguar, Av. dos Holandeses, 05, Sala 12, Olho D'Água, São Luís - MA, 65065-180 | Diretório energiasolarexplicada.com.br |
| Google | Nota 5.0, 53 avaliações | Mesmo diretório |
| CNPJ | 38.492.844/0001-70 (Prime Energia Solar LTDA) | Agregador de CNPJ |

**Confirme com o cliente** o endereço, o CNPJ e o número de avaliações, porque os dois últimos vieram de sites de terceiros. A nota e a contagem de avaliações estão escritas no HTML em vários lugares (números, Sobre, Avaliações, Contato e o JSON-LD no `<head>`). Atualize todos quando mudarem.

## Imagens para substituir (mantenha o mesmo nome do arquivo)
| Arquivo | Onde aparece | Sugestão |
|---|---|---|
| `video/hero.mp4` (+ `hero-mobile.mp4` e `hero-poster.jpg`) | Fundo do banner principal | Um vídeo de uma obra real da Prime, se houver |
| `img/carousel-1.jpg` | Janela "Como funciona a energia solar?" | Foto de uma instalação da Prime |
| `img/about.jpg` | Seção "Sobre" (retrato, ~700×800) | Equipe instalando ou a fachada do escritório |
| `img/product-1.jpg`, `img/gallery-2.jpg`, `img/gallery-6.jpg` | Cards de serviços | Uma residência, um comércio e um técnico |
| `img/gallery-1.jpg` a `img/gallery-6.jpg` | Galeria "Projetos" (quadradas, 400×400 ou maior) | Fotos dos posts e reels do Instagram |
| `img/gallery.jpg` | Fundo da galeria | Qualquer foto ampla de painéis |
| `img/favicon.svg` | Ícone da aba | Logo da Prime, se houver |

## Ainda não incluído (não estava disponível publicamente)
- Logo oficial: a navbar usa por enquanto um ícone de sol com o texto "PRIME Energia Solar".
- Depoimentos em texto: a página aponta para as avaliações do Google em vez de inventar depoimentos.
- Horário de atendimento e e-mail.
- Nome e foto do responsável técnico ou do proprietário (o perfil cita "@junior").

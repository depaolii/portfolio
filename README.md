<div align="center">

# Marcello De Paoli

**Vibe coder.** Crio com Claude Code sistemas que editam vídeo, publicam conteúdo, prospectam clientes e vendem produto digital.

[Instagram @celo.tech](https://www.instagram.com/celo.tech/) · [GitHub](https://github.com/depaolii)

</div>

---

## Como navegar

Clique no nome do projeto para ler como ele funciona, ou em **Abrir** para ver o que está no ar.

| | Projeto | Em uma frase | Ver |
|:-:|---|---|:-:|
| 1 | [Editor de Reels](#1-editor-de-reels) | Entra o vídeo bruto, sai o Reels editado | [Abrir](https://www.instagram.com/celo.tech/) |
| 2 | [Sede de agentes](#2-sede-de-agentes) | 8 agentes de IA produzem meu Instagram | [Demo](#2-sede-de-agentes) |
| 3 | [Planilha Adeus Dívidas](#3-planilha-adeus-dívidas) | Produto digital com vendas reais | [Abrir](https://planilha-adeus-dividas.netlify.app) |
| 4 | [Loja KRAVEN](#4-loja-kraven) | E-commerce de camisetas de academia | [Abrir](https://kraven-loja.netlify.app) |
| 5 | [Site da Algup](#5-site-da-algup) | Site de agência para enviar por WhatsApp | [Abrir](https://algup.netlify.app) |
| 6 | [Portfólio de edição](#6-portfólio-de-edição) | Página com meus vídeos para captar clientes | [Abrir](https://marcello-portfolio.pages.dev) |
| 7 | [Robô de prospecção](#7-robô-de-prospecção) | Encontra leads e conversa até a reunião | Privado |

---

## 1. Editor de Reels

**O que faz:** transforma um vídeo bruto e um roteiro em um Reels pronto para postar.

**Como funciona:**

1. Eu envio o vídeo bruto e o roteiro.
2. O sistema corta pausas e erros de fala.
3. Ele escolhe vídeos de apoio e coloca legenda, música, efeitos e cor.
4. O Reels chega no meu Telegram. Eu aprovo e ele posta no horário.

**Exemplo real:** um bruto de 4min08 virou um Reels de 1min45.

**Também usado em:** anúncios da Óticas Góes (5 criativos aprovados), Reels de imóveis da Marangoni e Reels da Tuon Cosméticos.

**Feito com:** Claude Code, Python e ffmpeg.

<p align="center"><img src="demos/reels-bruto-vs-final.webp" width="480" alt="Vídeo bruto ao lado do Reels editado"><br><sub>Bruto à esquerda, editado à direita. <a href="demos/reels-bruto-vs-final.mp4">Ver com som</a></sub></p>

[↑ Voltar ao início](#como-navegar)

---

## 2. Sede de agentes

**O que faz:** uma equipe de 8 agentes de IA produz o conteúdo do @celo.tech, e um escritório 3D mostra tudo ao vivo.

**Como funciona:**

1. Os agentes pesquisam notícias de IA.
2. Eles escrevem e criam os posts.
3. Os posts são publicados 2 vezes por dia.
4. Eu gravo o Reels de manhã e acompanho o resto pelo painel.

**Feito com:** Claude Code, Node.js e Three.js, com integração ao Telegram e ao Instagram. O executor de tarefas foi adaptado de um projeto do meu irmão, Gui De Paoli.

<p align="center"><img src="demos/sede-agentes.webp" width="800" alt="Escritório 3D com os agentes e o painel do dia"></p>

[↑ Voltar ao início](#como-navegar)

---

## 3. Planilha Adeus Dívidas

**O que faz:** produto digital para organizar e quitar dívidas, já com compradores reais.

**O que eu criei:**

1. A planilha e os bônus.
2. A página de vendas, com depoimentos de compradores.
3. O checkout na Kiwify.
4. As campanhas no Meta Ads, testando criativos diferentes.

**Feito com:** Netlify, Kiwify e Meta Ads.

<p align="center"><a href="https://planilha-adeus-dividas.netlify.app"><img src="demos/planilha.webp" width="260" alt="Página de vendas no celular"></a></p>

[↑ Voltar ao início](#como-navegar)

---

## 4. Loja KRAVEN

**O que faz:** loja virtual de camisetas oversized de academia.

**O que tem:**

1. Catálogo com filtros e páginas de drop.
2. Carrinho com barra de frete grátis e kit "Leve 3" com desconto automático.
3. Cupom e "Qual meu tamanho?".
4. Checkout em modo demonstração, sem cobrança.

**Feito com:** Next.js.

<p align="center"><a href="https://kraven-loja.netlify.app"><img src="demos/kraven.webp" width="260" alt="Loja KRAVEN no celular"></a></p>

[↑ Voltar ao início](#como-navegar)

---

## 5. Site da Algup

**O que faz:** apresenta uma agência de audiovisual e tráfego pago para quem recebe o link pelo WhatsApp.

**O foco:** convencer em uma única visita, pelo celular, mesmo com internet ruim.

**Feito com:** HTML, CSS e JavaScript puros.

<p align="center"><a href="https://algup.netlify.app"><img src="demos/algup.webp" width="260" alt="Site da Algup no celular"></a></p>

[↑ Voltar ao início](#como-navegar)

---

## 6. Portfólio de edição

**O que faz:** mostra 9 vídeos verticais editados por mim, com um botão para chamar no WhatsApp.

**Feito com:** site de uma página, publicado no Cloudflare Pages.

<p align="center"><a href="https://marcello-portfolio.pages.dev"><img src="demos/portfolio-edicao.webp" width="260" alt="Portfólio de edição no celular"></a></p>

[↑ Voltar ao início](#como-navegar)

---

## 7. Robô de prospecção

**O que faz:** encontra profissionais autônomos e conduz a conversa até marcar uma reunião.

**Como funciona:**

1. Encontra o lead e avalia o site dele.
2. Escreve a primeira mensagem.
3. Conversa seguindo o método SPIN e faz follow-up.
4. Leva o lead até a reunião.

**No Instagram é semiautomático, de propósito:** o robô escreve e eu envio, para não arriscar a conta.

**Feito com:** Python e Google Sheets. A base é um projeto do meu irmão, Gui De Paoli. Eu adaptei para Windows, mudei o público e as ofertas, e criei a versão de Instagram.

**Por que não tem link:** o código é privado porque guarda dados de leads (LGPD).

[↑ Voltar ao início](#como-navegar)

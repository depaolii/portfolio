<div align="center">

# Marcello De Paoli

**Vibe coder.** Crio com Claude Code sistemas que editam vídeo, publicam conteúdo e prospectam clientes.

[Instagram @celo.tech](https://www.instagram.com/celo.tech/) · [GitHub](https://github.com/depaolii)

</div>

---

## Como navegar

Clique no nome do projeto para ler como ele funciona, ou em **Abrir** para ver o que está no ar.

| | Projeto | Em uma frase | Ver |
|:-:|---|---|:-:|
| 1 | [Editor de Reels](#1-editor-de-reels) | Entra o vídeo bruto, sai o Reels editado | [Vídeo](https://youtu.be/6wW6w726Wt4) |
| 2 | [Sede de agentes](#2-sede-de-agentes) | 8 agentes de IA produzem meu Instagram | [Demo](#2-sede-de-agentes) |
| 3 | [Carrosséis do @celo.tech](#3-carrosséis-do-celotech) | Pesquisa, cria e publica posts de IA todo dia | [Abrir](https://www.instagram.com/celo.tech/) |
| 4 | [Carrosséis da AlgUp](#4-carrosséis-da-algup) | Carrosséis automáticos para uma agência de marketing | [Abrir](https://www.instagram.com/algupdigital/) |
| 5 | [Sobra](#5-sobra) | App que mostra quanto você ainda pode gastar | [Abrir](https://sobra-app-demo.netlify.app) |
| 6 | [Loja KRAVEN](#6-loja-kraven) | E-commerce de camisetas de academia | [Abrir](https://kraven-loja.netlify.app) |
| 7 | [Site da Algup](#7-site-da-algup) | Site de agência para enviar por WhatsApp | [Abrir](https://algup.netlify.app) |
| 8 | [Portfólio de edição](#8-portfólio-de-edição) | Página com meus vídeos para captar clientes | [Abrir](https://marcello-portfolio.pages.dev) |
| 9 | [Robô de prospecção](#9-robô-de-prospecção) | Encontra leads e conversa até a reunião | Privado |

---

## 1. Editor de Reels

**O que faz:** transforma um vídeo bruto e um roteiro em um Reels pronto para postar.

▶️ **[Assista ao sistema funcionando (1min43)](https://youtu.be/6wW6w726Wt4)**

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

## 3. Carrosséis do @celo.tech

**O que faz:** cria e publica posts sobre novidades de IA e tecnologia no meu perfil, todos os dias.

**Como funciona:**

1. Pesquisa as notícias do dia.
2. Escolhe o formato que combina com a notícia: carrossel, imagem única ou vídeo.
3. Cria os slides e a legenda, citando as fontes.
4. O post entra na fila de aprovação pelo Telegram e sai às 12h ou às 18h.

**Feito com:** Claude Code, Node.js, Telegram e API do Instagram.

<p align="center"><img src="demos/carrossel-celo.webp" width="320" alt="Carrossel do @celo.tech passando slide a slide"></p>

[↑ Voltar ao início](#como-navegar)

---

## 4. Carrosséis da AlgUp

**O que faz:** escolhe a pauta, cria e publica os carrosséis da agência de marketing AlgUp, toda segunda e sexta.

**Como funciona:**

1. Escolhe a pauta do post.
2. Monta de 6 a 8 slides com pouco texto, sempre com uma composição nova.
3. Manda para aprovação no Telegram. Nada é publicado sem aprovação.
4. Depois de aprovado, publica às 11h30, chamando para o WhatsApp.

**Feito com:** Claude Code, Node.js, Telegram e API do Instagram.

<p align="center"><img src="demos/carrossel-algup.webp" width="320" alt="Carrossel da AlgUp passando slide a slide"></p>

[↑ Voltar ao início](#como-navegar)

---

## 5. Sobra

**O que faz:** app de finanças pessoais que responde a pergunta *"quanto eu ainda posso gastar até a próxima renda?"*.

**Como funciona:**

1. Mostra o saldo e quanto está livre para gastar por dia.
2. Lista os compromissos e as parcelas do mês.
3. O "Posso comprar?" diz se uma compra cabe, à vista ou parcelada.
4. Mostra o planejamento dos próximos 6 meses.

**Feito com:** Next.js, React, TypeScript, Supabase e testes automatizados com Playwright. Projeto em parceria com o meu irmão, Gui De Paoli.

**Observação:** o link abre o modo demonstração, com dados de exemplo.

<p align="center"><a href="https://sobra-app-demo.netlify.app"><img src="demos/sobra.webp" width="260" alt="Telas do Sobra no celular"></a></p>

[↑ Voltar ao início](#como-navegar)

---

## 6. Loja KRAVEN

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

## 7. Site da Algup

**O que faz:** apresenta uma agência de audiovisual e tráfego pago para quem recebe o link pelo WhatsApp.

**O foco:** convencer em uma única visita, pelo celular, mesmo com internet ruim.

**Feito com:** HTML, CSS e JavaScript puros.

<p align="center"><a href="https://algup.netlify.app"><img src="demos/algup.webp" width="260" alt="Site da Algup no celular"></a></p>

[↑ Voltar ao início](#como-navegar)

---

## 8. Portfólio de edição

**O que faz:** mostra 9 vídeos verticais editados por mim, com um botão para chamar no WhatsApp.

**Feito com:** site de uma página, publicado no Cloudflare Pages.

<p align="center"><a href="https://marcello-portfolio.pages.dev"><img src="demos/portfolio-edicao.webp" width="260" alt="Portfólio de edição no celular"></a></p>

[↑ Voltar ao início](#como-navegar)

---

## 9. Robô de prospecção

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

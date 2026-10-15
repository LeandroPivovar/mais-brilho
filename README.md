# +Brilho Estética Automotiva

Site institucional da +Brilho Estética Automotiva. HTML/CSS/JS estático, sem build.
Base derivada do site da Alves Estética Automotiva (mesmo segmento), com a identidade da capa do WhatsApp:
azul royal, "+BRILHO" cromado e preto. As regras próprias ficam no fim do `styles.css`.

```bash
npx --yes serve . -l 6510
```

## Estrutura

```
index.html
assets/
  css/styles.css
  js/main.js              menu mobile, formulário -> WhatsApp, FAQ, reveal ao rolar, ano do rodapé
  fonts/phosphor/         ícones Phosphor (woff2 local, licença MIT)
  img/favicon.svg         "+" cromado no azul royal
```

Sem logo em arquivo nem fotos: a marca é texto e o hero tem a silhueta de um carro em SVG. A foto de perfil
(o dono com a arte da empresa) não foi usada.

## Dados usados (fonte: perfil do WhatsApp Business)

| Campo | Valor |
|---|---|
| Nome | +Brilho Estética Automotiva |
| WhatsApp / telefone | (31) 97260-5039 (`wa.me/5531972605039`; o número com o 9 aparece na foto de perfil) |
| Horário | Aberta 24 horas |
| Serviços (foto de perfil) | Limpeza técnica detalhada; Polimento técnico e comercial |

## Confirmar com o cliente

- **Serviços:** a foto de perfil lista só "limpeza técnica detalhada" e "polimento técnico e comercial". Os textos
  que explicam a diferença entre polimento técnico (mais etapas, mais correção) e comercial (mais rápido,
  revitaliza o brilho) seguem o uso comum do mercado. Confirmar e acrescentar outros serviços (vitrificação,
  higienização, cristalização...).
- **"Aberto 24 horas":** está no perfil do WhatsApp. Confirmar se é atendimento presencial 24h ou só pelo WhatsApp.
- **Endereço / cidade:** não informados (DDD 31, região de Belo Horizonte). Com o endereço dá para incluir mapa.
- **Logo e fotos:** pedir a logo em arquivo (a da capa tem baixa resolução) e fotos de antes e depois.

## Depoimentos

Não foram incluídos, para não publicar avaliações inventadas.

Fontes: Saira e Manrope (Google Fonts, OFL).

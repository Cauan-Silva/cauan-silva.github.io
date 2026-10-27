# Cauan Silva · site

Site para apresentar e vender os meus serviços: sistemas prontos, sistemas sob medida, automação e dados, sites e lojas.

Uma página só, em HTML e CSS, sem build. Publicado pelo GitHub Pages em https://cauan-silva.github.io.

## Configurações (no começo do `index.html`)

```js
const CONTATO = {
  whatsapp: '5548999998888', // DDI + DDD + número, só números
  email: 'voce@exemplo.com',
}
const CONTADOR = '' // código do GoatCounter, ex.: 'cauansilva'
```

## Contador de visitas (GoatCounter)

1. Crie a conta grátis em https://www.goatcounter.com/signup e escolha um código (ex.: `cauansilva`).
2. Coloque esse código em `CONTADOR`.
3. Os cliques em cada botão de WhatsApp e no e-mail aparecem no painel como eventos (`whatsapp-topo`, `whatsapp-pedido`, `whatsapp-agenda`, `whatsapp-celular`, `email`).

## Google

`robots.txt`, `sitemap.xml` e os dados estruturados (JSON-LD no `<head>`) já estão prontos. Para verificar o site no Google Search Console, use o método **Arquivo HTML**: baixe o arquivo `googleXXXX.html` que o Google gerar, coloque nesta pasta e faça o push.

## Vídeos dos projetos

`videos/*.mp4` (H.264) com `*.webm` (VP9) de reserva e `*.webp` como capa. Tocam só enquanto aparecem na tela e ficam parados para quem usa "reduzir movimento".

## Domínio próprio

1. Registre o domínio (ex.: `cauansilva.com.br` no Registro.br).
2. Crie aqui um arquivo `CNAME` com uma linha só: o domínio (ex.: `cauansilva.com.br`).
3. No Registro.br, em DNS, aponte o domínio para o GitHub Pages: registros `A` para `185.199.108.153`, `185.199.109.153`, `185.199.110.153` e `185.199.111.153`, e um `CNAME` de `www` para `cauan-silva.github.io`.
4. Em **Settings → Pages**, preencha o domínio e marque **Enforce HTTPS** quando ficar disponível.
5. Troque `https://cauan-silva.github.io/` pelo domínio novo no `index.html` (metatags e JSON-LD), no `robots.txt` e no `sitemap.xml`.

# Cauan Silva · site

Site para apresentar e vender os meus serviços: sistemas prontos, sistemas sob medida, automação e dados, sites e lojas.

Uma página só, em HTML e CSS, sem build. Publicado pelo GitHub Pages.

## Contatos

Os botões de WhatsApp e e-mail leem o bloco `CONTATO` no começo do `index.html`:

```js
const CONTATO = {
  whatsapp: '5548999998888', // DDI + DDD + número, só números
  email: 'voce@exemplo.com',
}
```

Sem o número, os botões levam para a seção de contato; sem o e-mail, o botão de e-mail some.

# AI Leadership · assets de e-mail

Hospedagem pública das imagens usadas na régua de comunicação do **AI Leadership**, da
StartSe. Servido por GitHub Pages.

Este repositório existe por um motivo só: **e-mail não aceita imagem em caminho relativo
nem em data URI.** Gmail e Outlook bloqueiam ou removem base64, então todo asset precisa de
uma URL pública e estável.

## Base

```
https://guibc18-svg.github.io/ai-leadership-assets/
```

| Arquivo | Onde aparece |
|---|---|
| `img/logo-al-alpha.png` | header de todos os e-mails |
| `img/logo-academy-branco.png` | assinatura "Equipe StartSe \| AI Academy" |
| `img/logo-startse-branco.png` | rodapé de marca |
| `img/header.png` · `img/hero.png` | variantes de topo |
| `img/bg/al-veu-blobs.jpg` | fundo do corpo, 600×2800, ancorado no topo |
| `img/bg/al-fecho.jpg` | fundo do rodapé, 600×360, ancorado na base |
| `img/social/*.png` | 5 ícones de rede social, 72×72 |

## Regras

⚠️ **Não renomear nem apagar nada aqui.** Estas URLs ficam dentro de e-mails já entregues.
Mudar um caminho quebra a imagem em toda mensagem que já saiu.

⚠️ **Os ícones sociais vieram do CDN do Mailjet** e foram internalizados em 08/09/2026, para
tirar a dependência de um terceiro que podia sumir no meio da régua.

Os arquivos-fonte vivem no projeto local, em `01-regua/template/img/`. Este repositório é
uma cópia publicada, não a fonte.

## Migração

Quando a StartSe fornecer um CDN institucional, basta trocar a constante `BASE` no
`réguas/build-entrega.py` do projeto e regerar os 40 arquivos. ⚠️ Isso vale apenas para
envios futuros: e-mail já entregue continua apontando para cá, então **este repositório não
pode ser apagado** depois da migração.

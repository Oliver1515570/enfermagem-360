# Enfermagem 360

Página pública do QR code: **https://oliver1515570.github.io/enfermagem-360/**

Hospedada no GitHub Pages (grátis, HTTPS, sem login pra quem acessa).

## Como atualizar a página

Edite o `index.html` e rode:

    git add -A && git commit -m "atualiza pagina" && git push

O site atualiza sozinho em ~1 minuto. **O QR code continua o mesmo** — a URL não muda,
então não precisa reimprimir nada.

## Arquivos do QR code (pasta `qr/`)

| Arquivo | Pra que serve |
|---|---|
| `cartao-enfermagem-360.png` | Cartão pronto pra imprimir (2000x2800, ~17x24 cm a 300 dpi) |
| `qrcode-enfermagem-360.png` | Só o QR code, 1600px — WhatsApp, Instagram, slides |
| `qrcode-enfermagem-360.svg` | Só o QR code em vetor — pra gráfica / banner / adesivo, escala sem perder qualidade |

QR gerado com correção de erro nível H (o mais alto): continua lendo mesmo com
até ~30% do código sujo, rasgado ou coberto.

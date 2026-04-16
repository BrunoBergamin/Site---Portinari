# Colégio Portinari — Site Institucional

Landing page institucional do **Colégio Portinari**, a única escola-chácara de Boituva/SP, com 8.000m² de natureza. Atende Berçário, Educação Infantil e Ensino Fundamental I.

## Tecnologias

- **HTML5** semântico
- **Tailwind CSS** (via CDN) — paleta customizada (verde, creme, terracota)
- **Alpine.js** — interatividade leve (menu mobile, tabs de segmentos)
- **Google Fonts** — Fraunces + DM Sans

## Estrutura

```
.
├── index.html          # Página única (single-page)
├── assets/
│   ├── css/main.css    # Estilos customizados
│   ├── js/             # Scripts
│   └── img/            # Imagens
└── README.md
```

## Seções

- Hero com chamada para matrículas
- Segmentos (Berçário, Infantil, Fundamental I)
- Diferenciais da escola-chácara
- Estrutura e espaços
- Contato e formulário

## Como executar

Basta abrir o `index.html` no navegador ou servir com qualquer servidor estático:

```bash
# Com Python
python -m http.server 8000

# Com Node (npx)
npx serve .
```

Acesse: `http://localhost:8000`

## Contato

- **Telefone:** (15) 3363-4057
- **WhatsApp:** (15) 99787-8556
- **Localização:** Boituva — SP

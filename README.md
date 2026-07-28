# ArmaCrack — Landing (Mundial 2026)

Landing page de la oferta **ArmaCrack**, modelada con el método R10K a partir de la oferta de referencia "MontaCraque", adaptada a Argentina (voseo, ARS, MercadoPago, sin mención de cuotas).

## Estructura

- `index.html` — landing de una sola página, HTML+CSS+JS vanilla, mobile-first, lazy load.
- `images/` — assets comprimidos a WebP liviano.
- `docs/` — entregables del método R10K:
  - `oferta.md` — Paso 1: oferta modelada (producto, bonus, precio, objeciones).
  - `investigacion.md` — Paso 2: investigación de mercado (avatares, ángulos, TL;DR).
  - `guiones.md` — Paso 4: guiones de video (hooks + estructuras).
  - `mockups-prompts.md` — Paso 5: prompts para mockups y creativos de ads.
  - `copys-meta.md` — Paso 6: copys y headlines para Meta Ads.

## Pendiente antes de pautar

- [ ] Conectar el link/checkout de MercadoPago en los botones `data-checkout-btn` (`index.html`).
- [ ] Pegar el Pixel ID de Meta en el bloque comentado al final de `index.html`.
- [ ] Generar los mockups reales a partir de los prompts en `docs/mockups-prompts.md` y reemplazar las imágenes de referencia en `images/` por las definitivas.

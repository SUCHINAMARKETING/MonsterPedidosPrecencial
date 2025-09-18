# Pedido por cliente (HTML único)

App simple y robusta para armar pedidos por cliente sin backend.

## Cómo usar
- Abre `index.html` (doble clic). 
- Escribe el **nombre del cliente**.
- Marca productos, ajusta **cantidades** y revisa el **total**.
- Usa **Copiar pedido** para pegarlo en WhatsApp/Email u otro canal.
- Usa **Limpiar pedido** para reiniciar.

> Los productos se editan en el arreglo `PRODUCTOS` dentro del `<script>`.

## Publicarla en GitHub Pages
1. Crea un repo nuevo en GitHub (público), por ejemplo: `pedido-cliente`.
2. Sube `index.html` y este `README.md` a la rama `main`.
3. Ve a **Settings → Pages**:
   - **Build and deployment** → *Source*: **Deploy from a branch**.
   - *Branch*: `main` / **root**. Guarda.
4. La página quedará en: `https://TU_USUARIO.github.io/pedido-cliente/`

### Tip opcional
- Si algún día agregas carpetas con nombres que comienzan con `_`, añade un archivo vacío llamado `.nojekyll` para evitar que GitHub Pages las ignore.

## Estructura mínima
```
pedido-cliente/
├── index.html
└── README.md
```

## Licencia
MIT — úsalo libremente, se agradecen mejoras y PRs.

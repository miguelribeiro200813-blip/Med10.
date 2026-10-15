# MED10 — Ótica (loja online)

Site em HTML único (`index.html`), sem build e sem dependências.

## Configuração (topo do `<script>` em index.html)
- `BRAND` — nome da marca
- `WHATSAPP_NUMBER` — troque `55XXXXXXXXXXX` pelo número real (DDI+DDD+número)
- `PRODUCTS` — catálogo de produtos (nome, preço, cores, estoque...)
- `services` — pontos de integração (pedidos, pagamento, atendimento, devoluções, rastreio). Hoje são simulados. Conectar Mercado Pago/Stripe/Asaas em `services.pay()` via backend; nunca coloque chaves secretas no frontend.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub e envie estes arquivos.
2. Settings → Pages → Source: *Deploy from a branch* → branch `main`, pasta `/ (root)` → Save.
3. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Imagens
- `imagens/logo-med10.jpeg` — logo original da MED10 (o site usa uma versão vetorial recriada; substitua pelo arquivo original sem corte quando tiver).
- `imagens/referencias/` — prints de referência de design (de outras marcas). Não use em produção.
- Para usar fotos reais dos óculos, coloque em `imagens/` e referencie com `<img src="imagens/arquivo.jpg">`.

# LP Vibe Render — Upsell

Página de upsell pós-compra do Vibe Render (oferta: desconto no plano anual do RenderLAB, revelada só na VSL).

- **VSL**: VTurb `vid-6a2b62663244f7b854ac0c24` (vertical, 400px)
- **Revelação do pitch**: bloco de oferta + botão aparecem aos **90s de vídeo real** (`window.CONFIG.mostrarEm`)
- **Checkout**: https://buy.stripe.com/4gM28r0vr8S7cZ62iheIw0k (`window.CONFIG.botaoLink`)
- **Pixel Meta**: 2428536680685666 (PageView + evento custom `UpsellPitchVisto` no pitch)
- `noindex` ativo — página não deve ser indexada

Deploy: GitHub + Cloudflare Pages (push na main → deploy automático em ~30s).
Domínio: viberenderup.montani3d.com.br

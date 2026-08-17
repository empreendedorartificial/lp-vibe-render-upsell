# Copy — link de recusa + página de inscrição confirmada (Vibe Render)

**Problema que isso resolve (Slack, 15–17/08):** quem compra o Vibe Render cai na página de upsell
do plano anual do RenderLab e **não tem como sair**. A página diz "não feche nem atualize" e não
oferece saída, então quem não quer o anual acha que ficou sem o curso. Um comprador escreveu pro
suporte: *"como entro nas aulas do curso? Eu não vou comprar o anual só o mensal porém a página do
site tá me obrigando, e não consegui dar início ao curso"* — e a Nathalia disse que não é o primeiro.

Duas peças: o **link de recusa** na página de upsell e a **página de confirmação** que recebe quem
clica nele.

---

## 1. Link de recusa (na página de upsell, abaixo do botão de compra)

Discreto, mas visível — texto sublinhado, cinza, sem cara de botão. O objetivo não é esconder: é
não competir com o CTA.

> Não quero essa oferta agora — quero ir direto pras minhas aulas

Alternativas, se preferir mais curto:

> Seguir sem a oferta e acessar meu curso
> Agora não, quero começar meu curso

⚠️ **Não usar isca de culpa** ("não, prefiro continuar amador", "abro mão de economizar"). O
comprador acabou de pagar; humilhar quem recusa vira reclamação no suporte e reembolso.

---

## 2. Página de inscrição confirmada

### Topo (barra verde ou selo)

> ✓ Compra confirmada

### Título

> Pronto! Sua inscrição no *Vibe Render* está confirmada

### Subtítulo

> Você já é aluno. Agora é só entrar na área de aulas e começar.

### Bloco: como acessar (3 passos numerados)

> **1. Procure o e-mail da Hotmart**
> Ele chega em poucos minutos com o título **"Seu acesso chegou"**. É por ele que você entra na
> área de aulas.
>
> **2. Crie sua senha**
> No primeiro acesso a Hotmart pede pra você criar uma senha. Use o mesmo e-mail que você usou na
> compra.
>
> **3. Comece pela primeira aula**
> As aulas ficam liberadas na ordem certa — é só seguir de cima pra baixo.

### Aviso (caixa de atenção)

> 📩 Não achou o e-mail? Olhe no **spam** e na aba **Promoções**. Ele costuma cair lá.

### Suporte

> Se em 1 hora o acesso não tiver chegado, chama a gente que a gente reenvia na hora.
> [Falar com o suporte no WhatsApp]

### Rodapé — a linha que resolve a reclamação

> Pode fechar esta página com segurança. Sua compra está registrada e seu acesso não depende dela.

---

## 3. Bloco opcional: segunda chance da oferta

Se quiser recuperar parte de quem recusou, entra **no fim da página** — depois das instruções de
acesso, nunca antes. Quem chegou aqui já disse não uma vez; a página é de acolhimento, não de
segundo pitch.

> **Mudou de ideia?**
> A condição do plano anual que você acabou de ver continua disponível por 24 horas na sua conta.
> [Ver a oferta de novo]

⚠️ Só usar se o prazo for verdade e o link realmente funcionar depois. Prazo inventado nessa
página queima o suporte, porque quem volta em 23h e não consegue vai reclamar.

---

## Notas de implementação (pro João)

- A página não precisa de vídeo, contagem regressiva nem pressão. O trabalho dela é: confirmar,
  ensinar a entrar e liberar a pessoa.
- **Sem `noindex`?** Melhor manter `noindex,nofollow` como as outras do funil.
- Se a mesma estrutura for usada no upsell do RenderLab (`lp-renderlab-upsell`), trocar o passo a
  passo: lá o acesso é a própria plataforma (`app.renderlab.club`), não a Hotmart.
- O evento de conversão do Google Ads que hoje dispara na página de upsell (é ela que serve de
  página de obrigado do Vibe) **precisa continuar disparando** pra quem recusa — senão a compra
  some do relatório de conversão. Conferir onde o snippet vai ficar.

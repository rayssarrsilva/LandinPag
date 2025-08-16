# LandingPag — Landing Page de Lançamento focada em conversão

**Objetivo:** entregar uma landing page **enxuta e direta**, com **FAQ para quebrar objeções** e **checkout seguro via Stripe**, reduzindo fricção e aumentando conversão.

🔗 **Demo:** https://rayssarrsilva.github.io/LandinPag/

---

## 🧩 Problema
Muitas landings perdem usuários por **textos longos, dúvidas não respondidas** e **processos de pagamento confusos** — o que eleva o abandono.

## 💡 Motivação
Construir uma landing que:
- **Responde dúvidas essenciais** (FAQ) **antes** do checkout;
- **Vai direto ao ponto** (sem “scroll infinito”);
- **Facilita o pagamento** com uma plataforma **confiável e simples** (Stripe).

## ✅ Solução
- **FAQ** visível e objetivo para remover objeções comuns;
- **CTA claro** (acesso ao produto sem ruído);
- **Stripe Checkout** para compra rápida e segura;
- **Animações on-scroll** sutis (percepção de qualidade sem poluir).

---

## 🔎 Principais funcionalidades
- **FAQ** para objeções e dúvidas rápidas;
- **Páginas de feedback** pós-checkout: `obrigado.html` e `cancelado.html`;
- **CTA** em destaque, copy direta;
- **Layout responsivo** (mobile-first);
- **Animações on-scroll** (AOS).

---

## 🧱 Tecnologias & Decisões (por que usei)
- **HTML5/CSS3/Tailwind**: estrutura semântica, estilização rápida e responsiva;
- **JavaScript**: animações e integração com Stripe (client-side);
- **AOS**: animação on-scroll leve e declarativa;
- **Stripe Checkout**: experiência de pagamento testada e segura (modo dev e live);
- **Formspree**: envio de formulário sem backend (estático);
- **GitHub Pages**: deploy simples, estável e gratuito.

---

## 📈 SEO & Acessibilidade aplicados
- `lang="pt-BR"`, `meta description`, **Open Graph** e **Twitter Cards**;
- `title` com palavras-chave e **canonical**;
- Headings hierárquicos (1 `<h1>`; seções com `<h2>`);
- Botões/links com texto claro; imagens com `alt`;
- Scripts não críticos com `defer` e `preconnect` para CDNs.

> **Schema.org (opcional):** `FAQPage` e `Product/Offer` podem ser adicionados para rich results.

---

## 🛠️ Como rodar localmente
Projeto estático.  
**Opção 1 (Python):**
```bash
python -m http.server 5500
# abra http://localhost:5500

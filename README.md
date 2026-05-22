# Super Mario Galaxy — Landing Page Interativa

Uma página de apresentação moderna e altamente visual inspirada em *Super Mario Galaxy*. Ideal para portfólios, demonstrações criativas e projetos front-end que valorizam animações, layout responsivo e experiências ricas em mídia.

**Destaques:**
- **Visual imersivo:** efeito `starfield`, animações de entrada e transições suaves.
- **Seções planejadas:** hero, navegação, personagens, trailers, marquee e contador animado (especificações em `docs/`).
- **Assets otimizados:** imagens e vídeos prontos para demonstração em `assets/`.
- **Responsivo e acessível:** pensado para funcionar bem em desktop e mobile.

**Demo rápida**
- Abra [index.html](index.html) no navegador para ver a versão local.
- Para servir localmente (recomendado):

```
# Servidor Python (porta 8000)
python -m http.server 8000

# Ou usando http-server (Node.js)
npx http-server . -p 8000
```

**Por que este projeto é interessante?**
- Excelente vitrine para habilidades em animação CSS/JS, performance de front-end e concepção visual.
- Estrutura modular com especificações por seção em `docs/`, facilitando iterações e entregas.
- Código simples de entender e rápido para adaptar a novos temas ou marcas.

**Estrutura do projeto**
- `index.html` — página principal
- `css/styles.css` — estilos principais
- `js/script.js`, `js/scroll-animations.js` — lógica e animações
- `assets/` — imagens, vídeos e outros recursos
- `docs/` — especificações técnicas por seção (ex.: [hero-section-spec](docs/hero-section-spec.md))
- `prints/` — imagens de demonstração

**Como contribuir**
1. Faça um fork e crie uma branch com sua feature: `git checkout -b feature/nome-da-feature`.
2. Abra um pull request com descrição clara das mudanças.

**Próximos passos sugeridos**
- Adicionar um deploy estático (GitHub Pages / Netlify) para demo pública.
- Incluir testes simples de acessibilidade e performance.

Se quiser, eu posso também: atualizar o `index.html` com um CTA para demo, criar um `LICENSE` (MIT) e preparar o repositório para deploy contínuo.

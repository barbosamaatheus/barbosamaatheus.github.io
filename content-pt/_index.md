---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Baixar CV
        url: http://lattes.cnpq.br/0987601661627331
      headings:
        about: "Resumo Profissional"
        education: "Formação"
        interests: "Interesses"
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: game
    content:
      title: ""
      text: |-
        <div style="display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:1rem;padding:1.25rem 1.5rem;border-radius:1rem;background:linear-gradient(135deg,#2d2450,#4a2f7a);color:#f6f1ff;box-shadow:0 6px 0 #0d0a18">
          <div style="flex:1 1 260px">
            <div style="font-size:1.25rem;font-weight:800">🎮 Prefere explorar?</div>
            <div style="opacity:.85;margin-top:.25rem">Passeie pela Merge Village, uma vila em pixel art desenhada como um histórico do git, e descubra minha pesquisa, artigos, projetos e palestras.</div>
          </div>
          <a href="game/" style="display:inline-block;padding:.8rem 1.2rem;border-radius:.75rem;background:#ffcf4a;color:#2a1d00;font-weight:800;text-decoration:none;box-shadow:0 4px 0 #c99a1d">▶ Jogar a versão gamificada</a>
        </div>
    design:
      columns: "1"
      spacing:
        padding: ["2rem", 0, "1rem", 0]
  - block: markdown
    content:
      title: "📚 Minha Pesquisa"
      subtitle: ""
      text: |-
        Sou pesquisador no grupo SPG do CIn UFPE. Investigo e desenvolvo ferramentas e técnicas para melhorar a qualidade e a produtividade no desenvolvimento de software, especialmente reduzindo esforço desnecessário e frustração no trabalho de pessoas desenvolvedoras.

        Meus principais interesses de pesquisa estão nos seguintes temas e na integração entre eles: ferramentas avançadas (semânticas) de merge de código, conflitos de integração de código, integração e entrega contínuas, modularidade de software, linhas de produto de software e refatoração.

        Entre em contato para colaborarmos 😃
    design:
      columns: "1"
  - block: collection
    id: papers
    content:
      title: Publicações em Destaque
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3
  - block: collection
    content:
      title: Publicações Recentes
      text: ""
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: events-and-talks
    content:
      title: Eventos e Palestras
      filters:
        folders:
          - events
    design:
      view: card
---

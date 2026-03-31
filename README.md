# Projeto: Site Github (Landing Page)

## Descrição

Projeto simples de landing page estática inspirado na interface e conceitos de Git/GitHub.

- HTML _sem servidor_ (puro client-side)
- CSS com design moderno, minimalista e responsivo
- Estrutura simples para aprendizado de versionamento e estilo

## Tecnologias

- HTML5 (`index.html`)
- CSS3 (`style.css`)
- JavaScript simples (`script.js`, caso seja implementado no futuro)

## Estrutura de arquivos

- `index.html`: conteúdo principal e layout da página
- `style.css`: tema moderno, tipografia, header/banner, cards e footer
- `script.js`: arquivo reservado para comportamento JS (atualmente pode estar vazio)
- `restrito/info.txt`: exemplo de conteúdo dentro de subpasta restrita.

## Componentes implementados

### Header
- `.site-header`, `.header-top`, `.header-banner`
- logo, navegação, campo de busca, botão de login, CTA
- responsividade para telas menores

### Corpo
- título principal e descrição com texto didático
- lista de funcionalidades (Pull Requests, Issues, CI)
- tabela de dados de exemplo (Repositório/PR/Issue)

### Footer
- `.site-footer` com marca, links, suporte e copyright
- design coerente com paleta de cores e tipografia

## Modelagem de dados

Projeto não possui backend nem persistência de dados.

- Os dados exibidos estão definidos diretamente no HTML
- Para escalar, API REST ou arquivo JSON poderiam ser integrados

## Extensões e bibliotecas

- Não há dependência externa (sem `npm`, sem framework)
- Pode usar futuras integrações:
  - `font-family`: Inter/Segoe UI/Roboto via CSS local, ou Google Fonts
  - Bibliotecas JS mínimas: `Alpine.js` / `Vanilla JS` / `Vue` (opcional)

## Boas práticas aplicadas

- Uso de `:root` para variáveis CSS (tema consistente)
- Reset básico global (`* { box-sizing: border-box; }`)
- Layout fluido com `width: min(1120px, 94vw)`
- Flexbox e grid para alinhamento responsivo
- Acessibilidade básica (`aria-label` em busca)

## Como usar

1. Clonar este repositório
2. Abrir `index.html` no navegador

## Próximos passos sugeridos

- Adicionar interações em `script.js` (busca, modais, scroll suave)
- Integrar API pública de GitHub para exibir repositórios reais
- Melhorar acessibilidade (WCAG 2.1)
- Incluir testes básicos e CI com `GitHub Actions`

---

### Contato

- Projeto de estudo: versão inicial fornecida em `D:\Leticya Laura\UC15\git\versionamentoVscode`
- Autor: `Leticya Laura` (usuária)

# Observações - João Pedro

## Análise do Site Atual (acbrasil.org.br)

### O que funciona
- Navegação principal clara: Home, Quem somos, O que fazemos, Artigos, Contato, Associe-se
- Paleta de cores consistente (azul #2579e8, amarelo #FFCA08, azul marinho #19176d)
- Tipografia unificada com Readex Pro
- Integração com redes sociais (LinkedIn, YouTube)
- Sistema de login/autenticação para membros
- Responsividade básica com menu hamburger no mobile

### Problemas identificados
1. **Homepage vazia** - não tem destaque para eventos nem conteúdo dinâmico na entrada
2. **Página de contato fraca** - não existe uma página de contato bem estruturada com formulário adequado
3. **Sem dados financeiros** - não tem quadro RSS com cotações da bolsa, algo que faz sentido para o público-alvo (conselheiros, investidores)
4. **Código poluído** - CSS inline excessivo, muitas redundâncias, difícil de manter
5. **SEO fraco** - falta de tags semânticas (h1, h2 adequados), meta descriptions fracas
6. **Eventos sem destaque** - sendo a principal atividade da associação, deveria ser o primeiro item visível
7. **Blog sem visibilidade** - artigos existem mas não são promovidos na homepage

---

## Brainstorm

### Objetivo do redesign
1. Tornar o site mais moderno, intuitivo e profissional
2. Dar destaque aos eventos (principal atividade da ACBrasil)
3. Facilitar o acesso ao conteúdo do blog/newsletter
4. Atrair novos associados com CTAs claros
5. Incluir dados financeiros relevantes (RSS da bolsa)

### Público-alvo
1. Conselheiros de administração e consultivos
2. Donos e gestores de PMEs
3. Executivos e investidores
4. Estudantes de administração e governança
5. Potenciais novos associados

### Funcionalidades prioritárias
1. **Seção de eventos** - calendário visual, próximos eventos em destaque na home
2. **Blog/Newsletter** - cards com publicações recentes, sistema de categorias
3. **Quadro financeiro** - ticker com cotações via API da bolsa de valores
4. **Área de membros** - login, conteúdo exclusivo, perfil
5. **Formulário de contato** - completo, com mapa e informações de contato
6. **CTA "Associe-se"** - seção chamativa na homepage

### Diferenciais do novo site
1. Animações e transições suaves nos elementos (hover, scroll)
2. Design responsivo de verdade (mobile-first)
3. Homepage rica com conteúdo dinâmico
4. Dados financeiros em tempo real
5. Navegação simplificada e intuitiva

---

## Mindmap - Estrutura do Site

```
                        ACBrasil (Redesign)
                              |
    ┌──────────┬──────────┬───┴────┬──────────┬──────────┬──────────┐
    |          |          |        |          |          |          |
   Home    Quem Somos  Eventos   Blog     Mercado   Membros    Contato
    |          |          |        |          |          |          |
    |      - História  - Calendário - Artigos - Ticker  - Login   - Formulário
    |      - Missão    - Próximos  - Newsletter  Bolsa  - Perfil  - Mapa
    |      - Equipe    - Passados  - Categorias - RSS   - Área    - Redes
    |      - Valores   - Inscrição - Busca      API     exclusiva   sociais
    |                                                              - Email
    |
    ├── Hero/Banner
    ├── Próximos Eventos (destaque)
    ├── Últimas do Blog (cards)
    ├── Ticker da Bolsa
    ├── CTA Associe-se
    └── Footer
```

---

## 5W2H

| Dimensão | Descrição |
|----------|-----------|
| **What** (O quê?) | Redesign completo do site institucional da ACBrasil - Associação de Conselheiros do Brasil |
| **Why** (Por quê?) | Site atual está desatualizado, com homepage vazia, sem destaque para eventos, sem dados financeiros e código difícil de manter |
| **Who** (Quem?) | Grupo de 7 alunos do curso de front-end: Arthur, João Pedro, Luiz Fernando, Pedro Soares, Pedro Becker, Vinícius Lima e Antonio Damasceno |
| **When** (Quando?) | 1º semestre de 2026 - entrega da AP1 (documentação) seguida de implementação |
| **Where** (Onde?) | Site responsivo (desktop, tablet e mobile), hospedagem a definir |
| **How** (Como?) | 1. Documentação (brainstorm, mindmap, 5W2H, doc de visão, Figma) → 2. Desenvolvimento front-end → 3. Testes → 4. Publicação |
| **How much** (Quanto?) | Custo zero - projeto acadêmico. Ferramentas gratuitas (VS Code, GitHub, Figma free) |

---

## Proposta de Tecnologias
- **HTML5 + CSS3 + JavaScript** (adequado ao nível da turma)
- **GitHub** para versionamento
- **Figma** para prototipagem
- **API financeira** para dados da bolsa (ex: Alpha Vantage, Yahoo Finance)

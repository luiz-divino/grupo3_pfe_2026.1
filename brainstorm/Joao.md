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

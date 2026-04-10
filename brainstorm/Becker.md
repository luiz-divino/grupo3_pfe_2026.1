# Anotações Pedro Becker

# Análise da página ACB BRASIL
  - **Link da página** [https://acbrasil.org.br/cms/]

  # Anotações Pedro Becker

# Brainstorm — Análise e Reformulação do Site ACB Brasil

## 1. Análise do Estado Atual

- **PÁGINA:** [https://acbrasil.org.br/cms/](https://acbrasil.org.br/cms/)

### 🏠 Home: Problemas identificados

#### Interface e Layout

- **Bug de string visível:** O shortcode `[acb-newsletter]` aparece renderizado como texto 
estático na seção de associação, sem nenhuma funcionalidade aparente.
- **String de menu exposta:** O elemento `[menu-associado]` aparece visível na navegação 
principal em desktop, sendo um código interno que deveria estar oculto.
- **Ausência de hierarquia visual:** A página inicial não possui uma hierarquia clara de 
conteúdo, dificultando que o usuário identifique rapidamente o propósito da associação.

#### Funcionalidade e Navegação

- **Links com erro 404:** O botão "Mais artigos" da seção de artigos recentes direciona para página não encontrada.
- **Botão "Seja um associado":** Redireciona para `/associe-se-a-acb/` sem o prefixo `/cms/`, 
quebrando a navegação dentro do ambiente CMS.
- **CTA fraco:** O banner de webinars leva o usuário para fora do site (`/webinar/`) sem 
nenhum aviso, prejudicando a retenção.

#### Responsividade

- **Navbar quebrada em mobile:** O menu de navegação não se adapta corretamente a viewports 
menores, causando sobreposição de elementos.
- **Imagens sem dimensões responsivas:** O banner de webinars usa dimensões fixas 
(800x133px), causando distorção em telas menores.

---

### 👥 Quem Somos: Problemas identificados

#### Interface e Layout

- **Ausência de elementos visuais:** A página não apresenta fotos, ícones ou ilustrações 
que reforcem a identidade da associação, tornando o conteúdo pouco atrativo.
- **Texto denso sem formatação:** O texto institucional é apresentado em bloco contínuo, 
sem uso de subtítulos, bullet points ou destaques.

#### Conteúdo

- **Falta de informações sobre fundadores/membros:** Não há apresentação dos conselheiros 
ou liderança da ACB, reduzindo a credibilidade institucional.

---

### 📋 O Que Fazemos: Problemas identificados

#### Interface e Layout

- **Falta de cards ou seções visuais:** Os serviços/atividades não são apresentados em 
formato de cards, dificultando a leitura e comparação.
- **Ausência de CTAs claros:** Não há botões de ação convidando o usuário a se engajar 
com as atividades descritas.

---

### 📰 Artigos: Problemas identificados

#### Funcionalidade

- **Ausência de filtros por categoria:** O usuário não consegue filtrar artigos por tema 
ou data de forma intuitiva.
- **Paginação pouco visível:** A navegação entre páginas de artigos não é destacada 
visualmente.

#### Layout

- **Cards de artigos sem padronização:** Os cards variam em altura e espaçamento, 
causando inconsistência visual na listagem.

---

### 📞 Contato: Problemas identificados

#### Funcionalidade

- **Formulário sem validação visual:** Não há feedback visual claro ao usuário sobre 
campos obrigatórios ou erros de preenchimento.

---

## 2. Propostas de Melhoria

- Corrigir todos os links quebrados, adicionando o prefixo `/cms/` onde necessário
- Remover strings internas visíveis (`[menu-associado]`, `[acb-newsletter]`)
- Implementar design responsivo em todas as páginas
- Padronizar os cards de artigos com altura fixa e truncamento de texto
- Adicionar filtros de categoria na página de artigos
- Criar seção "Nossa Equipe" na página Quem Somos
- Substituir o banner estático de webinars por um componente dinâmico
- Implementar paleta de cores oficial: branco, azul, amarelo e cinza
- Adicionar validação e feedback no formulário de contato
- Melhorar hierarquia visual da Home com seções bem definidas
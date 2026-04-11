# Visão geral do site
A proposta é reposicionar o site da ACB como uma plataforma que combina três funções principais:

* Institucional: transmitir credibilidade, clareza e posicionamento
* Conteúdo: consolidar autoridade intelectual por meio de artigos e newsletter
* Rede: fortalecer a conexão entre conselheiros, executivos e empresas

O site deixa de ser apenas informativo e passa a operar como um hub ativo.

# Estrutura do site

Menu principal:

* Home
* Quem Somos
* Eventos
* Blog / Newsletter
* Mercado
* Membros
* Contato

A principal mudança é tratar “Membros” como área estratégica (não apenas listagem) e “Blog” como produto editorial estruturado.

# Home

A home deve funcionar como ponto de entrada dinâmico e orientar rapidamente o usuário.

## Hero
* Headline clara com proposta de valor
* Subtexto curto e direto
* Dois CTAs principais:

  * Ver eventos
  * Explorar newsletter

## Carrossel de conteúdo
* Exibição dos 5 conteúdos mais recentes
* Mistura de artigos, newsletters e análises
* Formato mais próximo de revista do que blog tradicional

## Agenda de eventos
* Lista dos próximos eventos
* Cards com:

  * data
  * local
  * tipo (online/presencial)
* Foco em facilitar a inscrição

## Mercado
* Exibição de:

  * IBOV
  * dólar
  * SELIC
* Indicadores com variação percentual
* Mini gráficos
* Feed RSS com notícias econômicas

## Bloco institucional
* Explicação breve da ACB
* Benefícios objetivos
* Depoimentos curtos de membros

## Redes sociais
* Feed integrado de forma leve
* Uso mais como validação institucional do que conteúdo principal

# Blog / Newsletter

Essa área deve funcionar como um produto editorial estruturado.

## Estrutura
* Destaque principal da semana
* Feed de conteúdo em grid
* Cards com:

  * autor
  * resumo
  * categoria

## Categorias
* Governança
* ESG
* Compliance
* Mercado
* PMEs
* Opinião

## Publicação por membros
* Editor simples para membros escreverem
* Fluxo com moderação antes da publicação
* Garantia de qualidade editorial

## Newsletter
* Envio em formato de digest semanal
* Arquivo acessível dentro do site
* Destaques selecionados
* CTA recorrente para assinatura

## Autor
* Nome visível em todos os conteúdos
* Mini bio
* Área de atuação

# Eventos
Eventos devem ser tratados como eixo central do site.

## Listagem
* Grid de eventos com cards
* Informações:

  * data
  * local
  * tipo

## Página de evento
* Descrição clara
* Agenda
* Botão de inscrição

## Evoluções futuras
* Filtros por data, tipo e localização
* Histórico de eventos

# Mercado

Área dedicada para dados financeiros e contexto econômico.

## Dashboard
* IBOV, dólar, SELIC
* Variação percentual
* Atualização via API

APIs sugeridas:

* Brapi.dev
* Yahoo Finance

## Feed de notícias
* Integração com RSS de economia
* Atualização automática

## Requisitos
* Carregamento rápido
* Fallback com última cotação caso a API falhe
* Interface de leitura rápida

# Membros
Área estratégica com evolução em fases.

## Fase inicial
* Página pública com proposta de valor
* Benefícios da associação
* Formulário de pré-cadastro (“em breve”)

## Estrutura futura

### Login
* Acesso individual

### Painel do membro
* Eventos exclusivos
* Newsletters completas
* Materiais e templates
* Networking

### Diretório
* Perfis com:

  * nome
  * empresa
  * especialidade

# Contato
Área funcional e direta.

## Canais
* Email institucional
* Contato para eventos e parcerias
* WhatsApp

## Formulário
* Nome
* Email
* Empresa
* Assunto
* Mensagem

## Lógica
* Roteamento por tipo de assunto
* Otimização do atendimento

## Experiência
* Confirmação automática de envio
* SLA definido (ex: até 48 horas)

# Formulários e e-mails
Devem ser tratados como parte da experiência do produto.

## Melhorias
* Templates com identidade visual da ACB
* Comunicação clara e objetiva
* Confirmação automática

## Casos principais
* Contato
* Inscrição em eventos
* Newsletter com double opt-in

# Visual

## Paleta
* Azul escuro como base institucional
* Amarelo como destaque
* Cinza e preto como suporte

## Tipografia
* Títulos: Playfair Display
* Texto: DM Sans

## Direção
* Estética inspirada em jornal econômico
* Uso consistente de espaçamento
* Hierarquia clara
* Evitar excesso de elementos visuais

# Estrutura técnica

## Base
* Mobile first
* Totalmente responsivo

## Performance
* Carregamento rápido
* Evitar scripts desnecessários

## SEO
* Estrutura semântica bem definida
* Conteúdo indexável (principalmente blog)

## Acessibilidade
* Contraste adequado
* Navegação simples e clara
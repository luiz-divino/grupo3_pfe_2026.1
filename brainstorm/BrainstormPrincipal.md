# Relatório de Análise e Redesign - ACBrasil

## 1. Problemas Identificados no Site

### [Geral e Arquitetura](https://acbrasil.org.br/cms/)
#### Problemas principais
* **Arquitetura da Informação Confusa:** O feed principal mistura artigos de opinião extensos com informativos institucionais sem diferenciação visual clara.
* **Código Poluído:** Presença de CSS inline excessivo, muitas redundâncias e dificuldade de manutenção.
* **SEO e Semântica Fracos:** Uso excessivo de tags genéricas (`<div>`) e falta de tags semânticas como `h1` e `h2` adequados.
* **Interface Datada:** O layout não utiliza padrões modernos de UI, como Grid/Cards, tornando a leitura densa e cansativa.
* **Desperdício de Conteúdo Multimídia:** Vídeos, videocasts e webinars não estão integrados na página inicial.
* **Paginação Obsoleta:** A navegação entre publicações exige o recarregamento total da página, prejudicando a UX.

### [Página Inicial](https://acbrasil.org.br/cms/)
#### Problemas principais
* **Strings de Código Expostas:** Os elementos `[menu-associado]` e `[acb-newsletter]` aparecem como texto estático sem funcionalidade.
* **Ausência de Hierarquia Visual:** Dificuldade para o usuário identificar rapidamente o propósito da associação.
* **Links com Erro 404:** O botão "Mais artigos" e o banner de webinars direcionam para páginas não encontradas.
* **Sobreposição de Elementos:** Componentes visuais sobrepostos no canto inferior direito prejudicam a estética e o funcionamento.
* **Falhas de Responsividade:** Transbordamento lateral, desalinhamento de seções e navbar quebrada em dispositivos mobile.

### [Quem Somos](https://acbrasil.org.br/cms/quem-somos/)
#### Problemas principais
* **Texto Denso sem Formatação:** Conteúdo institucional apresentado em bloco contínuo, sem uso de subtítulos ou bullet points.
* **Ausência de Elementos Visuais:** Falta de fotos, ícones ou ilustrações que reforcem a identidade da associação.
* **Falta de Informações de Liderança:** Não há apresentação dos conselheiros ou membros da ACB, reduzindo a credibilidade.
* **Erros de Renderização:** Falha ao renderizar o logo da empresa e desalinhamento no menu de navegação.

### [O Que Fazemos](https://acbrasil.org.br/cms/o-que-fazemos/)
#### Problemas principais
* **Falta de Cards ou Seções Visuais:** Dificuldade de compreensão das atividades por não estarem em formatos comparativos ou organizados.
* **Ausência de CTAs Claros:** Falta de botões de ação convidando o usuário ao engajamento.
* **Cores e Contraste:** Uso mal planejado de cores no formulário, dificultando a identificação dos campos de entrada.

### [Artigos](https://acbrasil.org.br/cms/c/artigos/)
#### Problemas principais
* **Cards sem Padronização:** Variação em altura e espaçamento dos cards, causando inconsistência visual.
* **Ausência de Filtros:** O usuário não consegue filtrar publicações por tema ou categoria de forma intuitiva.

---

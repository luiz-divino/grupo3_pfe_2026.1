# Brainstorm de Análise: Site ACB Brasil - Pedro Soares

### 1. Diagnóstico de Bugs e Erros
* *Falhas de Renderização de Shortcodes:* Foram detetados textos estáticos como [adc-newsletter] e [acb-contatos] no frontend. Isso indica que alguma funcionalidade não está sendo processada de forma correta, resultando em perda de funcionalidade.
* *Integridade de Rotas (Erro 404):* Existem falhas críticas de endereçamento em botões de conversão e navegação (Webinars, Mais Artigos, Seção de Associados e Imagens de Fundadores).
* *Conflitos de CSS e Z-Index:* Elementos no canto inferior direito apresentam sobreposição. No separador "O Que Fazemos", o menu de navegação está sobrepondo os títulos das seções por falta de ajuste.
* *Lógica de Exibição do Menu:* A string de classe/ID menu-associado está sendo impressa no documento em resoluções de desktop, quando deveria apareceer apenas no breakpoint mobile.

### 2. Infraestrutura e Responsividade
* *Breakpoints Inconsistentes:* O layout apresenta quebra lateral e desalinhamento em diferentes resoluções.
* *Assets Quebrados:* Erro na renderização do logótipo institucional na página "Quem Somos".


##  Perspetiva B: Foco em Experiência do usuario e Design
analisando da perspectiva do usuario (Eu)

### 1. Atritos na Jornada e Usabilidade
* *Caminhos Sem Saída:* A experiência de navegação é interrompida constantemente por botões que levam a páginas inexistentes, o que prejudica a credibilidade da instituição.
* *Problemas de Contraste e Legibilidade:* Nos formulários (Contacto e O Que Fazemos), a paleta de cores dificulta a identificação dos campos de input, tornando o preenchimento cansativo e pouco intuitivo.
* *Poluição Visual e Hierarquia:* A sobreposição de componentes e o desalinhamento de títulos criam um ruído visual que impede uma leitura fluida da proposta de valor da ACB.
* *Interface Mobile Instável:* O menu hambúrguer e a adaptação para telas pequenas estão inconsistentes, dificultando o acesso à informação via smartphone.

### 2. Estética e Profissionalismo
* *Ruído Técnico:* A exibição de termos técnicos e códigos (como os nomes dos menus ) no meio do design passa uma imagem de site "em construção" ou mal acabado.



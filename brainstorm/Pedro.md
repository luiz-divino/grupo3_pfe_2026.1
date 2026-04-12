# Brainstorm de Análise: Site ACB Brasil - Pedro Soares

### 1. Diagnóstico de Bugs e Erros
* *Falhas de Renderização de Shortcodes:* Foram detetados textos estáticos como [adc-newsletter] e [acb-contatos] no frontend. Isso indica que alguma funcionalidade não está sendo processada de forma correta, resultando em perda de funcionalidade.
* *Integridade de Rotas (Erro 404):* Existem falhas críticas de endereçamento em botões de conversão e navegação (Webinars, Mais Artigos, Seção de Associados e Imagens de Fundadores).
* *Conflitos de CSS e Z-Index:* Elementos no canto inferior direito apresentam sobreposição. No separador "O Que Fazemos", o menu de navegação está sobrepondo os títulos das seções por falta de ajuste.
* *Lógica de Exibição do Menu:* A string de classe/ID menu-associado está sendo impressa no documento em resoluções de desktop, quando deveria apareceer apenas no breakpoint mobile.

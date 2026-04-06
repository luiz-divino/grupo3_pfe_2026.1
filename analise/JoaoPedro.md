# Análise do site ACBrasil - João Pedro

Testei o site https://acbrasil.org.br/cms/ no desktop e no celular pra anotar os problemas que encontrei em cada página.

## Página Inicial (Home)

- O texto `[menu-associado]` aparece no header como texto puro, deveria ser um menu mas não funciona no desktop
- Tem um `[adc-newsletter]` solto na tela abaixo da seção de associação, sem estilo nenhum
- O botão "Fique por dentro dos nossos webinars" leva pra uma página que não existe (erro 404)
- O botão "Mais artigos" na seção de artigos recentes também dá 404
- O botão "Seja um associado" abaixo dos artigos não funciona
- O carrossel de artigos demora pra passar e trava um pouco
- A home é basicamente só artigos, não tem destaque pra eventos que é a atividade principal deles

## Quem Somos

- O link "Faça sua associação" não funciona
- As fotos dos fundadores são clicáveis mas não levam pra lugar nenhum, parece que ia ter uma página de perfil mas nunca fizeram
- O conteúdo é ok mas poderia ter mais informações sobre a história da associação

## O Que Fazemos

- O header sobrepõe o texto no topo da página, fica por cima do conteúdo
- Tem um formulário mas o campo de telefone não valida se o número tá certo (aceita qualquer coisa)

## Artigos

- O filtro de categorias não é padronizado, não mostra todos os artigos
- A paginação no final tem um espaçamento estranho entre o texto da página atual e o seletor
- Tem um autor "Webmasterbr" que aparece em alguns artigos, não faz sentido pro visitante
- O link de email do Webmasterbr abre na mesma aba em vez de abrir o app de email numa nova aba

## Contato

- Aparece o texto `[acb-contatos]` solto na tela, igual o problema da newsletter na home
- Não tem formulário funcionando
- Não tem telefone, email nem endereço visível
- Não tem mapa
- Basicamente a página tá vazia/quebrada

## Associe-se

- Tem um espaço enorme entre o header e o conteúdo da página
- O código de conduta não consegue baixar
- Os campos de CPF, celular, data de nascimento, CEP e cidade não validam nada, aceita qualquer texto
- Não dá pra ler a política de privacidade no final do formulário

## LGPD / Proteção de Dados

- A política de privacidade não carrega
- A política de cookies também não
- Só dá pra acessar essa página pelo footer, não tem link em nenhum outro lugar

## Footer

- O link de "Home" no footer não funciona
- Faltam links organizados pra todas as páginas (tipo um sitemap)
- Tem LinkedIn e YouTube mas podia ter mais redes sociais

## Problemas gerais

- Muito CSS inline no código, tudo repetido e difícil de entender
- O site demora pra carregar por causa de tanto código desnecessário
- No celular a responsividade quebra em algumas partes, elementos ficam desalinhados
- Não tem favicon personalizado
- As meta descriptions são fracas pro SEO

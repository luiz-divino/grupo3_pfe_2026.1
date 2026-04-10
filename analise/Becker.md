# Análise do site ACBrasil - Pedro Becker

Acessei o site https://acbrasil.org.br/cms/ no desktop e no celular para mapear 
os problemas técnicos e de usabilidade encontrados em cada página.

## Página Inicial (Home)

- O shortcode `[menu-associado]` aparece visível na barra de navegação no desktop,
  sendo um código interno que nunca deveria ser exibido ao usuário final
- O shortcode `[acb-newsletter]` também aparece como texto solto na seção de 
  associação, sem renderizar nenhum componente funcional
- O botão "Fique por dentro dos nossos webinars" gera erro 404, pois aponta para 
  um domínio diferente do CMS (`/webinar/` em vez de `/cms/webinar/`)
- O botão "Mais artigos" da seção de artigos recentes também resulta em 404, 
  redirecionando para `/c/artigos/` sem o prefixo `/cms/`
- O botão "Seja um associado" na seção sobre a associação quebra a navegação pelo 
  mesmo motivo de prefixo incorreto
- A Home é dominada por artigos, sem nenhuma seção dedicada a eventos, que é uma 
  das atividades centrais da ACB
- O carrossel de artigos em destaque não possui indicadores de navegação claros, 
  dificultando a interação do usuário

## Quem Somos

- O link "Faça sua associação" no rodapé desta página está quebrado
- A página apresenta apenas texto corrido sem divisões visuais, ícones ou imagens 
  que tornem a leitura mais agradável
- Não há seção com os membros ou conselheiros da diretoria, o que reduz a 
  credibilidade institucional da página

## O Que Fazemos

- O header fixo sobrepõe o título da página ao rolar, ocultando parte do conteúdo
- As atividades da ACB são listadas sem cards, ícones ou qualquer diferenciação 
  visual entre elas
- Não há chamada para ação (CTA) ao final da página incentivando o usuário a se 
  associar ou entrar em contato

## Artigos

- O filtro por categoria não funciona de forma consistente, ocultando artigos que 
  deveriam aparecer em determinadas categorias
- A paginação apresenta espaçamento irregular entre o número da página atual e os 
  demais seletores
- Autor "Webmasterbr" aparece em vários artigos sem foto ou bio, passando 
  despercebido como um perfil genérico de sistema
- Os cards de artigos não possuem altura padronizada, causando desalinhamento 
  visual na grade

## Contato

- O shortcode `[acb-contatos]` aparece como texto solto na página, sem renderizar 
  nenhum formulário ou informação de contato
- Não há exibição de telefone, e-mail nem endereço físico da associação
- A página de contato está essencialmente vazia para o usuário final por conta do 
  bug acima, sendo crítico para a comunicação da organização

## Associe-se

- O formulário de associação não possui validação nos campos de telefone e CPF, 
  aceitando qualquer entrada sem verificação de formato
- Não há feedback visual de sucesso ou erro após o envio do formulário
- A página não explica os benefícios de ser associado antes de apresentar o 
  formulário, o que pode reduzir conversões
# 🌱 Guia de Alimentação Saudável

Pequena aplicação frontend que sugere refeições saudáveis com base no objetivo (Emagrecimento, Ganho de Massa, Manutenção).

## O que tem aqui
- index.html: interface responsiva e acessível para selecionar objetivo e refeição.
- Funcionalidades:
  - Seleção de objetivo e refeição.
  - Sugestão contextual exibida com aria-live para leitores de tela.
  - Persistência local (localStorage) para lembrar a seleção.
  - Botões de limpar e copiar sugestão.
  - Suporte a teclado (Enter / Space).
  - Fallback para usuários sem JavaScript (mensagem).

## Uso
1. Abra `index.html` em um navegador moderno.
2. Selecione um objetivo e depois a refeição para ver a sugestão.
3. Use "Limpar seleção" para resetar ou "Copiar sugestão" para copiar o texto.

## Acessibilidade e boas práticas
- aria-live é usado para anunciar mudanças do resultado.
- Botões usam `aria-pressed` para indicar o estado selecionado.
- Foco visível para navegação por teclado.
- Contraste e tamanhos adaptados para leitura.

## Contribuindo
- Sugestões de novas refeições ou melhorias de design são bem-vindas.
- Ao abrir PRs, descreva a mudança e o motivo.

## Licença
Sinta-se à vontade para usar e adaptar. Recomenda-se adicionar uma licença (ex: MIT) se for publicado.

Last Seen

Interface inicial de um jogo de perseguição urbana por GPS entre amigos.

Etapa 1 — HTML semântico
Esta versão apresenta apenas a estrutura semântica em HTML. Os dados são
fictícios e os controles de pesquisa, filtro, ordenação, edição e exclusão
ainda não possuem comportamento em JavaScript.

Entidade principal: Jogador
Cada jogador possui nickname, papel na partida, posição GPS, status de
conexão, status de prontidão e sala.

Estruturas previstas
- Cadastro de jogador com formulário semântico.
- Listagem de jogadores com pesquisa, filtros e ordenação.
- Visualização de detalhes de um jogador.
- Ações de editar e excluir preparadas na interface.
- Área reservada para o mapa com Leaflet e OpenStreetMap nas próximas etapas.

Etapa 2 — CSS, Layout e Responsividade
- Arquivo CSS externo (style.css) com identidade visual em cinza escuro e vermelho.
- Variáveis CSS para cores, tipografia e espaçamentos.
- Layout da página com CSS Grid; menu, ações e formulários com Flexbox/Grid.
- Tabela de jogadores com status em etiquetas coloridas.
- Estados de interação: hover, focus, active e campos inválidos.
- Mensagens de sucesso, erro e aviso estilizadas.
- Responsividade com Media Queries (800px e 600px); em telas pequenas a
  tabela vira uma lista de cartões.

# Descrição do Projeto
Este projeto consistiu em uma análise das despesas com marketing da empresa Y.Afisha, com o objetivo de otimizar os investimentos em publicidade. Os dados fornecidos incluíram logs do servidor com informações de acesso ao site, registros de pedidos realizados e estatísticas de despesas com marketing.


# Passo a Passo para a Realização do Projeto

## Passo 1: Preparação dos Dados
Carreguei os dados dos logs de servidor, pedidos e despesas de marketing.
Armazenei os dados em variáveis e os otimizei para análise.
Certifiquei-me de que cada coluna continha o tipo correto de dados.


## Passo 2: Análise e Cálculo de Métricas

### Produto
Determinei o número de usuários que utilizam o produto diariamente, semanalmente e mensalmente.
Calculei a quantidade de sessões por dia e o comprimento médio de cada sessão.
Analisei a frequência de retorno dos usuários.

### Vendas
Identifiquei o momento em que os usuários realizam compras.
Calculei a quantidade de pedidos feitos durante um período específico.
Determinei o volume médio de uma compra e o valor do ciclo de vida do cliente (LTV).

### Marketing
Avaliei o total de despesas com marketing, dividido por origem e ao longo do tempo.
Calculei o custo de aquisição de clientes para cada origem.
Analisei o retorno sobre o investimento (ROI).


## Passo 3: Conclusão e Recomendações
Escrevi uma conclusão baseada na análise realizada.
Recomendei aos especialistas de marketing onde investir e quanto investir, fundamentando as escolhas com base nas métricas analisadas.
Formato do Projeto


O projeto foi desenvolvido em um notebook Jupyter.
O código foi organizado em células de código e explicações de texto em células markdown.
Foi aplicada formatação adequada e utilizados cabeçalhos para facilitar a leitura e compreensão do conteúdo.


## Descrição dos Dados
Os dados utilizados no projeto estavam divididos em três tabelas:

### visits: Continha os logs do servidor com informações sobre os acessos ao site.

Uid: Identificador único do usuário.
Device: Dispositivo utilizado pelo usuário.
Start Ts: Data e hora de início da sessão.
End Ts: Data e hora de término da sessão.
Source Id: Identificador da origem do anúncio que levou o usuário ao site.


### orders: Continha dados sobre os pedidos realizados.

Uid: Identificador único do usuário que fez o pedido.
Buy Ts: Data e hora do pedido.
Revenue: Receita gerada pelo pedido.



### costs: Continha dados sobre as despesas com marketing.

source_id: Identificador da origem do anúncio.
dt: Data.
costs: Despesas relacionadas a essa origem de anúncio na data especificada.




Para quaisquer dúvidas ou esclarecimentos adicionais, entre em contato.

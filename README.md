Visão Geral
Este script foi desenvolvido para facilitar o tratamento dos dados da PNADc (Pesquisa Nacional por Amostra de Domicílios Contínua) do IBGE. Ele serve como uma base para que os usuários possam criar novas ramificações (branches) para análises distintas, seja por recortes setoriais, temporais, ou outros.

Funcionalidade
Função check.packages: Esta função verifica se os pacotes listados estão instalados. Se algum pacote não estiver instalado, ele será automaticamente instalado e carregado. No exemplo, o pacote PNADcIBGE é o principal, pois permite a extração e manipulação dos dados da PNADc.

Lista de Variáveis de Interesse: O script permite que o usuário defina quais variáveis da PNADc deseja incluir na análise por meio da lista vars. O objetivo é fornecer flexibilidade para diferentes tipos de análise, de acordo com a necessidade do estudo.

Extração de Dados: A função get_pnadc é utilizada para baixar os dados da PNADc de um ano e trimestre específicos, com a opção de adicionar rótulos (labels), deflatores, e um conjunto personalizado de variáveis.

Próximos Passos
Este script serve como um ponto de partida para a criação de novas branches no projeto. Em cada nova branch, você poderá realizar diferentes tipos de recortes e análises, como:

Recortes Setoriais: Focar em setores específicos da economia.
Recortes Temporais: Analisar dados em diferentes períodos.
Outros Recortes: Explorar diferentes dimensões e categorias de dados.
Sinta-se à vontade para modificar e expandir este script de acordo com os requisitos da sua análise.

Dependências
R versão 3.6 ou superior
Pacote PNADcIBGE: https://rpubs.com/gabriel-assuncao-ibge/pnadc
Como Usar
Clone este repositório.
Modifique a lista vars para incluir as variáveis de interesse.
Execute o script para baixar e preparar os dados para análise.
# FastAnalytics-Protheus
Projeto padrão do FAST Protheus

v1.00 - 01/01/2018 - Desenvolvimento do sistema inicial.
v1.01 - 03/05/2018 - Correção do nº de parcelas dos títulos a pagar / receber.
v2.00 - 15/05/2018 - Desenho da nova arquitetura de graphs.
v3.00 - 14/06/2018 - Adicionado módulos de Materiais / Controladoria.
v3.01 - 20/06/2018 - Corrigido um bug no cálculo do lead time do prd_fct_ProducaoRealizada.grf.
v4.00 - 21/08/2018 - Adicionado parâmetro NUMBER_MAXSIZE, para impedir valores grandes demais
                     serem carregados na plataforma.
                   - Bloco de tratamento dos dados de cada graph alterado para utilizar funções.
v4.01 - 31/08/2018 - Ajuste nas funções do bloco de tratamento. Tabelas lookup de estado/município
                     leem seus dados internamente, sem utilizar blocos do ETL, e foram exportadas.
v4.02 - 13/09/2018 - Correção no graph _Main_Materiais para chamar a execução dos graphs "Comprador"
                     e "Transportadora.
v4.03 - 26/09/2018 - Correção na função de máscara de dados (DEMO) do FAST.
v4.04 - 27/09/2018 - Ajustes nas dimensões de data do módulo de Compras (Unificação / Nomenclatura).
                   - Ajuste no dataset de Faturamento do módulo Comercial: Conexão com o grupo
                     de cliente corrigida. Alteração no graph de ComprasCarteira.
v4.05 - 21/11/2018 - Inclusão da biblioteca externa de tratamento de dados "lib.ctl".

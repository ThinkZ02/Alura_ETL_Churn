Análise de Churn da Telecom X
Este projeto tem como objetivo analisar os dados da empresa Telecom X para entender os fatores que contribuem para a evasão de clientes (churn) e fornecer insumos para reduzir essa taxa.

Descrição
A Telecom X está enfrentando um alto índice de churn, e este projeto foca na extração, tratamento e análise exploratória dos dados disponíveis em uma API pública no GitHub. A partir da análise, buscamos identificar padrões de comportamento dos clientes que possam ajudar na criação de estratégias para diminuir a evasão.

Estrutura do Projeto
Extração dos Dados:
Os dados foram extraídos diretamente de uma API hospedada no GitHub.

Transformação e Limpeza:

Expansão das colunas aninhadas em um formato tabular para facilitar a análise.

Tratamento de dados faltantes, especialmente na coluna de cobranças.

Adequação dos tipos de dados para facilitar as operações.

Análise Exploratória (EDA):

Visualização do churn por gênero, tipo de contrato, tempo de vínculo e uso do serviço telefônico.

Identificação de padrões e correlações relevantes para o problema.

Conclusões e Recomendações:

Clientes com contratos mensais têm maior propensão ao churn.

Maior tempo de relacionamento com a empresa está associado a menor evasão.

Foco estratégico recomendado para contratos anuais e aumento do tempo de vínculo.

Como Utilizar
Clone ou baixe o projeto.

Certifique-se de que as bibliotecas pandas, requests, matplotlib e seaborn estejam instaladas.

Execute o script principal para realizar a extração, limpeza dos dados e visualizar as análises.

Consulte o relatório no final do script para entender os insights obtidos.

Tecnologias Utilizadas
Python

Pandas

Requests

Matplotlib

Seaborn

Futuras Melhorias
Implementar modelagem preditiva para antecipar churn.

Explorar variáveis adicionais para entender melhor os motivos da evasão.

Desenvolver dashboards interativos para acompanhamento em tempo real.

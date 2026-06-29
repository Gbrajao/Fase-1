# Análise de Satisfação de Clientes (NPS) em E-commerce
**Objetivo do Projeto**
Este projeto tem como objetivo analisar os fatores que influenciam a satisfação dos clientes de um e-commerce por meio do Net Promoter Score (NPS). A análise busca identificar os principais motivos que levam clientes a se tornarem promotores, neutros ou detratores, gerando insights que possam apoiar a tomada de decisão e a melhoria da experiência do cliente.

**Problema de Negócio**

A satisfação do cliente é um dos principais indicadores de sucesso em um e-commerce. Um baixo nível de satisfação pode reduzir a taxa de recompra, prejudicar a reputação da marca e impactar negativamente o crescimento do negócio.

Neste projeto, foi realizada uma análise exploratória dos dados para responder às seguintes questões:

Quais fatores parecem mais críticos para a satisfação do cliente?
O que mais gera clientes detratores?
Existe algum ponto de ruptura na experiência do cliente?
Que perfil de cliente tende a apresentar maior ou menor NPS?

**Base de Dados**

A base utilizada contém informações sobre pedidos realizados em um e-commerce, incluindo variáveis relacionadas ao cliente, logística, atendimento, pedidos e satisfação.

Principais variáveis
customer_age
customer_region
customer_tenure_months
order_value
items_quantity
discount_value
payment_installments
delivery_time_days
delivery_delay_days
freight_value
delivery_attempts
customer_service_contacts
resolution_time_days
complaints_count
repeat_purchase_30d
csat_internal_score
nps_score

**Tecnologias Utilizadas**

Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
Metodologia

**O projeto foi desenvolvido seguindo as seguintes etapas:**

Carregamento da base de dados, importamos a biblioteca pandas para importação dos dados em python,Numpy para calculos matematicos Matplotlib para criação de gráficos 
Inspeção inicial dos dados, feita pelo read cvs que leu o arquivo com os dados
Limpeza dos dados (valores ausentes e duplicados), isnull e duplicated
Criação da variável categórica de NPS (Promotor, Neutro e Detrator).
Análise Exploratória dos Dados (EDA).
Análise de correlação entre as variáveis.
Identificação dos fatores mais relevantes para a satisfação dos clientes.
Geração de insights e conclusões de negócio.
Principais Resultados

**A análise identificou que os fatores com maior influência sobre o NPS foram:**

**Variável**	**Impacto**
delivery_delay_days	Forte impacto negativo
repeat_purchase_30d	Forte impacto positivo
csat_internal_score	Forte impacto positivo
complaints_count	Forte impacto negativo
customer_service_contacts	Impacto negativo
resolution_time_days	Impacto negativo

Os resultados indicam que atrasos na entrega, elevado número de reclamações e necessidade frequente de contato com o atendimento são os principais fatores associados à insatisfação dos clientes.

**Principais Insights**

Atrasos na entrega possuem a maior relação com a redução do NPS.
Clientes que realizam uma nova compra tendem a apresentar maior satisfação.
Quanto maior o número de reclamações e contatos com o atendimento, menor tende a ser o NPS.
Melhorias nos processos logísticos e no atendimento ao cliente podem aumentar significativamente a satisfação dos consumidores.

**Conclusão**

A análise demonstrou que a satisfação dos clientes está fortemente relacionada à qualidade da experiência de entrega e ao atendimento prestado após a compra.

Os resultados podem auxiliar diferentes áreas da empresa, como Logística, Atendimento, Operações e Customer Experience, na definição de estratégias voltadas à redução de reclamações, melhoria dos prazos de entrega e aumento da fidelização dos clientes.

**Autor**

**Gabriel Santos Brajão**

Projeto desenvolvido como estudo de Análise de Dados, utilizando Python para exploração de dados, geração de insights e apoio à tomada de decisão baseada em dados.
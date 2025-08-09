Análise de Churn da Telecom X
📖 Visão Geral do Projeto
Este repositório documenta a análise exploratória de dados (EDA) realizada sobre um conjunto de dados de uma empresa de telecomunicações fictícia, a Telecom X. O principal objetivo deste projeto é investigar as causas da alta taxa de evasão de clientes (churn), identificando os perfis e os principais fatores que levam os clientes a cancelar os seus serviços.

O trabalho aqui presente cobre todo o processo de ETL (Extração, Transformação e Carregamento), culminando na geração de insights que podem ser utilizados para desenvolver estratégias de retenção e na preparação dos dados para a modelagem preditiva em etapas futuras.

🎯 O Problema de Negócio
A Telecom X tem observado um aumento preocupante na sua taxa de churn, o que impacta diretamente a receita e a sustentabilidade do negócio. No entanto, a empresa não possuía uma visão clara sobre quais segmentos de clientes eram mais propensos a cancelar e porquê. Esta análise visa preencher essa lacuna, respondendo à pergunta central: "Quais são os principais fatores que impulsionam a evasão de clientes na Telecom X?"

📊 Principais Descobertas da Análise
A taxa de churn geral da empresa foi calculada em 25,7%. A análise revelou um perfil bem definido para o cliente com maior probabilidade de cancelamento.

Contratos Flexíveis são um Risco:

Clientes com contrato mensal apresentam uma taxa de churn alarmante de 42,7%.

A taxa cai para 11,3% em contratos anuais e apenas 2,8% em contratos de dois anos.

A "Zona de Perigo" é no Início:

A maioria dos cancelamentos ocorre nos primeiros meses. A mediana de tempo de contrato para um cliente que cancela é de apenas 10 meses.

O Preço e o Tipo de Serviço Importam:

Clientes com serviço de Fibra Ótica têm uma taxa de churn de 41,9%.

Clientes que cancelam pagam, em média, mais caro (mediana de $79,65 vs. $64,43 dos que permanecem).

Fatores Demográficos Relevantes:

Idosos têm uma taxa de churn de 41,7%, quase o dobro dos não idosos.

Clientes sem parceiro(a) e sem dependentes são significativamente mais propensos a cancelar.

A Falta de Suporte é Crítica:

Clientes sem serviços de Segurança Online ou Suporte Técnico apresentam uma taxa de churn superior a 41%. A contratação desses serviços reduz a taxa para cerca de 15%.

👤 Perfil do Cliente com Alto Risco de Churn
O cliente mais propenso a cancelar é idoso, não tem parceiro(a) ou dependentes, possui um contrato mensal recente, utiliza o serviço de Fibra Ótica com uma mensalidade elevada e não contratou serviços de suporte e segurança.

🛠️ Tecnologias e Bibliotecas Utilizadas
Linguagem de Programação: Python 3

Manipulação de Dados: Pandas

Visualização de Dados: Matplotlib e Seaborn

Ambiente de Análise: Jupyter Notebook

🚀 Como Executar o Projeto Localmente
Siga as instruções abaixo para configurar o ambiente e replicar a análise.

Clone este repositório:

Bash

git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Crie e ative um ambiente virtual (recomendado):

Bash

python -m venv venv
source venv/bin/activate  # Para Linux/macOS
# venv\Scripts\activate   # Para Windows
Instale as dependências necessárias:

Bash

pip install -r requirements.txt
(Nota: Crie um ficheiro requirements.txt com as bibliotecas pandas, matplotlib e seaborn)

Execute o Jupyter Notebook:
Navegue até à pasta notebooks e execute o ficheiro da análise para ver todo o processo passo a passo.

Bash

📈 Recomendações de Negócio
Com base nos insights gerados, as seguintes ações são recomendadas para a Telecom X:

Focar na Retenção de Clientes de Fibra: Criar ofertas que agreguem valor, como incluir Suporte Técnico e Segurança Online gratuitamente ou com desconto.

Incentivar Contratos de Longo Prazo: Desenvolver campanhas para migrar clientes do plano mensal para contratos anuais, oferecendo benefícios claros.

Programa de Acompanhamento Inicial: Implementar um contacto proativo nos primeiros meses de contrato para garantir a satisfação do cliente.

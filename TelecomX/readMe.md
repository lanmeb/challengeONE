# Telecom X - Análise de Evasão de Clientes

Você foi contratado como assistente de análise de dados na Telecom X e fará parte do projeto "Churn de Clientes". 
A empresa enfrenta um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes.

Seu desafio será coletar, tratar e analisar os dados, utilizando Python e suas principais bibliotecas para extrair insights valiosos.
A partir da sua análise, os demais colegas da  equipe de Data Science poderá avançar para modelos preditivos e desenvolver estratégias para reduzir a evasão.

## O que você vai praticar:

✅ Importar e manipular dados de uma API de forma eficiente.

✅ Aplicar os conceitos de ETL (Extração, Transformação e Carga) na preparação dos dados.

✅ Criar visualizações de dados estratégicas para identificar padrões e tendências.

✅ Realizar uma Análise Exploratória de Dados (EDA) e gerar um relatório com insights relevantes.

# 📚 Bibliotecas
Bibliotecas utilizadas

✅ pandas

✅ requests

✅ numpy

✅ matplotlib.pyplot

✅ seaborn


# 📌 Extração (E - Extract)

Extração de dados da API TelecomX no GitHub : [Link](https://github.com/ingridcristh/challenge2-data-science/blob/main/TelecomX_Data.json)


# 🔧 Transformação

✅ Explorar as colunas do dataset e verificar seus tipos de dados.

* Os tipos de dados mostrados foram do tipo 'object' e 'dictionary'. 
* Foi feita a Normalização dos dados.
* Foi feita a verificação de valores únicos, duplicados, nulos ou em branco.
* Transformação da coluna 'account.Charges.Total' para float.


✅ Consultar o dicionário para entender melhor os significados das variáveis.

✅ Identificar as colunas mais relevantes para a análise de evasão.
* customer.tenure – Mostra há quanto tempo o cliente está ativo. Clientes com pouco tempo de casa tendem a ter maior propensão ao cancelamento.

* account.Contract – O tipo de contrato (mensal, anual etc.) influencia diretamente na probabilidade de churn. Contratos mensais geralmente têm maior rotatividade.

* internet.TechSupport, internet.OnlineSecurity, internet.DeviceProtection – Indicam se o cliente utiliza serviços que aumentam a fidelidade. A ausência desses pode estar relacionada à saída.

* account.PaperlessBilling e account.PaymentMethod – Podem revelar perfis mais modernos ou dificuldades de pagamento, dependendo do caso.

* customer.Partner e customer.Dependents – Clientes com responsabilidades familiares tendem a ter comportamentos diferentes de evasão.

* internet.InternetService e phone.PhoneService – Se o cliente usa poucos serviços, pode ser mais propenso a sair.

# 📊 Carga e Análise (L - Load & Analysis)

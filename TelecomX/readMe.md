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
* 1. 💁 customer.tenure 
* 2. 📅 account.Contract 
* 3. 📡 internet.TechSupport, internet.OnlineSecurity, internet.DeviceProtection 
* 4. 📬 account.PaperlessBilling e account.PaymentMethod 
* 5. 👨‍👩‍👧 customer.Partner e customer.Dependents 
* 6. ☎️ internet.InternetService e phone.PhoneService 

# 📊 Carga e Análise (L - Load & Analysis)

# 📋 Relatório Final — Principais Insights sobre Evasão de Clientes (Churn)
1.  💁  Visão Geral do Churn
* A maior parte dos clientes permanece ativa, mas os padrões de cancelamento revelam riscos importantes para a empresa.

2. ⏰ Tempo de Serviço (Tenure)
* Churn é mais comum nos primeiros meses de contrato.
* Clientes com mais tempo de casa apresentam maior lealdade e retenção.

3. 📅 Tipo de Contrato
* Contratos mensais concentram os maiores percentuais de churn (acima de 40%).
* Contratos anuais/bienais têm menor evasão — indicando que comprometimento de longo prazo contribui para retenção.

4. 👨‍👩‍👧 Perfil Familiar: Parceiro(a) e Dependentes
* Clientes sem parceiro ou dependentes apresentam maior propensão ao churn.
* Laços familiares (como parceiro e filhos) demonstram efeito positivo na permanência.

5. ☎️ Serviços Contratados
* A ausência de suporte técnico, segurança online ou proteção de dispositivos está associada a maior churn.
* Clientes que usam múltiplos serviços permanecem mais tempo, reforçando o efeito da percepção de valor.

6. 💳 Forma de Pagamento e Fatura
* Fatura digital está associada a maior evasão, possivelmente ligada a perfis menos engajados.
* Cheque eletrônico apresenta maiores taxas de churn; boleto e débito automático variam conforme perfil.

## 📌 Recomendações Estratégicas
* Investir em engajamento nos primeiros meses de contrato.
* Incentivar planos de longo prazo com benefícios exclusivos.
* Oferecer pacotes de serviços agregados para aumentar a fidelização.
* Desenvolver campanhas personalizadas para perfis com risco elevado de churn.

# Case Churn - DataMaster 

## Resumo:
 Avaliação de Churn O objetivo principal deste estudo é avaliar a probabilidade de churn dos clientes de um serviço de streaming nos próximos três meses, com a intenção de implementar políticas e ações que evitem a concretização desse cenário.  O problema está dividido em duas partes:  Previsão de Churn e Análise Não Supervisionada (comportamental)

📝 Descrição:
Modelo preditivo de churn utilizando Python, Pandas, PySpark e SQL. Aplicação de machine learning para prever evasão de clientes.

🛠️ Tecnologias: Python, Scikit-learn, Pandas, SQL, PySpark

### Case:

 análise da evasão de clientes (churn) através de um modelo de classificação.

A definição do alvo (target) é guiada por alguns aspectos-chave: o cliente está inativo? Cancelou seu plano? Não ouviu música nos últimos três meses?

Para prever a saída de um cliente, é crucial observar a relação entre diferentes variáveis. Para isso, a avaliação de diversos cenários e hipóteses se torna necessária, algumas delas incluem:

Comportamento histórico do cliente: Qual foi o valor da sua assinatura e quanto música ele ouviu nos meses anteriores? Existe uma correlação com a possibilidade de churn? Características socioeconômicas: Idade, gênero, cidade e canal de aquisição influenciam a taxa de churn? 
Relação entre a quantidade ouvida no mês anterior e o churn: Existe uma conexão significativa? 
Dias desde o registro: Clientes mais novos apresentam maior propensão ao churn? 

Além de testar essas hipóteses, é fundamental compreender como os dados se comportam e se relacionam com o nosso alvo, mantendo apenas as variáveis que são realmente importantes e que influenciam o problema em estudo.

Dessa forma, dividiremos nosso processo em dois capítulos, cada um contendo as seguintes subfases:

1. Modelo de Previsão de Churn Análise superficial dos dados
2. Análise exploratória Definição das variáveis para treinamento
3. Construção do alvo (target) Seleção de Features Divisão em conjuntos de treinamento e teste
4. Treinamento do algoritmo Hiperparametrização
5. Previsão do futuro e conclusão
6. Conclusão Análise Não Supervisionada Normalização e PCA (Análise de Componentes Principais) Amostragem K-means

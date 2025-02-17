## Desafio de Ciência de Dados

### 📌 Descrição
Este desafio tem como objetivo resolver um problema de negócios atuando como um cientista de dados. O projeto deverá abranger os seguintes tópicos:

- **Extração e ingestão** da base de dados em alguma ferramenta (Google Sheets, Google Colab, Databricks, etc.).
- **Análise exploratória dos dados** para entender padrões e inconsistências.
- **Desenvolvimento de modelos**:
  - Resolver um dos dois desafios de negócio propostos com uma solução baseada em **algoritmos supervisionados**.
  - Resolver o desafio de negócio utilizando uma abordagem **não supervisionada**.
- **Justificativa das análises, premissas adotadas e métodos escolhidos**, apresentando os resultados tanto do modelo quanto do impacto no negócio.

O projeto deve ser **minimamente organizado e comentado**, de forma que possa ser apresentado passo a passo para a banca avaliadora. 

Caso haja testes que falharam, é interessante deixar explícito (exemplo: testes de hiperparâmetros), detalhando aprendizados obtidos.

### 🖥️ Apresentação do Case

Durante a apresentação, o candidato deverá:
- Compartilhar a tela e mostrar o código-fonte.
- Utilizar a plataforma onde o código foi desenvolvido ou apresentar um arquivo exportado (.html, por exemplo).
- Explicar todas as etapas desenvolvidas, justificando as escolhas metodológicas e comparando com outras possíveis abordagens.
- Demonstrar os resultados obtidos sob duas óticas:
  - **Modelagem**: Apresentação das métricas utilizadas, explicando e justificando sua escolha.
  - **Negócio**: Demonstração dos impactos e ganhos da solução.
- Destacar decisões relacionadas ao uso de algoritmos ou pacotes específicos, considerando questões como:
  - Desempenho
  - Eficiência computacional
  - Recursos disponíveis
  - Potencial implantação em produção

A clareza na comunicação e na estruturação da apresentação é de inteira responsabilidade do candidato.

### 🏅 Critérios de Avaliação
A avaliação será realizada conforme as seguintes categorias:

#### Níveis de Desempenho

- **(A)** Realizou a etapa de forma adequada e demonstrou domínio do tema.
- **(B)** Realizou a etapa de forma parcialmente adequada ou demonstrou domínio parcial do tema, necessitando orientações para aprofundamento.
- **(C)** Não realizou a etapa de forma adequada ou não demonstrou domínio do tema.

#### Definição das Badges

| Badge            | Critérios |
|-----------------|--------------------------------------------------------------------------|
| **Expert**      | - Máximo de 2 avaliações "C"  
                  - Pelo menos 13 avaliações "A"   |
| **Advanced**    | - Máximo de 6 avaliações "C"  
                  - Pelo menos 5 avaliações "A"    |
| **Driven**      | - Máximo de 16 avaliações "C"  
                  - Pelo menos 5 avaliações "B" ou superior  |
| **Sem Badge**   | - Pelo menos 16 avaliações "C"  
                  - No máximo 5 avaliações "B" ou superior  |

### 📂 Entregáveis
Os seguintes materiais deverão ser entregues:

1. **Código-fonte do notebook desenvolvido** (exportado em `.html` ou outro formato legível) - **OBRIGATÓRIO**.
2. **Apresentação em PowerPoint** contendo:
   - Descrição do problema
   - Principais insights obtidos
   - Resultados dos modelos e impacto no negócio (**OPCIONAL**).

Mesmo que o candidato utilize um PowerPoint, ele deve ter o código aberto e disponível para responder a perguntas da banca avaliadora.
A organização do código é fundamental para facilitar a apresentação e será um critério de avaliação.

### 📊 Dicionário de Dados
Os dados utilizados no projeto estão no formato **Parquet** e incluem as seguintes tabelas:

#### `transactions.csv`
Contém as transações dos usuários até 31/03/2017.

- **msno**: ID do usuário.
- **payment_method_id**: Método de pagamento.
- **payment_plan_days**: Duração do plano de assinatura.
- **plan_list_price**: Preço do plano (em New Taiwan Dollar - NTD).
- **actual_amount_paid**: Valor pago pelo usuário (em NTD).
- **is_auto_renew**: Indica se a renovação automática está ativada.
- **transaction_date**: Data da transação (`%Y%m%d`).
- **membership_expire_date**: Data de expiração da assinatura (`%Y%m%d`).
- **is_cancel**: Indica se o usuário cancelou a assinatura nesta transação.

#### `user_logs.csv`
Registra o comportamento de escuta dos usuários até 31/03/2017.

- **msno**: ID do usuário.
- **date**: Data do log (`%Y%m%d`).
- **num_25**: Quantidade de músicas tocadas por menos de 25% do tempo total.
- **num_50**: Quantidade de músicas tocadas entre 25% e 50% do tempo total.
- **num_75**: Quantidade de músicas tocadas entre 50% e 75% do tempo total.
- **num_985**: Quantidade de músicas tocadas entre 75% e 98.5% do tempo total.
- **num_100**: Quantidade de músicas tocadas por mais de 98.5% do tempo total.
- **num_unq**: Número de músicas únicas tocadas.
- **total_secs**: Total de segundos de reprodução por dia.

#### `members_v3.csv`
Informações sobre os usuários (nem todos os usuários do conjunto de dados estão incluídos).

- **msno**: ID do usuário.
- **city**: Cidade do usuário.
- **bd**: Idade do usuário (contém valores discrepantes entre -7000 e 2015, análise cuidadosa necessária).
- **gender**: Gênero do usuário.
- **registered_via**: Método de registro.
- **registration_init_time**: Data de registro (`%Y%m%d`).

### ⏳ Tempo de Apresentação
O candidato terá **1 hora e 30 minutos** para:
- Apresentar o case.
- Responder às perguntas dos avaliadores.

---

Boa sorte! Esperamos que sua solução demonstre um domínio completo dos conceitos de **Ciência de Dados**! 🚀


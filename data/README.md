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

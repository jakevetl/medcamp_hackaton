# MedCamp Hackathon

Este projeto é para o hackathon da MedCamp, focado na análise e modelagem dos dados de eventos de saúde.

## Estrutura do Projeto

- `data/`: Contém arquivos de dados brutos e processados.
- `notebooks/`: Contém notebooks Jupyter para análise e experimentação.
- `scripts/`: Contém scripts Python para processamento de dados e modelagem.

## Dicionário de Dados

### 1. `First_Health_Camp_Attended.csv`

- **Patient_ID**: Identificador único do paciente (int64)
- **Health_Camp_ID**: Identificador do camp de saúde (int64)
- **Donation**: Valor da doação feita pelo paciente (float64)
- **Health_Score**: Pontuação de saúde do paciente (float64)

### 2. `Health_Camp_Detail.csv`

- **Health_Camp_ID**: Identificador do camp de saúde (int64)
- **Camp_Start_Date**: Data de início do camp (object)
- **Camp_End_Date**: Data de término do camp (object)
- **Category**: Categoria do camp (tipo de formato) (object)

### 3. `Patient_Profile.csv`

- **Patient_ID**: Identificador único do paciente (int64)
- **Online_Follower**: Número de seguidores online do paciente (int64)
- **Social_Media**: Detalhes sobre as redes sociais do paciente (object)
- **Income**: Renda do paciente (float64)
- **Education**: Nível de educação do paciente (object)
- **Age**: Idade do paciente (int64)
- **First_Interaction_Date**: Data da primeira interação do paciente com o camp (object)
- **City_Type**: Tipo de cidade onde o paciente reside (object)
- **Employer_Category**: Categoria do empregador do paciente (object)

### 4. `Second_Health_Camp_Attended.csv`

- **Patient_ID**: Identificador único do paciente (int64)
- **Health_Camp_ID**: Identificador do camp de saúde (int64)
- **Health_Score**: Pontuação de saúde do paciente (float64)

### 5. `Third_Health_Camp_Attended.csv`

- **Patient_ID**: Identificador único do paciente (int64)
- **Health_Camp_ID**: Identificador do camp de saúde (int64)
- **Number_of_Stall_Visited**: Número de estandes visitados pelo paciente (int64)
- **Last_Stall_Visited_Number**: Número do último estande visitado (int64)

### 6. `Train.csv`

- **Patient_ID**: Identificador único do paciente (int64)
- **Health_Camp_ID**: Identificador do camp de saúde (int64)
- **Registration_Date**: Data de registro do paciente para o camp (object)
- **Anonymized_Variables**: Variáveis anonimizadas relacionadas ao registro (object)

### 7. `test.csv`

- **Patient_ID**: Identificador único do paciente (int64)
- **Health_Camp_ID**: Identificador do camp de saúde (int64)
- **Registration_Date**: Data de registro do paciente para o camp (object)
- **Anonymized_Variables**: Variáveis anonimizadas relacionadas ao registro (object)

## Estrutura do Projeto

- `data/`: Contém arquivos de dados brutos e processados.
- `notebooks/`: Contém notebooks Jupyter para análise e experimentação.
- `scripts/`: Contém scripts Python para processam
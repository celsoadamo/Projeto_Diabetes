# Documentação do Projeto Diabetes

Projeto de ciência de dados da área de **saúde** com objectivo de **prever** se um determinado paciente tem diabetes.

![image](https://user-images.githubusercontent.com/64884982/162898613-5303ac4f-d3bf-42ce-98df-147e96ad1431.png)

# **Introdução**

A diabete está entre as doenças **crônicas mais prevalentes** nos Estados Unidos da América (EUA), impactando milhões de Americanos a cada ano exercendo um encargo financeiro significativo na economia. É uma doença crônica grave em que os indivíduos perdem a capacidade de regular níveis de glicose (acuçar) no sangue, podendo levar à redução de qualidade de vida e da expectativa de vida (Teboul, A., 2021).

A diabete geralmente é caracterizada pelo facto do corpo não produzir insulina suficiente ou ser incapaz de usar insulina de forma tão eficaz quanto necessário, o que pode provocar complicações como: **doenças cardíacas, perda de visão, amputação de membros inferiores e doença renal.**

O diagnóstico precoce pode levar a mudanças no estilo de vida e tratamento mais eficaz, tornando os modelos preditivos de risco de diabetes ferramentas importantes para autoridade públicas e de sáude pública.

# **Objetivos do projeto**

Neste projeto cobrimos todas as etapas de um projeto real de Ciência de Dados e respondemos a algumas questões importantes sobre a área de saúde (diabetes), utilizando dados disponibilizados no kaggle sobre uma pesquisa feita nos EUA, com intuito de permitir que tenhamos conhecimento e/ou descubramos insigths que não estão evidenciados de forma explicita sobre diabetes que é uma doença que temos casos no nosso dia a dia:

•	Qual é a corelação entre as avriáveis preditoras e a variável alvo?
•	Qual  é a distribuição dos entrevistados por cada classe? 
•	Qual é a distribuição das variáveis índice de massa corporal, idade, nível de pessão arterial, nível de colestrol é igual em cada uma das classes?
•	Quais os factores que mais influenciam na obtenção de diabetes?

O objetivo é dar a conhecer alguns insigths extraídos a partir dos dados e criar uma solução (modelo preditivo e dashboard) para a área de saúde que permite classificar um paciente de forma precoce nas seguintes classes: **diabético, pré-diabético e não diabéticos**.

Por fim, realçar que o grande impacto que o projeto terá na área de saúde é o que a seguir se descreve: 
•	Esta ferramenta e/ou solução tecnológica permitirá que os orgãos responsáveis pela saúde pública investiguem com mais detalhes o que contribui e/ou quais os factores que influenciam nesta doença, de modo a definir-se estratégias a curto prazo para identificação precoce de diabetes (no estágio de pré-diabetes) e permitindo um tratamento mais eficaz.

**Pré-diabetes** é uma condição de saúde grave em que **os níveis de acuçar no sangue são mais altos do que o normal**, mais ainda não altos o suficiente para serem diagnosticados como diabetes do tipo 2 (Wikipédia).

# **Solução Proposta**

**Tecnologias Utilizadas**

Para resolver este problema foi construida uma solução completa para armazenamento e gestão usando Google Cloud Plataform (GCP), além de explorar uma suite de tecnologias e/ou bibliotecas para análise, visualização de dados e machine learning tais como: pandas, matplotlib, seaborn, scikit-learn, streamlit, pycaret e pyspark.

**Pandas** – biblioteca usada para manipulação de dados
![image](https://user-images.githubusercontent.com/64884982/162899778-6f2bea02-a8b8-4be3-a5c1-5885359a11a4.png)

**Matplotlib** – biblioteca usada para visualização de dados.
![image](https://user-images.githubusercontent.com/64884982/162899811-0d623e91-20ac-4905-b8d7-58da573a2156.png)

**Seaborn** – biblioteca usada para visualização de dados baseada no matplotlib, permitindo construir graficos mais profissonais.
![image](https://user-images.githubusercontent.com/64884982/162899855-98ff2052-6e24-4143-b2ab-66f03c84d6b9.png)
 
**Scikit-learn** – biblioteca usada para implementar os algoritmos de machine learning (utilizou-se o pickle para serializar o modelo em disco)
![image](https://user-images.githubusercontent.com/64884982/162899884-2aca9910-6e0c-49e5-a1ab-4b47c35732bd.png)
 

**Pycaret** – biblioteca open-source usada para fazer Auto-ML em um projeto de ciência` de dados.
![image](https://user-images.githubusercontent.com/64884982/162899903-6ae93747-a63a-4bb4-843a-5a459d30d4aa.png)
 
**Streamlit** – biblioteca utilizada para desenvolver a aplicação e/ou fórmulário para testar o modelo em ambiente de produção.
![image](https://user-images.githubusercontent.com/64884982/162899919-992cd3a2-dc5d-425d-8f60-90ac57581039.png)
 

**Ferramentas de auxiliares:**

**Pyspark** – para processamento de grandes volumes de dados em ambientes distribuído.
![image](https://user-images.githubusercontent.com/64884982/162899940-51f646bd-4301-438e-b71a-e7ffe8c76288.png)
 
**Python** – liguagem de programação utilizada para desenvolver o projeto de ciência de dados.
**Google colab** – editor de código online que geralmente é organizado por células que permite executar todas as etapas de um projeto de ciência de dados.
 ![image](https://user-images.githubusercontent.com/64884982/162899986-8e100884-64fd-409d-882b-8e5b86ef15f6.png)

**Github** – ferramenta que permite versionar, partilhar o código desenvolvido e também atribuir acesso a outros profissinais para colaborarem nos artefatos do projeto.
![image](https://user-images.githubusercontent.com/64884982/162900024-0db3a47d-a8e9-42e8-a521-dac4d5812c50.png)
 
**Apache Airflow** - é uma plataforma de gerenciamento de fluxo de trabalho de código aberto para pipelines de engenharia de dados.
![image](https://user-images.githubusercontent.com/64884982/162900040-b89e2e4e-92d4-41cb-a0dd-ba6046c13d24.png)
 
**Terraform** – é uma ferramenta do tipo infraestrutura como código (IaC) que permite o gerenciamento e provisionamento da infraestrutura por meio de códigos, em vez de processos manuais. Esta ferramenta foi utilizada para criar os buckets de forma automatizada.
![image](https://user-images.githubusercontent.com/64884982/162900057-c9cb146e-fcdd-452e-a708-fdfda0694427.png)
 
**Kubernetes** -  é uma ferramenta para orquestrar os serviços disponibilizadas no docker, ou seja, é um plataforma de código aberto, portável e extensiva para o gerenciamento de cargas de trabalho e serviços distribuídos em contêineres, que facilita tanto a configuração declarativa quanto a automação
![image](https://user-images.githubusercontent.com/64884982/162900087-0f84710d-c171-4904-be7b-02f557f1f5ca.png)
 
**Google Cloud Plataform (GCP)** - é uma suíte de computação em nuvem oferecida pelo Google, funcionando na mesma infraestrutura que a empresa usa para seus produtos dirigidos aos usuários
 

**Overview Geral de Tecnologias Utilizadas no Projeto**
![image](https://user-images.githubusercontent.com/64884982/162900238-f8f64a2b-7186-4d54-8f7b-02c2e41c8729.png)

**Arquitecturas**
Em seguida é ilustrada o overview da solução desde a coleta até ao deploy da solução desenvolvida.
Projetada pela squad **Jupyter** cujos os integrantes são:
- Pedro Lucas – Data Analyst and Project Leader
- Celso Adamo - Data Scientist
- Adilson Silva - Data Engineer

![image](https://user-images.githubusercontent.com/64884982/162900309-1b10e747-6ebf-46f5-bd82-66fa632d4723.png)

Os principais desafios enfrentados foram:
•	**Integrar o notebook** do Google Colab com o GCS usando emails pessoais, permitindo desta forma a leitura dos datasets armazenados no GCP.
•	**Carregar o modelo** na app do streamlit devido a incompatibilidade de versões.
•	**Criar a api** usando o framework web FastAPI.
•	C**onectar o GCS com api-ml** e a aplicação.

# **Resultados**

**Insights e Conhecimento Gerado**

Na etapa de Análise Exploratória dos Dados foram descobertos vários insights importantes abaixo descritas.
Pela análise estatistica básica feita sobre os dados apurou-se o seguinte:
•	Em médias os entrevistados têm um índice de massa corporal (BMI) de 28.68.
•	Quase metade das pessoas entrevistadas fumam e/ou comem fruta.
•	73.34 % das pessoas entrevistadas praticam actividades físicas. 	
•	79.48 % das pessoas entrevistadas comem vegetais.
•	Quase ninguém consume álcool em altas proporções (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week).
•	94% das pessoas entrevistadas usaram algum plano e/ou seguro de saúde.

Foram feitas algumas questões sobre os dados e constatamos o seguinte:
A maioria das variáveis possuem uma **correlação fraca** entre elas exceptuando a variáveis **PhysHlthe GenHlth** que possuem uma **correlação média**.

![image](https://user-images.githubusercontent.com/64884982/162900590-2391808f-6686-468d-a7a9-7909d1c56d13.png)

Analisando a distribuição dos entrevistados por classes constatou-se que 83% dos entrevistados não tem diabetes.

![image](https://user-images.githubusercontent.com/64884982/162900719-8ee75eb9-6c31-4c5a-8b17-2d90d56f33ab.png)

O índice de massa coporal tem o mesmo dominio de valores para as 3 classes envolvidas.
![image](https://user-images.githubusercontent.com/64884982/162900746-c0f87623-2b52-456b-b52c-e6cbe98d7a47.png)

A maior parte das pessoas com **pré-diabetes e diabetes** estão em **idade** pertencentes a **categoria 6 em diante**. Não obstante, não chegamos a nenhuma conclusão de grau de obtenção de diabetes em função da idade.
 
![image](https://user-images.githubusercontent.com/64884982/162900859-52baf841-ab1a-44d3-aad0-cae98d46d179.png)

A maior parte das pessoas com **pressão arterial alta e/ou colesterol alto* pertencem as categorias **pré-diabetes e diabetes**.
![image](https://user-images.githubusercontent.com/64884982/162900936-7e3bf3f1-fa22-4a6f-a406-ed29c187591a.png)

![image](https://user-images.githubusercontent.com/64884982/162900949-13483bd4-9924-42bd-be16-2af72541385a.png)

Grau de importâncias das variáveis preditoras no modelo em percentagem.
![image](https://user-images.githubusercontent.com/64884982/162901012-57c6b8d9-e445-4532-a4e8-01d98c605cea.png)

**Métricas de Performance**

Para predizer se o paciente pertence a cada uma das classe foi implementado um modelo utilizando o **Random Forest** que atingiu uma performance **F1-Score** de aproximadamente 85% (84.70% - superando um pouco um modelo de base que é de 75%). 
Como tratava-se de um problema de **classes desbalanceadas** e houve necessidade utilizar a técnica de **over sampling denominada SMOTE** e de analisar as métricas **precision e recall** como forma de analisar a performance de previsão de cada uma das classes.

![image](https://user-images.githubusercontent.com/64884982/162901281-476467fb-46c7-4a47-b292-48bbc1010336.png)

# **Conclusão**

Através deste projeto foi possível praticar e implementar conceitos importantes de Ciência e Engenharia de Dados e propor uma solução para a área de saúde que permite **descobrir alguns insigths** sobre diabetes e **classificar se um paciente** pertence a cada uma das classes identificadas na secção do objectivo.

A resolução dos problemas acima mencionados, permitirá obter insights para desenhar e/ou alterar a estratégia aplicada á área de saúde no que concerne a diabetes, visto que, esta doença tem um impacto significativo na economia e pode ter complicaçoes quando nao detectado em estágios mais precoces. 

Com a implementação desta solução teremos como beneficio, um recurso organizacional que servirá de apoio aos médicos na leitura de análises médicas e contribuirá para identificar as principais variáveis que influenciam em cada uma das classes.

Por fim, como um processo de melhoria continua pode-se reduzir o erro de previsão do modelo utilizando outras técnicas como feature engeneering, redução de dimensionaldade, entre outras e criar mais interatividade no dashboard do streamlit.



**Anexos**
Link do Streamlit e dashboard: http://34.69.222.196/
**App**
![image](https://user-images.githubusercontent.com/64884982/162901418-75ce03ed-e672-4519-be62-2d8014490b87.png)
 
**Dashboard**
![image](https://user-images.githubusercontent.com/64884982/162901432-78d816cf-c64f-4fdb-8a02-9028731a9b4e.png)



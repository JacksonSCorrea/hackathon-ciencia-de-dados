## PoD Bank - Modelo de Concessão de Crédito

---

### 1. Entendimento do Negócio
A concessão de crédito implica em riscos financeiros, incluindo perda financeira, redução de liquidez, aumento de custos de recuperação, avaliação inadequada de crédito e fraude.

Sabendo-se disso, a PoD Bank, uma startup financeira, busca aprimorar suas decisões de crédito através de modelos estatísticos, oferecendo crédito imobiliário, veicular e empréstimo pessoal.
Fornece, como principais produtos, o Crédito Imobiliário, o Crédito Veicular e o Empréstimo Pessoal.

Atualmente está enfrentando problemas com o aumento da inadimplência, 
em paralelo ao também aumento da carteira de clientes. Sendo assim, necessita de um ferramental tecnológico para auxílio na concessão de um crédito mais consciente.

---

### 2. Objetivo do Projeto
Desenvolvimento de um modelo preditivo para avaliação do risco de inadimplência, visando decisões informadas na concessão de crédito.

---

### 3. Sobre os Dados
Utilização de dados internos e externos fornecidos pela PoD Bank, incluindo informações cadastrais, transacionais e históricos de crédito.

---

### 4. Etapa de Feature Engineering
Criação de 11 novas variáveis para enriquecer a compreensão do perfil do aplicante, incluindo razões de renda para crédito, idade, proporção de filhos para renda, entre outras.

---

### 5. Metodologia
Implementação de dois modelos: um performático baseado em XGBoost e outro de Regressão Logística para explicabilidade. Ênfase na ordenação de Scores.


#### 5.1 Modelo Performático
Utilização do algoritmo XGBoost, com treinamento e otimização de hiperparâmetros. Avaliação inclui métricas como Acurácia, Precision, Recall e AUC-ROC.


#### 5.2 Regressão Logística
Treinamento com o algoritmo Logit da Statsmodels, com geração de Scorecard. Ênfase na interpretabilidade e significância estatística das variáveis.


#### 5.3 Escolha do Modelo
Dado o momento atual do banco, onde é necessário realizar uma transição da forma de concessão, o modelo selecionado foi a Regressão Logística, devido a sua explicabilidade.

---

### 6. Principais Indicadores de Desempenho (KPIs) do Modelo de Crédito Apresentado:
- Taxa de Inadimplência média da carteira atual: 8%
- Taxa de Inadimplência média da carteira futura: 4,3%
- Taxa de Aprovação: 70%


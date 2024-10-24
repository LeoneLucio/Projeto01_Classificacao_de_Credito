# Projeto 01 - Concessão de Cartões de Crédito

## Descrição

Este projeto visa desenvolver um modelo preditivo para identificar o risco de inadimplência em propostas de cartões de crédito. O modelo será utilizado para auxiliar os mutuários em suas decisões financeiras, ajudando a prever se um cliente poderá se tornar um mau pagador (inadimplente) nos próximos 12 meses.

## Objetivos

- **Objetivo do negócio**: Ajudar os mutuários a avaliarem suas próprias decisões de crédito.
- **Objetivo da modelagem**: Desenvolver um modelo preditivo robusto para identificar inadimplentes com base em dados disponíveis no momento da solicitação do cartão.

## Etapas do Projeto

### 1. Entendimento do Negócio
- Análise do problema de concessão de cartões de crédito e definição dos objetivos.

### 2. Entendimento dos Dados
- Análise de 15 variáveis, incluindo características demográficas e financeiras dos clientes.
- Variável resposta: **mau** (indicadora de mau pagador).

### 3. Preparação dos Dados
- Limpeza e formatação dos dados, incluindo a transformação de variáveis categóricas em variáveis dummy.

### 4. Modelagem
- Utilização da técnica de **Floresta Aleatória** (Random Forest) para construir o modelo preditivo.
- Divisão dos dados em conjuntos de treinamento e teste para avaliação do modelo.

### 5. Avaliação dos Resultados
- Cálculo da acurácia do modelo e análise da matriz de confusão para avaliar a performance.

### 6. Implantação
- Discussão sobre como implementar o modelo em um sistema automatizado de concessão de crédito.

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**: pandas, seaborn, matplotlib, scikit-learn

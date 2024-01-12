# LungCancerClassificationAndPrediction
Modelo de **regressão logística binária.**

![Linear Regression Vs. Logistic Regression](https://github.com/Vi-n1/LungCancerClassificationAndPrediction/assets/138793693/b37d656e-8944-4bf8-a231-48a6152b318d)
fonte: Linear Regression Vs. Logistic Regression, Data Camp.


# Objetivo:
Classificar e prever o câncer de pulmão usando regressão logística binária em um conjunto de dados de pacientes com sintomas respiratórios.

# Explicação do modelo:

O modelo de machine learning escolhido para esse dataset foi a regressão logística binária, que é um modelo de aprendizado supervisionado que estima a probabilidade de um resultado binário (câncer ou não câncer) com base em variáveis independentes (idade, sexo, fumante, etc.). Esse método tem algumas vantagens, como:

- Pode lidar com variáveis independentes de diferentes tipos e escalas, sem a necessidade de transformações ou padronizações.
- Pode modelar a relação não linear entre as variáveis independentes e a probabilidade do evento de interesse.
- Pode ser facilmente implementada em diversos softwares estatísticos, como o R, o SPSS, o SAS, o Stata, entre outros.

As variáveis independentes são:

- Gender: M(male), F(female)
- Age: Age of the patient
- Smoking: YES=2 , NO=1.
- Yellow fingers: YES=2 , NO=1.
- Anxiety: YES=2 , NO=1.
- Peer_pressure: YES=2 , NO=1.
- Chronic Disease: YES=2 , NO=1.
- Fatigue: YES=2 , NO=1.
- Allergy: YES=2 , NO=1.
- Wheezing: YES=2 , NO=1.
- Alcohol: YES=2 , NO=1.
- Coughing: YES=2 , NO=1.
- Shortness of Breath: YES=2 , NO=1.
- Swallowing Difficulty: YES=2 , NO=1.
- Chest pain: YES=2 , NO=1.

A variável dependente é:

- Lung Cancer: YES , NO.

O modelo foi avaliado usando os dados de teste, que correspondem a 30% do dataset original. Os resultados foram os seguintes:


|     Metrícas     |           Performance           | 
|     --------     |             -------             | 
| Accuracy         |              89%                |
| F1 score         |              94%                |
| Confusion matrix | TN = 3, FP = 7, FN = 2, TP = 71 |
| ROC AUC          |              88%                |

# Observação:
Este projeto tem fins apenas **educacionais** e não deve ser usado em casos reais.

Banco de dados utilizado: https://www.kaggle.com/datasets/mysarahmadbhat/lung-cancer

# Qualquer dúvida entre em contato:
- Email: dev.venicius1912@gmail.com
- LinkedIn: www.linkedin.com/in/venicius-santana-lima

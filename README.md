# ✈️ Projeto ASTP — Análise de Séries Temporais e Previsão

Este projeto foi desenvolvido no âmbito da unidade curricular de **Análise de Séries Temporais e Previsão (ASTP)** do Mestrado em Ciência de Dados.

O objetivo central é aplicar técnicas de **análise exploratória, modelação clássica, modelação com deep learning** e **análise de causalidade** sobre séries temporais relacionadas com o setor da aviação, nomeadamente **atrasos e cancelamentos de voos**, complementadas com dados meteorológicos reais.

---

## 🗂️ Estrutura do Projeto

```bash
📁 data/
├── flight-delay-dataset-2018-2022_Final.csv
├── weather-events-2018-2022_Final.csv
├── causality-dataset-2018-2022_Final.csv

📁 notebooks/

├── fligth-delay-cleaning.ipynb  
➡️ Limpeza e agregação dos dados de atrasos e cancelamentos de voos, por data.

├── weather-events-cleaning.ipynb  
➡️ Tratamento e filtragem dos dados meteorológicos, agregando os eventos diários por tipo.

├── fligth-delay-EDA.ipynb  
➡️ EDA das séries de atrasos e cancelamentos com testes de normalidade e estacionariedade, etc.

├── weather-events-EDA.ipynb  
➡️ EDA completa das variáveis meteorológicas com visualizações, testes estatísticos e correlações, etc.

├── modelacao-classica.ipynb  
➡️ Aplicação de modelos ETS para prever atrasos e cancelamentos, com avaliação in/out-of-sample.

├── modelacao-deep-learning.ipynb  
➡️ Treino de uma RNN para previsão das séries temporais, com avaliação in/out-of-sample.

├── granger-causality.ipynb  
➡️ Teste de causalidade de Granger entre eventos climáticos e operações aéreas, com visualizações e interpretação.
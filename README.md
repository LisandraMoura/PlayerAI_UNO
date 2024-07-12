# INF0417 - Computer Vision

## Seminário

### Integrantes
- 202204882 - Carlos Henrique
- 202204883 - Edward Scott
- 202204283 - Letícia Mendes
- 202202448 - Lisandra Menezes
- 202202452 - Marcos Vinicius

### [Link para o relatório](https://docs.google.com/document/d/1MbKAPjRs9rijoPWYAb_aqmyYjEI99ii4TLMICg1S3_k/edit?usp=sharing)

### [Link para o pitch](https://www.canva.com/design/DAGIxChZ-xs/RTFOvX1mD3-ZtqcXbYUciA/edit)

### Instale as bibliotecas

´pip install requirements.txt´

### Execução

´cd UnoDetectorModel´

´python .\uno_llm.py´


### Proposta

- **Introdução**:

Com o avanço das técnicas de visão computacional e inteligência artificial, é possível criar sistemas que rivalizam com a habilidade humana em jogos complexos. Nesse contexto, nosso projeto propõe a criação de um jogador automatizado para os populares jogos de cartas Truco e UNO. Utilizando técnicas avançadas de visão computacional, pretendemos desenvolver um sistema capaz de **detectar, em tempo real**, as cartas dos jogos e, com base em bibliotecas de jogos, implementar a jogabilidade.
Para alcançar esse objetivo, empregaremos a biblioteca RICard, uma ferramenta robusta para a implementação de estratégias e regras específicas desses jogos. Nosso projeto se concentrará em métodos de **detecção de objetos, classificação de objetos e segmentação**, fundamentais para que o sistema reconheça as cartas e suas posições de forma precisa e eficiente.

A avaliação da nossa aplicação será baseada em dois critérios principais: **a quantidade de partidas executadas corretamente e a precisão na detecção das cartas**. Esses indicadores nos permitirão medir o desempenho do sistema e identificar áreas para melhorias contínuas.

Utilizamos dois conjuntos de dados para a detecção: cartas de Uno e cartas tradicionais de baralho. Esses conjuntos de dados foram obtidos no Roboflow, e o link para acessá-los está disponível nas referências.
# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto

## Nome do grupo

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/a1exlima/">RM559784@fiap.com.br - Alex da Silva Lima </a>
- <a href="https://www.linkedin.com/in/johnatanloriano/">RM559546@fiap.com.br - Johnatan Sousa Macedo Loriano</a>
- <a href="https://www.linkedin.com/in/matheus-maia-655bb1250/">RM560683@fiap.com.br - Matheus Augusto Rodrigues Maia</a>
- <a href="https://www.linkedin.com/in/brunoconter/">RM560518@fiap.com.br - Bruno Henrique Nielsen Conter</a>
- <a href="https://www.linkedin.com/in/fabiosantoscardoso/">RM560479@fiap.com.br - Fabio Santos Cardoso</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>


## 📜 Descrição

Em cooperativas agrícolas de pequeno porte, a classificação manual de grãos por especialistas pode ser um processo lento e propenso a erros humanos. Este projeto tem como objetivo automatizar a classificação de grãos de trigo utilizando aprendizado de máquina, otimizando a eficiência e a precisão do processo.

Para alcançar esse objetivo, utilizamos o conjunto de dados "Seeds Dataset", disponível no UCI Machine Learning Repository, que contém 210 amostras de grãos de trigo divididas em três variedades: Kama, Rosa e Canadian. As características físicas analisadas incluem área, perímetro, compacidade, comprimento e largura do núcleo, coeficiente de assimetria e comprimento do sulco do núcleo.

O projeto foi desenvolvido com base na metodologia **CRISP-DM (Cross-Industry Standard Process for Data Mining)**, que organiza as etapas de análise em fases bem definidas:

### 1. Entendimento e Preparação dos Dados:
- Análise inicial do conjunto de dados com estatísticas descritivas, incluindo média, mediana e desvio padrão para cada atributo.
- Visualização da distribuição das características utilizando histogramas e boxplots para identificar padrões e outliers.
- Avaliação das relações entre os atributos através de gráficos de dispersão.
- Tratamento de valores ausentes (se existentes) e aplicação de técnicas de pré-processamento, como normalização e padronização, para garantir que os dados sejam adequados para modelos de aprendizado de máquina.

### 2. Modelagem:
- Implementação e comparação de três algoritmos de classificação:
  - **K-Nearest Neighbors (KNN):** Avaliado pela simplicidade e eficiência em problemas com classes bem definidas.
  - **Support Vector Machine (SVM):** Escolhido por sua robustez em problemas de classificação complexa.
  - **Random Forest:** Utilizado para explorar a capacidade de modelagem baseada em múltiplas árvores de decisão.
- O conjunto de dados foi dividido em **70% para treinamento** e **30% para teste**, garantindo a avaliação adequada dos modelos.
- Métricas de desempenho como **acurácia, precisão, recall, F1-score** e análise de matrizes de confusão foram utilizadas para comparar os resultados dos modelos.

### 3. Otimização:
- Aplicação de Grid Search para identificar os melhores hiperparâmetros de cada modelo.
- Reavaliação do desempenho após a otimização, verificando melhorias significativas nas métricas.

### 4. Interpretação dos Resultados:
- Comparação detalhada entre os algoritmos, destacando os pontos fortes e fracos de cada abordagem.
- Extração de insights práticos, como quais características tiveram maior impacto na classificação e como isso pode ser utilizado para otimizar processos em cooperativas agrícolas.

### Contribuições:
- Este projeto demonstra como técnicas de aprendizado de máquina podem ser aplicadas para resolver desafios reais em setores agrícolas.
- Os resultados obtidos oferecem um panorama claro das possibilidades de automatização da classificação de grãos, com potencial para aumentar a produtividade e reduzir custos operacionais.

O código desenvolvido neste projeto está organizado em um notebook Jupyter, detalhando cada etapa descrita acima. A implementação utiliza bibliotecas amplamente conhecidas, como Pandas, Matplotlib, Seaborn e Scikit-learn, tornando o projeto acessível e replicável para outras aplicações.


## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>.github</b>: Nesta pasta ficarão os arquivos de configuração específicos do GitHub que ajudam a gerenciar e automatizar processos no repositório.

- <b>assets</b>: aqui estão os arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>config</b>: Posicione aqui arquivos de configuração que são usados para definir parâmetros e ajustes do projeto.

- <b>document</b>: aqui estão todos os documentos do projeto que as atividades poderão pedir. Na subpasta "other", adicione documentos complementares e menos importantes.

- <b>scripts</b>: Posicione aqui scripts auxiliares para tarefas específicas do seu projeto. Exemplo: deploy, migrações de banco de dados, backups.

- <b>src</b>: Todo o código fonte criado para o desenvolvimento do projeto ao longo das 7 fases.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

### Pré-requisitos

- **Python** versão 3.7 ou superior.
- Bibliotecas necessárias:
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

Para instalar as dependências, execute o seguinte comando no terminal:
```bash
pip install pandas matplotlib seaborn scikit-learn
```

### Passo a passo de execução

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-repositorio.git
   ```
2. Navegue até a pasta principal:
   ```bash
   cd nome-do-projeto
   ```
3. Execute o notebook `analise_exp.ipynb` em um ambiente como Jupyter Notebook ou VS Code.

4. Acesse o dataset diretamente pelo notebook, já configurado para carregar os dados de um URL público.

## 🗃 Histórico de lançamentos

* 0.1.0 - 04/12/2024
    * Versão inicial com o notebook contendo análise exploratória básica.

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

# Plano de trabalho

> Versão 1.0 - 21/11/2020

### 1. Identificação da proposta

#### 1.1 Título

Sistema de Irrigação Vertical - **SIV**

#### 1.2 Prazo

O prazo final da entrega do produto é 15/04/2021.

#### 1.3 Equipe

Jeneffer Farias, Marcelo Bittencourt e Osvaldo Neto.

#### 1.4 Resumo da proposta

Desenvolvimento de um sistema capaz de realizar automaticamente a irrigação de um pequena horta de 
acordo com as condições do solo. Também será desenvolvido um *Dashboard* com o intuito do usuário 
acompanhar as informações e resultados da sua plantação.

#### 1.6 Data de início da projeto: 30/11/2020

### 2. Descrição da proposta

#### 2.1 Justificativa

Com a pandemia de 2020 o mercado de hortaliças, flores e cultivo particular de alimentos sofreu um 
considerável aumento em suas vendas. Dessa forma, o desenvolvimento do sistema SIV permitirá o usuário,
que muitas vezes não tem um conhecimento muito avançado em agricultura e está ali apenas por *hobby*,
uma melhor experiência e controle sobre sua plantação através de uma interface de análise fácil e rápida.
No mercado existem poucas soluções para esse nicho, dentre essas poucas escolhas não encontramos nenhuma 
que fornece a opção de uma interface virtual de análise, sendo este o diferencial da aplicação SIV.
O sistema funcionará basicamente da seguinte forma: Através de sensores presentes no solo da horta, ocorrerá a
comunicação através de uma rede *wifi* entre um módulo de coleta de dados com um servidor, que amarzenará as informações 
em um banco de dados que por sua vez serão processadas para realizar ou não a irrigação da plantação e, por fim,
apresentar essas informações em uma página *web*.

#### 2.2 Objetivo Geral

Desenvolvimento de um sistema capaz de suprir a necessidade de irrigação de sua pequena horta.

#### 2.3 Objetivos específicos

- Desenvolver os dispositivos para a coleta correta dos dados e do acionamento físico da irrigação.

- Realizar uma comunicação confiável entre os módulos (integração dos módulos).

- Armazenamento e análise dos dados coletados.

- Criar uma interface de visualização.

  

#### 2.4 Delimitação/Restrições

- O sistema não será capaz de cobrir plantações extensas.
- Não garantimos que o nosso produto cuidará de todas as variáveis para um bom cultivo.
- O usuário deverá ter uma rede local de *wifi* para o funcinamento do sistema.
- Será necessário também uma fonte de alimentação de energia próxima aos módulos de captura e transmissão dos dados.

### 3. Metas/Macro entregas



| Nº     | Meta(descrição)                                              | Indicadores (físico)                                         |
| ------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **M1** | Elaborar a estrutura do projeto e adquirir componentes       | Relatório especificando a compra do material. Data: 17/12/2020                 |
| **M2** | Sistema de irrigação/o sistema de coleta de dados operacional | Vídeo e código demonstrando o funcionamento do módulos. Data: 25/02/2020       |
| **M3** | Integração entre coleta de dados e API                       | Vídeo e código demonstrando o funcionamento do módulos . Data: 25/02/2021     |
| **M4** | Análise dos dados armazenados                                | Relatório avaliando os dados coletados e implementação de  dashboards: 04/03/2021 |
| **M5** | Protótipo da placa e de definição dos custos                 | Relatório técnico final e protótipo da placa utilizando software para projeto de placas (EasyEDA): Data: 01/04/2021 |



### 4. Identificação das etapas



| Metas  | Nº da etapa | Reponsável pela etapa | Descrição da atividade                                       |
| ------ | ----------- | --------------------- | ------------------------------------------------------------ |
| **M1** | **E1**      | **Osvaldo**           | Realizar compra dos componentes                              |
| **M1** | **E2**      | **Osvaldo**           | Testar e analisar a funcionalidade dos componentes           |
| **M1** | **E3**      | **Osvaldo**           | Implementar testes com os módulos adquiridos                 |
| **M2** | **E4**      | **Osvaldo**           | Registrar o funcionamento dos teste (vídeo)                  |
| **M3** | **E5**      | **Jeneffer**          | Desenvolver API para comunicação com os módulos de coleta e criar uma base de dados para salvar as informações coletadas. |
| **M3** | **E6**      | **Jeneffer**          | Comunicação com a API (armazenamento/leitura dos dados)      |
| **M4** | **E7**      | **Jeneffer**          | Correlação dos dados                                         |
| **M4** | **E8**      | **Marcelo**           | Apresentação dos dados em interface web                      |
| **M5** | **E9**      | **Marcelo**           | Entrega do projeto de protótipo da placa (usando softwarre de design de EasyEDA) |
| **M5** | **E10**     | **Marcelo**           | Levantamento de custos para implementação do sistema         |
| **M5** | **E11**     | **Toda equipe**       | Relatório técnico final                                      |



### 5. Cronograma de execução (Semanas)

| Etapa | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 |
|:-----:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|   M1  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M2  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M3  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M4  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M5  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M6  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M7  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M8  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|   M9  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|  M10  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|  M11  |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |

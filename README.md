# MicrosoftAzure
Aula do curso de Azure pela DIO


Passo a passo para poder realizar a atividade proposta pela educadora da DIO:

- Acessei o Portal do Azure
- No Portal do Azure, cliquei em "Criar um recurso" no lado superior esquerdo.
- Procurei por "Machine Learning" e selecionei "Machine Learning".
- Cliquei em "Criar".
- Tem o tipo de instância de Machine Learning que deseja (por exemplo, Basic, Standard, etc.) e clicar em "Revisar + Criar".
- Após a revisão, cliquei em "Criar" para iniciar a implantação do recurso.
- Preparei os dados que usei para treinar o modelo de previsão. Isso pode envolver limpeza de dados, transformações, seleção de recursos, etc.
- Carregamos os dados no Azure, por exemplo, em um armazenamento de blobs ou um banco de dados Azure SQL.

- No Portal do Azure, fui para o recurso de Machine Learning que nós criamos anteriormente.
- Cliquei em "Estúdio" para abrir o Azure Machine Learning Studio.
- No Estúdio, tem que ir para a seção "Designer".
- Usei a interface do Designer para criar um pipeline de treinamento que inclua a preparação de dados, treinamento do modelo e avaliação do desempenho.
- Executar o pipeline para treinar o modelo.

- Após treinar o modelo, voltamos para o Portal do Azure.
- No recurso de Machine Learning, voltar para a seção "Implantações".
- Cliquei em "Implantar um modelo".
- Escolhi as configurações de implantação adequadas, como tipo de serviço (por exemplo, ACI ou AKS), configurações de escalabilidade, etc.
- Implantamos o modelo.


- Depois de implantar o modelo, nós receberemos um ponto de extremidade (endpoint) que pode ser usado para fazer previsões em tempo real.
- Acessar esse ponto de extremidade e configure conforme necessário para que possa ser acessado pelos sistemas ou aplicativos que precisam das previsões.


- Testei o ponto de extremidade para garantir que esteja funcionando corretamente.
- Configuramos monitoramento para acompanhar o desempenho do modelo em produção.


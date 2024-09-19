# DIOCursoMLAzure

# Etapa 1: Acessar o ambiente da Azure Machine Learning

No canto direito superior terá uma opção "Criar recurso", após isso pesquise pela solu;cão Azure Machine Learning, ao encontrar no Marketplace, selecione a opção.



# Etapa 2: Configuração do recurso

Siga o tutorial a seguir para configurar esse recurso: [Tutorial Microsoft](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

Alguns pontos são importantes, selecione servidor do EUA pois sai mais barato a hora de processamento. Além disso, preencha os nomes adequados do grupo de recursos, nome da área de trabalho.

# Etapa 3: Iniciar o Estúdio

Ao criar o recurso, aparece um botão com a descrição "Ir para recurso".

Depois de aberto o Estúdio, vá na opção do menu lateral esquerdo chamado "ML automatizado", faça configuração e suba o arquivo de dados CSV local para o servidor. [Arquivo CSV para o treinamento](https://github.com/diegoandresantana/DIOCursoMLAzure/blob/main/daily-bike-share.csv)

Realize todas as configurações necessárias e vá avançando.

# Etapa 4: Atenção, no item de configuração de tarefa. 

Vá em Limites digite alguns parametros importantes:
- Máximo de avaliações: 3
- Máximo de avaliações simultâneas: 3
- Máximo de nós: 3
- Limite de pontuação da métrica: 0,085
- Tempo limite do experumento(minutos): 15
- Tempo Limite de iteração: 15

Selecione o Habilitar encerramento antecipado.

Deixe a configuração padrão do servidor que aparece.

Envie para treinamento.

# Etapa 5: Registar modelo

Vá na opção modelos e registre o modelo treinado,após o registro aparecerá na lista de modelos.

# Etapa 6: Avaliando as métricas do modelo

No item tarefas(jobs) pode avaliar as métricas do modelo treinado.

# Etapa 7: Pontos de extremidade.

Vá no item do menu chamado Pontos de extremidade, clique em "Criar", depois selecione o modelo, informe as configurações e implante o serviço.



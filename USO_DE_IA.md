# Declaração de uso de Inteligência Artificial generativa

> **Regra do trabalho:** usar IA generativa é **permitido e incentivado**, mas
> **todo e qualquer uso** precisa estar declarado e detalhado em uma seção própria
> do artigo e na apresentação (vídeo). Uso não declarado é considerado **plágio** e
> leva à **nota zero** no trabalho para todo o grupo.
>
> Este arquivo é o rascunho de trabalho da declaração: preencham **ao longo** do
> projeto (não no último dia) e copiem a tabela para o artigo. Apaguem as linhas de
> exemplo e todas as marcações.

## 1. Ferramentas usadas

| Ferramenta (nome e versão/modelo) | Como acessaram | Quem usou |
|---|---|---|
| _OpenRouter, modelo openai/gpt-6-luna_ | _chave do grupo, via código_ | _todos_ |
| _Claude Code_ | _local_ | _todos_ |
| _Claude Code, modelo Claude Fable 5.2_ | _local_ | _Lucas (usos 15 a 20)_ |

## 2. Usos, um por linha

| # | Etapa | O que a IA fez | Prompt (ou resumo + link para o registro) | O que o grupo fez com o resultado |
|---|---|---|---|---|
| 1 | _Tratamento das Fontes_ | _Limpou os arquivos HTML5 e transformou para MD e transcreveu os arquivos pdf escaneados e colocou em um MD_ | _Transcreva o conteúdo presente nesses arquivos sem mudar o conteúdo e transforme em MarkDown_ | _verificamos se as informações estavam de acordo com os arquivos base_ |
| 2 |_Fontes fictícias_| _Gerou documentos ficticíos baseados nos documentos originais coletados_ | _Utilizando as fontes coletadas como base, crie documentos markdown fictícios para cada uma das intenções buscando aumentar a quantidade de fontes a serem analisadas pelo chatbot crie dois documentos para cada intenção_| _Foram validados para ver se contribuíam na resposta do modelo_ |
| 3 | _Geração de dados para treino_ | _Foi utilizado o script de gerar dados que foi disponibilizado_ | _ver `dados/prompts_llm.md`_ | _Analisamos as frases e escolhemos algumas para entrar nos dados de treino: foram geradas 3.009 frases (2.861 distintas, em 180 prompts) e 967 entraram no treino_ |
| 4 | _Ambiente de desenvolvimento_ | _Ajudou a preparar e configurar o ambiente do VS Code para rodar o projeto_ | _Resumo: "prepare o meu ambiente do VS Code a partir do link do github que te enviei,não faça nada além disso apenas prepare para que eu confira sozinho"_ | _Seguimos os passos e conferimos que o projeto rodava_ |
| 5 | _Uso do terminal_ | _Ensinou a usar os comandos do terminal (git, python)_ | _Resumo: "me ensine a utilizar os comandos no terminal, não rode-os por mim, apenas me ensine passo a passo e quais comandos devo utilizar"_ | _Aprendemos os comandos e executamos nós mesmos_ |
| 6 | _Conferência dos dados de treino_ | _Conferiu os dados adicionados em `dados/treino.csv`_ | _Resumo: "confira os dados que foram adicionados ao arquivo 'dados/treino.csv' e siga as restrições do professor para corrigi-los"_ | _Revisamos o que foi apontado e decidimos o que corrigir_ |
| 7 | _Declaração de uso de IA_ | _Explicou como preencher o USO_DE_IA.md e como fazer commit_ | _"como eu faço para declarar o uso de IA no github?"_ | _Seguimos as instruções e preenchemos o arquivo nós mesmos_ |
| 8 | _Utilização da biblioteca sklearn_ | _Nos auxiliou como utilizar a biblioteca sklearn, como utilizar os classificadores, como usar o GridSearchCV_ | _como utilizo os classificadores KNN, NB, DT, SVM linear, Regressão logística e MLP. Como realizo a validação cruzada com o GridSearchCV_ | _Seguimos as orientações e testamos e refinamos os resultados que obtivemos_ |
| 9 | _Geração dos scripts para gerar gráficos e tabelas_ | _Auxiliou a gerar os gráficos para tanto para análise dos hiperparâmetros, quanto para gerar as tabelas com o desempenho de cada classificador sobre as representações_ | _Como gero os gráficos para análise do resultado do GridSearchCV e gero a matriz de confusão_ | _Entendemos os gráficos e validamos nossa escolha_ |
| 10 | _Escrita do artigo_ | _Montou o rascunho do artigo no modelo SBC (LaTeX e PDF) a partir da seção 9.1 do enunciado e do que já estava no repositório: estrutura das seções, texto, tabelas, figura do fluxo do bot e referências. Marcou como "PENDENTE" as seções ainda não concluídas_ | _"baseado nas instruções sobre a confecção do artigo na seção 9.1, monte este artigo seguindo todas as instruções e o modelo do artigo localizados lá, faça de maneira objetiva e clara (...); se tiver alguma seção que não foi concluída ainda, adicione o nome da seção, o que ela precisa ter e o que ainda falta"_ | _Revisamos o texto, conferimos os números e as frases citadas com os dados e o notebook, e completamos as seções pendentes_ |
| 11 | _Explicação e revisão da geração das seções 6 e 8_ | _Gerou o código das seções descritas e explicou como funcionava_ | _Tendo em vista as células anteriores preencha as seções 6 e 8 e explique o funcionamento delas_ | _Discutimos sobre os resultados gerados e validamos as informações e aceitamos as sugestões_ |
| 12 | _Roteiro e slides para o vídeo_ | _Montou a estrutura dos slides e um roteiro base para apresentação, a partir do artigo e das saídas do notebook; depois removeu o rodapé dos slides e gerou o PDF_ | _"baseado no artigo que foi montado, faça um roteiro base de apresentação para o vídeo de até 10 minutos e estruture os slides baseado no artigo de maneira clara e objetiva"; "retire o que está escrito no canto inferior dos slides e me envie os slides em pdf"_ | _Revisamos os textos e conferimos os números com o notebook, preenchemos os resultados do teste e ajustamos as falas antes de gravar_ |
| 13 | _Geração do código e analise as métricas da seção 9_ | _Gerou o código para plotarmos gráficos e tabelas que auxiliaram na nossa avaliação_ | _Gere ao código para a tabela com os 3 níveis, matriz de confusão, cross validation x teste, desempenho por classe no teste, análise dos erros e o efeito da origem e do tamanho_ | _Utilizamos das métricas para avaliar nosso chatbot e nos ajudar no que precisariamos melhorar_ |
| 14 | _Atualização do artigo e dos slides_ | _Atualizou e adicionou as informações que estavam pendentes no artigo e slides_ | _"baseado no ultimo pull que eu realizei, atualize o conteúdo do artigo e dos slides que já foram confeccionados, com as novas informações trazidas,e  me envie os dois arquivos em pdf"_| _Revisamos os textos e formatos dos documentos buscando uma versão final_ |
| 15 | _Levantamento do que faltava para a entrega_ | _Leu o enunciado e o repositório e listou o que ainda faltava para a entrega; analisou as respostas do formulário (CSV) e sugeriu novas perguntas para ele_ | _"elenque as partes que faltam ser feitas no projeto para finalizar a entrega (...) NÃO ALTERE NADA NO TRABALHO APENAS LISTE"_ | _A lista serviu de referência do que faltava; as mudanças sugeridas para o formulário não foram aplicadas_ |
| 16 | _Análise de viés e variância dos classificadores_ | _Analisou as tabelas e as curvas de validação do notebook, rodou experimentos de validação cruzada só com o treino e sugeriu usar `class_weight="balanced"` e tirar `C = 1000` da grade do classificador de escopo, mantendo a regressão logística_ | _"analisa os gráficos e valores f1 score para a execução de todas as células que eu tenho, não quero um modelo que seja overfittado, quero minimizar o viés e a variância (...) Não altere nada."_ | _Mudamos a grade no notebook, reexecutamos e conferimos os novos resultados (na validação cruzada, o falso aceite do escopo foi de 16,9% para 14,8%)_ |
| 17 | _Revisão dos textos do notebook_ | _Comparou os textos (markdown) de cada seção com as saídas das células e listou os números e argumentos desatualizados. Na etapa final, corrigiu quatro trechos que restavam, o endereço do repositório na primeira célula, recolocou a seção 10 e escreveu o texto de análise do aprofundamento A3 a partir das saídas_ | _"todas as celulas de markdown estao com as informaçoes corretas de codigo?"; "liste todas as mudanças que eu preciso fazer nas celulas de markdown"; "faça o que consegue do que falta"_ | _Corrigimos os textos no notebook e conferimos os números com as saídas_ |
| 18 | _Aprofundamento A3_ | _Gerou uma primeira versão do código do aprofundamento (comparação por origem das frases e curva de aprendizado), ensaiada sem usar o conjunto de teste_ | _"nós escolhemos o A3"_ | _Adaptamos o código (sorteio por intenção e curvas separadas por origem) e executamos no notebook_ |
| 19 | _Revisão final do artigo e entrega_ | _Conferiu os números do artigo com o notebook e os dados (corrigiu "160 prompts" para 180), preencheu a contribuição do integrante Lucas com o texto ditado por ele, incluiu estes usos na tabela de IA do artigo, gerou o `relatorio/relatorio.pdf`, acrescentou ao README o resumo do trabalho e fez os commits. Também ajudou com o Git (atualizar o repositório local) e com a seleção do kernel no VS Code_ | _"faça o que consegue do que falta, declare (...) Coloque o relatório no repositório"_ | _Revisamos o PDF final e os arquivos alterados antes da entrega_ |
| 20 | _Novo visual dos slides_ | _Refez o visual dos 16 slides do vídeo (cores, tipografia, diagrama e gráficos redesenhados a partir dos mesmos dados), mantendo o conteúdo e a ordem de cada slide, e gerou o PDF_ | _"refaça esse slide mantendo as mesmas informações em cada slide, só que mudando completamente o estilo (...) não deixe nada de fora nem mude a ordem"_ | _Conferimos slide a slide com a versão anterior antes de gravar_ |




## 3. O que NÃO foi feito com IA

Definição de intenções, escolha das fontes, preenchimento do **grupo.yaml**, Coleta de frases, rotulação das perguntas coletadas para treinamento e teste com Google Forms

## 4. Reflexão (2 a 4 frases)

A IA nos auxiliou principalmente na parte do código, tanto do pandas para realizar a análise exploratória quanto para analisar os resultados obtidos com os classificadores.
Como era algo que não tinhamos experiência antes foi um facilitador para aprendermos a usar as bibliotecas necessárias.
A verificação foi sendo realizada por quem estava usando na hora e caso aparecesse alguma dúvida nós discutiamos entre a gente para ver o resultado gerado era válido.

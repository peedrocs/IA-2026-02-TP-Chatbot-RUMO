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

## 2. Usos, um por linha

| # | Etapa | O que a IA fez | Prompt (ou resumo + link para o registro) | O que o grupo fez com o resultado |
|---|---|---|---|---|
| 1 | _Tratamento das Fontes_ | _Limpou os arquivos HTML5 e transformou para MD e transcreveu os arquivos pdf escaneados e colocou em um MD_ | _Transcreva o conteúdo presente nesses arquivos sem mudar o conteúdo e transforme em MarkDown_ | _verificamos se as informações estavam de acordo com os arquivos base_ |
| 2 |_Fontes fictícias_| _Gerou documentos ficticíos baseados nos documentos originais coletados_ | _Utilizando as fontes coletadas como base, crie documentos markdown fictícios para cada uma das intenções buscando aumentar a quantidade de fontes a serem analisadas pelo chatbot crie dois documentos para cada intenção_| _Foram validados para ver se contribuíam na resposta do modelo_ |
| 3 | _Geração de dados para treino_ | _Foi utilizado o script de gerar dados que foi disponibilizado_ | _ver `dados/prompts_llm.md`_ | _Analisamos as frases e escolhemos algumas para entrar nos dados de treino, foram criadas 1615, foram escolhidas por volta de 170_ |
| 4 | _Ambiente de desenvolvimento_ | _Ajudou a preparar e configurar o ambiente do VS Code para rodar o projeto_ | _Resumo: "prepare o meu ambiente do VS Code a partir do link do github que te enviei,não faça nada além disso apenas prepare para que eu confira sozinho"_ | _Seguimos os passos e conferimos que o projeto rodava_ |
| 5 | _Uso do terminal_ | _Ensinou a usar os comandos do terminal (git, python)_ | _Resumo: "me ensine a utilizar os comandos no terminal, não rode-os por mim, apenas me ensine passo a passo e quais comandos devo utilizar"_ | _Aprendemos os comandos e executamos nós mesmos_ |
| 6 | _Conferência dos dados de treino_ | _Conferiu os dados adicionados em `dados/treino.csv`_ | _Resumo: "confira os dados que foram adicionados ao arquivo 'dados/treino.csv' e siga as restrições do professor para corrigi-los"_ | _Revisamos o que foi apontado e decidimos o que corrigir_ |
| 7 | _Declaração de uso de IA_ | _Explicou como preencher o USO_DE_IA.md e como fazer commit_ | _"como eu faço para declarar o uso de IA no github?"_ | _Seguimos as instruções e preenchemos o arquivo nós mesmos_ |
| 8 | _Utilização da biblioteca sklearn_ | _Nos auxiliou como utilizar a biblioteca sklearn, como utilizar os classificadores, como usar o GridSearchCV_ | _como utilizo os classificadores KNN, NB, DT, SVM linear, Regressão logística e MLP. Como realizo a validação cruzada com o GridSearchCV_ | _Seguimos as orientações e testamos e refinamos os resultados que obtivemos_ |
| 9 | _Geração dos scripts para gerar gráficos e tabelas_ | _Auxiliou a gerar os gráficos para tanto para análise dos hiperparâmetros, quanto para gerar as tabelas com o desempenho de cada classificador sobre as representações_ | _Como gero os gráficos para análise do resultado do GridSearchCV e gero a matriz de confusão_ | _Entendemos os gráficos e validamos nossa escolha_ |
| 10 | _Escrita do artigo_ | _Montou o rascunho do artigo no modelo SBC (LaTeX e PDF) a partir da seção 9.1 do enunciado e do que já estava no repositório: estrutura das seções, texto, tabelas, figura do fluxo do bot e referências. Marcou como "PENDENTE" as seções ainda não concluídas_ | _"baseado nas instruções sobre a confecção do artigo na seção 9.1, monte este artigo seguindo todas as instruções e o modelo do artigo localizados lá, faça de maneira objetiva e clara (...); se tiver alguma seção que não foi concluída ainda, adicione o nome da seção, o que ela precisa ter e o que ainda falta"_ | _Revisamos o texto, conferimos os números e as frases citadas com os dados e o notebook, e completamos as seções pendentes_ |
| 11 | _Explicação e revisão da geração das seções 6 e 8_ | _Gerou o código das seções descritas e explicou como funcionava_ | _Tendo em vista as células anteriores preencha as seções 6 e 8 e explique o funcionamento delas_ | _Discutimos sobre os resultados gerados e validamos as informações e aceitamos as sugestões_ |
| 12 | _Roteiro e slides para o vídeo_ | _Montou a estrutura dos slides e um roteiro base para apresentação, a partir do artigo e das saídas do notebook; depois removeu o rodapé dos slides e gerou o PDF_ | _"baseado no artigo que foi montado, faça um roteiro base de apresentação para o vídeo de até 10 minutos e estruture os slides baseado no artigo de maneira clara e objetiva"; "retire o que está escrito no canto inferior dos slides e me envie os slides em pdf"_ | _Revisamos os textos e conferimos os números com o notebook, preenchemos os resultados do teste e ajustamos as falas antes de gravar_ |




## 3. O que NÃO foi feito com IA

Definição de intenções, escolha das fontes, preenchimento do **grupo.yaml**, Coleta de frases, rotulação das perguntas coletadas para treinamento e teste com Google Forms

TODO: digam explicitamente o que foi feito sem IA (ex.: definição das intenções,
frases do teste, análise dos erros, conclusões).

## 4. Reflexão (2 a 4 frases)

A IA nos auxiliou principalmente na parte do código, tanto do pandas para realizar a análise exploratória quanto para analisar os resultados obtidos com os classificadores.
Como era algo que não tinhamos experiência antes foi um facilitador para aprendermos a usar as bibliotecas necessárias.
A verificação foi sendo realizada por quem estava usando na hora e caso aparecesse alguma dúvida nós discutiamos entre a gente para ver o resultado gerado era válido.
TODO: onde a IA ajudou, onde atrapalhou ou errou, e como vocês verificaram o que ela produziu.

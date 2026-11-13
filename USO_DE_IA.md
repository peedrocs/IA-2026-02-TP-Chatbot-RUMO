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
| _Exemplo: OpenRouter, modelo openai/gpt-6-luna_ | _chave do grupo, via código_ | _todos_ |
| _Exemplo: ChatGPT (versão gratuita)_ | _navegador_ | _Fulana_ |
| _Claude Code_ | _local_ | _Pedro_ |

## 2. Usos, um por linha

| # | Etapa | O que a IA fez | Prompt (ou resumo + link para o registro) | O que o grupo fez com o resultado |
|---|---|---|---|---|
| 1 | _Dados de treino_ | _Gerou 412 frases para 6 intenções_ | _ver `dados/prompts_llm.md`_ | _Revisamos todas; 57 descartadas, 12 rótulos corrigidos_ |
| 2 | _Chatbot_ | _Redige as respostas das intenções e do chitchat_ | _prompts em `chatbot/llm.py` + persona do `grupo.yaml`_ | _Ajustamos a persona 3 vezes após testes (seção X do artigo)_ |
| 3 | _Código_ | _Sugeriu a função que plota a curva de validação_ | _"como plotar o resultado do GridSearchCV em função de C"_ | _Adaptamos nomes e eixos; entendemos e testamos_ |
| 4 | _Escrita_ | _Revisou a gramática da Introdução_ | _"revise a gramática sem mudar o conteúdo: ..."_ | _Aceitamos parte das sugestões_ |
| 5 | _Tratamento das Fontes_ | _Limpou os arquivos HTML5 e transformou para MD e transcreveu os arquivos pdf escaneados e colocou em um MD_ | _Transcreva o conteúdo presente nesses arquivos sem mudar o conteúdo e transforme em MarkDown_ | _verificamos se as informações estavam de acordo com os arquivos base_ |
| 6 |_Fontes fictícias_| _Gerou documentos ficticíos baseados nos documentos originais coletados_ | _Utilizando as fontes coletadas como base, crie documentos markdown fictícios para cada uma das intenções buscando aumentar a quantidade de fontes a serem analisadas pelo chatbot crie dois documentos para cada intenção_| _Foram validados para ver se contribuíam na resposta do modelo_ |
| 7 | _Geração de dados para treino_ | _Foi utilizado o script de gerar dados que foi disponibilizado_ | _ver `dados/prompts_llm.md`_ | _Analisamos as frases e escolhemos algumas para entrar nos dados de treino, foram criadas 1615, foram escolhidas por volta de 170_ |


## 3. O que NÃO foi feito com IA

Definição de intenções, escolha das fontes, preenchimento do **grupo.yaml**, Coleta de frases, rotulação das perguntas coletadas para treinamento e teste com Google Forms

TODO: digam explicitamente o que foi feito sem IA (ex.: definição das intenções,
frases do teste, análise dos erros, conclusões).

## 4. Reflexão (2 a 4 frases)


TODO: onde a IA ajudou, onde atrapalhou ou errou, e como vocês verificaram o que ela produziu.

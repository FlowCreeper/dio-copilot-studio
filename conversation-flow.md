# Criando Copilot com Fluxo de Conversa Personalizado
Primeiro crie um copilot me banco (Veja o tutorial no arquivo [Criando um Copilot](creating-copilot.md))

## Customize um tópico
### Criando o tópico
- Na aba Tópicos/Topics clique no botão Adicionar um Tópico/Add a Topic e selecione uma das opções de sua escolha.
### Frases de Gatilho
- Dentro do tópico, clique no botão Editar/Edit e modifique/crie palavras chaves que acionarão aquele tópico.
### Resposta/Ação pós gatilho
- Clicando no botão + você poderá escolher o que vai acontecer quando o Copilot entrar naquele tópico.
### Teste se está funcionar
- Após criar um evento recarregue a página e virifuqe se ele está funcionando clicando no botão Test/Teste no canto superior direito.

## Personalizando uma mensagem de erro
### Procurando o tópico de erros
- Na aba tópicos procure o tópico Conversational Boosting caso o esteja usando, senão procure o tópico Fallback.
### Criando a mensagem
- Dentro do tópico de erros, crie uma mensagem ou uma ação de sua escolha na condição default.

## Gerenciando a qualidade de resposta com GenAI
Em uma ação que cria respostas generativas, clicando em edit na data source você pode definir:
### Base de conhecimentos
- Quais base de conhecimento que a IA irá usar para gera a resposta.
### Conhecimento geral
- Deixa escolher será usado ou não a base de conhecimento geral do modelo de IA atual.
### Nivel de moderação
- Nessa opção você pode escolher a criativadade/precisão do agente, sendo low a mais criativa e high a mais precisa, ajuste de acordo com o objetivo da ação.
### Prompt
- O prompt que será passado para o IA para gerar a resposta.

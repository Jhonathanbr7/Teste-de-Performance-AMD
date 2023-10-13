# Teste de Performance AMD

O programa consiste em um teste de performance para placas de video AMD, avaliando qual a porcentagem de tempo em que o FPS estava igual ou acima do requisitado pelo usuário.
Ajudando assim o usuário a descobrir se deve ou não melhorar as configurações para aumentar o desempenho do jogo.

**Como funciona**

Esta API funciona da seguinte maneira:

1.Com o AMD adrenalin instalado, você deve abrir o jogo no qual deseja fazer o teste de performance.
2.Após aberto o jogo, você deve apertar o atalho 'Alt+R' para abrir o AMD adrenalin em modo de sobreposição.
3.Dentro do AMD adrenalin, agora você deve ir para a aba 'Desempenho' e clicar em "Começar a Registrar".
4.Agora você precisa de apertar novamente 'Alt+R' para voltar pro jogo, e jogue pelo tempo que achar necessario fazer a análise.
5.Quando estiver satisfeito com o tempo de analize, aperte 'Alt+R' e clique em "Parar de Registrar", feito isso o programa te mostrará o diretório onde foi salvo a base de dados em ".csv".
6.Você agora deve copiar o arquivo 'Teste de performance AMD.ipynb' para o diretório da base de dados, e renomear a base de dados para "base.csv".
7.Feito isso, você pode executar o arquivo pelo jupyter-notebook, caso não tenha o 'pandas' instalado, basta digitar '!pip install pandas' e executar a célula.
8.Com o pandas instalado, basta executar a célula e digitar qual é o parâmetro de FPS desejado e em seguida apertar o enter.
9.Feito isso o programa mostrará uma mensagem na tela informando qual foi a porcentagem de tempo que o jogo rodou com a taxa de quadros desejada.

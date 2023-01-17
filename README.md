# Webstreams-NodeJS
Treinamento de Webstreams NodeJS -  Erick Wendel

Consumir gigabytes de arquivo direto no frontend sem travar o backend, sem travar o frontend e com funcionalidade para cancelar requests. 

- converter streams do Node.js para as Webstreams
- processar massivamente dados sob demanda

- [ ] Ler um Arquivo CSV com mais de 3 mil linhas
- [ ] Converter os dados para JSON em memória
- [ ] Entregar para o frontend 
- [ ] Frontend pode abortar a operação

Como ler 10GB de JSON no frontend sem travar a tela - Webstreams 101

Problema: se você ler um arquivo de texto de 1gb e quardar em uma variável seu programa vai parar e vai dizer que você estourou a quantidade máxima de memória disponível. Algumas pessoas quebram o arquivo em pequenos pedaços e tentam processar esses dados, mas você rodar um FORLoop que você mapeia, limpa e seleciona a informação faz com que o programa pare de responder os clientes e trave todo o sistema.

A melhor forma de processar uma quantidade infinita de dados em JS é executar tudo sobre demanda e evitar quardar informações na memória

https://www.youtube.com/watch?v=-IpRYbL4yMk

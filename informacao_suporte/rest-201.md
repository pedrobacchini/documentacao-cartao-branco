# Mas porque 201? Entendendo um pouco sobre REST!!!

Seguindo o estilo arquitetural REST temos que aplicar algumas características que o modelo define.

Toda criação de um novo recurso deve ser realizada utilizando o método **HTTP POST** e quando essa operação
for realizada com sucesso ele deve retornar o status code **201** indicando que o recurso foi criado com sucesso.

Adicionalmente você pode incluir o elemento criado no _Body_ na resposta da requisição caso você precise. Outra prática
recomendada é incluir o cabeçalho **Location** na sua resposta. Se você tem dúvida como fazer isso
usando o Spring [veja neste material !!!](../informacao_suporte/spring-response-entity.md)

#Informação de Suporte

Quer conhecer mais sobre REST e ver todos os status codes e suas descrições [Veja Aqui !!!](../informacao_suporte/rest-status.md)

Procura uma descrição mais detalhada do que essa prática recomenda. [Neste link você pode encontrar](https://restfulapi.net/http-status-201-created/) 
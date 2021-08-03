### APIs REST - Contexto Atual

- REST como principal estilo arquitetural

- Microserviços ganhando força

- Enonomia das APIs

- Escalabilidade, disponibilidade e ***performance são questões centrais***.

#### E como podemos obter mais performance ?

- Reduzindo o tamanho das respotas produzidas

- Utilizando banco de dados de forma mais racional

- Monitoramento contínuo a fim de identificar gargalos

- Empregando cache

- Evitando processamentos de longa duração

- Escalando nossas APIs

#### Como reduzir o tamanho das respostas ?

> Removendo valores nulos
<h1 align="center">
  No desevolvimento de API da camada backend, a maioria dos desenvolvedores não fazem uma cobertura completa e assertiva dos valores nullos, pensando em entregar mais rapido a solução ou até gerar um valor de forma mais rapida, acaba passando batido essa validação tão importante. É muito relevante destacar que essa pratica esta totalmente ligada ao core da aplicação, se tratando de uma aplicação backend desenvolvidade em .NET core ou afins, por padrão default, temos os valores nullos em campos não tratados em no JSON, a solução seria tratar esses valores e ignorar, fazendo assim a aplicação gerar leitura somente para os valores que realmente importa, trazendo uma maior performance da API para a leitura, tendo em vista que foi diminuido os dados travegados e os dados a serem enviados no roteamento do backend.
</h1>

> Utilizando técnicas de compressão



> Cache, banco de dados em mémoria

- [x] [Dicas de performance para APIs REST no APS.NET Core](https://renatogroffe.medium.com/dicas-de-performance-para-apis-rest-no-asp-net-core-f2f3c66042c8)
- [x] [APIs REST em ASP.NET Core - Guia de Referência](https://renatogroffe.medium.com/apis-rest-em-asp-net-core-guia-de-refer%C3%AAncia-3e542d02bfb6)
- [x] [Compactação de resposta no ASP.NET Core](https://docs.microsoft.com/pt-br/aspnet/core/performance/response-compression?view=aspnetcore-5.0) 

#### Ferramentas para vizualizar a performance HTTP ou HTTPS
- [Fiddler](https://www.telerik.com/fiddler)
- [Firefox Browser Developer](https://www.mozilla.org/firefox/developer/)

## 👨🏻‍🚀 Sobre mim
<a href="https://www.linkedin.com/in/mateus-macedo-937a32163/">
 <img style="border-radius:50%" width="100px; "src="https://avatars.githubusercontent.com/u/63172367?s=460&u=11fd26ea8a7f5663d7707d7ef254e4f8bfca1b05&v=4"/>
 <p>Mateus Macedo</p>
</a>

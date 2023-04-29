Marvel Personagens
Este é um projeto que utiliza a API da Marvel para buscar personagens e exibir suas informações em uma página web. É possível buscar personagens pelo nome utilizando um campo de busca e a página exibirá os resultados em cards com a imagem do personagem e seu nome.

Tecnologias utilizadas
HTML
JavaScript
Bootstrap
Como utilizar
Para utilizar este projeto, basta baixar ou clonar este repositório e abrir o arquivo index.html em um navegador web. O projeto já está configurado para utilizar a API da Marvel, portanto não é necessário realizar nenhuma outra configuração.

Ao carregar a página, será exibida uma lista com todos os personagens disponíveis. Para buscar um personagem específico, basta digitar o nome dele no campo de busca e a página irá atualizar automaticamente com os resultados da busca.

Como funciona
O código utiliza a API da Marvel para buscar os personagens. Para isso, é necessário informar uma chave de acesso (API key), um timestamp e um hash que são gerados pela própria Marvel. Essas informações são armazenadas em variáveis no início do arquivo JavaScript.

O campo de busca é implementado com um input HTML e um event listener que é acionado sempre que o usuário digita alguma coisa no campo. Quando isso acontece, é feita uma requisição à API da Marvel com o nome do personagem que foi digitado pelo usuário. A resposta da API é processada e os resultados são exibidos em cards na página.

Cada card é criado com a imagem e o nome do personagem. A imagem é obtida da resposta da API e o nome é obtido através de uma tag de texto em HTML. Cada card é adicionado ao HTML da página utilizando o método appendChild() do JavaScript.

Limitações
Este projeto utiliza a API pública da Marvel, que possui limitações de uso. O número de requisições que podem ser feitas por dia é limitado e, caso esse limite seja atingido, o código irá parar de funcionar corretamente. Além disso, a API pública não permite o acesso a todas as informações dos personagens, como suas histórias em quadrinhos, eventos e séries.

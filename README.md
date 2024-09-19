# The-Lord-of-The-Vue
 
1. [Pokedex](#pokedex)
2. [Pedra Papel Tesoura](#pedra-papel-tesoura)

## Pokedex

Este projeto é uma aplicação web interativa de Pokedex, que consome uma API de Pokémon para exibir informações detalhadas sobre diferentes Pokémon. A aplicação foi desenvolvida utilizando Vue.js, com ênfase no gerenciamento de estado global sem o uso do Vuex, e faz requisições de API com Axios para obter os dados.

### Funcionalidades:

- **Gerenciamento de Estado Global**: Ao invés de utilizar Vuex, o estado global da aplicação é gerenciado de forma manual utilizando propriedades globais do Vue ou padrões de comunicação de componentes como `props` e `events`. Isso simplifica o gerenciamento em uma aplicação menor, mas mantém o controle de estados importantes como os dados do Pokémon e o status de carregamento.
  
- **Requisições de API com Axios**: A aplicação realiza chamadas à API de Pokémon usando o Axios, um cliente HTTP popular. Essas requisições são feitas para buscar informações dos Pokémon, como nome, tipo, habilidades e imagem, que são exibidas de forma dinâmica na interface.

- **Carregamento Infinito**: Implementação de "infinite scrolling", onde os Pokémon são carregados dinamicamente à medida que o usuário rola a página. Isso garante que a interface seja responsiva e que não haja sobrecarga de dados ao carregar todos os Pokémon de uma vez. Novas requisições são feitas conforme o usuário chega ao final da página, carregando mais Pokémon automaticamente.

Essa abordagem proporciona uma experiência fluida para os usuários, com uma interface que exibe Pokémon de forma contínua e atualiza o conteúdo à medida que o usuário interage, sem a necessidade de recarregar a página.


## Pedra Papel Tesoura


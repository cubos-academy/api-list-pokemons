![](https://i.imgur.com/xG74tOh.png)

# API List

## Api para acompanhar a aula 🏫

Esse repositório serve para você acompanhar a aula, nele temos:
- Orientações básica de endpoints de uma `api` de listagem de pokemons

---
### API:

URL: https://api-list.pedagogico.cubos.academy
Endpoints: 

* **GET** `/pokemons`: Esse endpoint traz o retorno com uma lista de pokemons, veja no exemplo abaixo:

```json

[
  {
    "id": 1,
    "name": "Bulbasaur",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png",
    "pokemonType": "grass"
  },
  {
    "id": 2,
    "name": "Charmander",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/4.png",
    "pokemonType": "fire"
  },
  {
    "id": 3,
    "name": "Squirtle",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/7.png",
    "pokemonType": "water"
  },
  {
    "id": 4,
    "name": "Pikachu",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/25.png",
    "pokemonType": "electric"
  },
  {
    "id": 5,
    "name": "Eevee",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/133.png",
    "pokemonType": "normal"
  },
  {
    "id": 6,
    "name": "Snorlax",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/143.png",
    "pokemonType": "normal"
  },
  {
    "id": 7,
    "name": "Dragonite",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/149.png",
    "pokemonType": "dragon"
  },
  {
    "id": 8,
    "name": "Mewtwo",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/150.png",
    "pokemonType": "psychic"
  },
  {
    "id": 9,
    "name": "Chikorita",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/152.png",
    "pokemonType": "grass"
  },
  {
    "id": 10,
    "name": "Cyndaquil",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/155.png",
    "pokemonType": "fire"
  },
  {
    "id": 11,
    "name": "Totodile",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/158.png",
    "pokemonType": "water"
  },
  {
    "id": 12,
    "name": "Hoothoot",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/163.png",
    "pokemonType": "normal"
  },
  {
    "id": 13,
    "name": "Togepi",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/175.png",
    "pokemonType": "fairy"
  },
  {
    "id": 14,
    "name": "Sudowoodo",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/185.png",
    "pokemonType": "rock"
  },
  {
    "id": 15,
    "name": "Espeon",
    "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/196.png",
    "pokemonType": "psychic"
  }
]
```

* **GET** `/pokemons/:idPokemon`: Esse endpoint traz o retorno com um pokemon específico, veja no exemplo abaixo:


```json

{
  "id": 1,
  "name": "Bulbasaur",
  "picture": "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png",
  "pokemonType": "grass"
}

```





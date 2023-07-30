# Boas-vindas ao repositório do exercício Tô Viajando?

Você vai criar uma página de suas viagens favoritas – tanto os lugares para os quais já viajou como os que sonha em conhecer.

<details>
  <summary><strong>👨‍💻 O que deverá ser desenvolvido</strong></summary><br />

Neste exercício, você vai desenvolver três componentes: `Header`, `Card` e `CardList`, que serão utilizados para renderizar as informações sobre as cidades.

Os componentes deverão ser criados dentro da pasta nomeada `components`.

</details>

<details>
  <summary><strong>:memo: Habilidades</strong></summary><br />

Neste exercício, vai ser verificada sua capacidade de:

- Criar componentes React reutilizáveis.

- Renderizar as informações recebidas via props, com a tipagem correta.

</details>

## 1 - Crie o componente `<Header />`

- Este arquivo precisa ser criado na pasta `src/components`.

- Este componente deve ser utilizado no `App` para renderizar uma tag `h1` com o texto 'Tô viajando?'.

---

## 2 - Crie o componente `<Card />`

- Este arquivo precisa ser criado na pasta `src/components`.

- O `Card` deve conter a prop `cityInfo`. Nela, deve haver as chaves do tipo string `city`, `country` e `imageUrl`, todas elas obrigatórias, e a chave do tipo boolean `visited`, que é opcional.

- O `Card` deve renderizar o nome da cidade e o país em que se localiza.
  
- A imagem deve ser renderizada com a prop `city` como alt.
  
- Renderize a mensagem "Já Fui!" caso a prop `visited` seja true. Caso contrário, renderize a mensagem "Não Fui."

<br />

---

## 3 - Crie o componente `<CardList />`

- Agora, você deverá renderizar os três Cards para três destinos.
- Este arquivo já está criado na pasta `src/components`.
- Este componente deve renderizar três componentes `Card`, cada um deles com a informação das respectivas cidades (um componente `Card` para Rio de Janeiro, um para a Cidade do Cabo e outro para Acapulco) já contidas no arquivo `src/components/CardList.tsx`.

- Renderize esse componente no App.

---

# Exercício extra

<details>
  <summary> Estilize a aplicação adicionando classes que vão aprimorar seus componentes, de modo que cada conteúdo listado seja um Card</summary><br />.
</details>
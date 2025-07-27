# Adivinhe o filme

Repositório de estudos em HTML e JavaScript.

# Início

# Descrição do Projeto: Quiz de Filmes

O projeto se inicia com **5 filmes**, distribuídos entre os gêneros:

- Aventura
- Ação
- Ficção científica
- Terror
- Suspense

O usuário deve **adivinhar o filme com base em uma descrição**.

Cada filme apresenta **4 opções de resposta**, sendo apenas uma correta.

Após o clique em uma resposta, a **lista de opções deve ser ocultada**, e o **pôster do filme correto deve ser exibido**.

---

# Lista de melhorias (exercícios):

- [x] Melhoria 1 - Acrescentar mais 5 páginas com novos gêneros.
- [] Melhoria 2 - Informar se o usuário acertou ou errou a resposta.
- [] Melhoria 3 - Criar uma tela final com a pontuação total.
- [] Melhoria 4 - Exibir uma mensagem personalizada na tela final.
- [] Melhoria 5 - Exibir miniaturas dos pôsteres dos 10 filmes na tela final.
- [] Melhoria 6 - Adicionar uma contagem regressiva de 60 segundos em cada pergunta.

---

## Melhorias Propostas

### Melhoria 1

Acrescentar mais **5 páginas** com os seguintes gêneros:

- Romance
- Guerra
- Comédia
- Drama
- Fantasia

**Total final:** 10 páginas (10 filmes).

---

### Melhoria 2

Atualmente, ao clicar em uma opção, a tela apenas mostra o pôster do filme correto.  
Precisamos:

- Informar ao usuário se ele **acertou** ou **errou** a resposta.
- Mostrar essa mensagem **junto ao pôster** do filme.

---

### Melhoria 3

Criar uma **tela final** que exiba a **pontuação total** do usuário com base no número de acertos.

---

### Melhoria 4

Na tela final, além da pontuação, exibir uma **mensagem personalizada** com base no desempenho:

| Pontuação | Mensagem                                                               |
| --------- | ---------------------------------------------------------------------- |
| 10        | **Parabéns!** Você é um adivinhador de filmes nível máximo!            |
| 8 a 9     | **Você foi excelente!**                                                |
| 5 a 7     | **Você foi bem**, mas ainda tem muito a melhorar.                      |
| 1 a 4     | **Você não foi bem!** Tente novamente.                                 |
| 0         | **Nossa!** Acho que você estava em uma caverna... assista mais filmes! |

---

### Melhoria 5

Na **tela final**, exibir **miniaturas dos pôsteres** dos 10 filmes, organizadas em formato de **grade (grid)** com **2 linhas de 5 colunas**.

- Os filmes em que o usuário **acertou** devem aparecer **coloridos**.
- Os filmes em que o usuário **errou** devem aparecer em **preto e branco (tons de cinza)**.

---

### Melhoria 6

Em **cada tela de pergunta**, adicionar uma **contagem regressiva de 60 segundos** para que o usuário responda.

- Caso o tempo termine sem resposta, a pergunta deve ser automaticamente marcada como **incorreta**.

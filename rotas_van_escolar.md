# Rota de Van Escolar

Você precisa montar um sistema que ajuda a montar uma lista de endereço para uma rota para uma de alunos de uma van escolar. Para montar este programa você deverá montar um **menu de opções** ao iniciar o programa:

1 – listar alunos e endereço

2 – cadastrar um novo aluno

0 – sair do programa

### Opcao 1

Quando o usuário digitar 1, o programa deverá exibir o nome do aluno junto do seu endereço EX se já contiver alunos cadastros, caso contrário, exibir uma mensagem avisando que não há alunos cadastrados:

Alunos:

1. Joaozinho – Rua Voluntários da Patria, 190, Botafogo, Rio de Janeiro, RJ – CEP 22270-902
2. Mariazinha – Rua Paraná, 120, Centro, Araruma, RJ – CEP 28970-000
3. ...

**Template**: {aluno} – {endereco\_completo} – {cep}

### Opcao 2

Quando o usuário digitar 2, o programa deverá iniciar perguntando o nome do aluno, em seguida seu CEP.
```
Nome : Joaozinho
CEP : 22270902
```
(dica: não peça o traço na hora de digitar o dado, apenas exiba o traço na listagem)

- Se o CEP for inválido ou não encontrado na API, deverá pedir para o usuário digitar novamente.
- Se o CEP não tiver os dados completos, como nome da rua e bairro, ele deverá perguntar para o usuário estas informações para completar o cadastro.

**Exemplo:**

*Já exibir cidade e estado* e perguntar:
```
Logradouro:  Rua Paraná
Bairro: Centro
Número: 123
```
(dica, não transforme em inteiro, deixe com string)

- Se o CEP tiver todos os dados de nome de rua e bairro, pedir apenas o número da residência.

Ao final do cadastro, deve exibir uma mensagem de sucesso e voltar para o **menu de opções.**

### Opcao 3

Quando o usuário digitar a opção 0, o programa deverá ser encerrado.

### para testes

CEPS para ajudar nos exemplos de cidades que não são mapeadas pelos correios

* 28970-000
* 28950-000
* 28930-000

# Sistema de Cadastro e Consulta de Produtos em Python

Este projeto consiste em um script simples em Python para **cadastrar produtos** com seus respectivos preços e realizar **consultas de preços** em tempo de execução via terminal.

---

## 📌 Funcionalidades

- **Cadastro de Produtos:**
  - Permite definir a quantidade inicial de produtos a serem cadastrados.
  - Recebe o nome e o preço de cada produto.
  - **Validação de duplicatas:** Se o produto já tiver sido cadastrado, exibe a mensagem `"Produto já cadastrado"`.
- **Busca de Preços:**
  - Permite consultar o preço de qualquer produto digitando o seu nome.
  - Se o produto existir, o sistema exibe o seu preço.
  - Se não existir, exibe a mensagem `"Produto não cadastrado"`.
  - O loop de busca é encerrado ao digitar a palavra `"Fim"`.

---

## 🛠️ Estrutura do Código

O código utiliza uma única lista linear em Python para armazenar alternadamente os nomes e os preços dos produtos (`[nome1, preco1, nome2, preco2, ...]`).

- `cadastrar_produtos(n)`: Responsável por ler $n$ produtos, verificar se já existem usando slicing (`lista[::2]`) e adicionar os dados na lista.
- `buscar_precos(lista)`: Loop contínuo de consulta até a entrada ser `"Fim"`.
- `main()`: Função principal que gerencia o fluxo de execução do programa.

---

## 🚀 Como Executar

### Pré-requisitos
- Ter o **Python 3.x** instalado na sua máquina.

# Projeto Alunos (JavaScript)

Este é um projeto simples em JavaScript desenvolvido para praticar a manipulação de arrays e objetos. O objetivo principal é criar uma lista de alunos e acessar propriedades específicas de elementos baseando-se em suas posições (índices).

---

## 🚀 Funcionalidades

O script realiza as seguintes operações:
1. Cria um array chamado `alunos` contendo 5 objetos.
2. Cada objeto possui as propriedades: `nome`, `idade` e `disciplinaPreferida`.
3. Acessa e exibe no console o **nome do primeiro aluno**.
4. Acessa e exibe no console a **disciplina preferida do último aluno** utilizando lógica dinâmica para o índice.

---

## 💻 Estrutura do Código

O arquivo principal contém a seguinte estrutura:

* **Manipulação de Índices:** Demonstração prática de que arrays em JavaScript iniciam no índice `0`.
* **Acesso Dinâmico:** Uso da propriedade `.length` para encontrar o último elemento de um array sem precisar adivinhar o tamanho fixo dele (`array[array.length - 1]`).

---

## 🛠️ Como Executar o Projeto

Você pode rodar este projeto de duas formas simples:

### Opção 1: Pelo Terminal (Node.js)
Se você tiver o Node.js instalado em sua máquina:
1. Abra o terminal na pasta do arquivo.
2. Execute o comando:
   ```bash
   node seu_arquivo.js
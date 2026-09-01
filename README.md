<h1 align="center">Repositório de Estudos e Projetos – Java</h1>

<p align="center">
Exercícios, tarefas e projetos desenvolvidos durante minha jornada de aprendizagem em Java na Engenharia de Software e em cursos complementares.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-21+-ED8B00?logo=openjdk&logoColor=white" alt="Java 21+">
  <img src="https://img.shields.io/badge/FIAP-Engenharia%20de%20Software-E4002B" alt="FIAP">
  <img src="https://img.shields.io/badge/Alura-Java-0A66C2" alt="Alura">
</p>

---

### 📖 Sobre o Projeto

Este repositório reúne exercícios, tarefas e projetos desenvolvidos durante meus estudos de **Java**, documentando minha evolução desde os fundamentos da linguagem até a criação de aplicações práticas.

Os conteúdos foram desenvolvidos principalmente durante a disciplina de **Engenharia de Software / DDD na FIAP** e também durante o curso de **Java da Alura**, permitindo colocar em prática conceitos de programação e lógica por meio de diferentes desafios e aplicações.

Entre os conteúdos desenvolvidos estão exercícios envolvendo variáveis, operadores, entrada e saída de dados, estruturas condicionais e de repetição, além de projetos com classes, atributos, métodos e regras de negócio.

---

### 📁 Estrutura do Projeto

O repositório está organizado de acordo com os diferentes momentos e atividades dos estudos:

```text
Java/
│
├── Aula01/ a Aula08/
│   ├── Primitivo.java
│   ├── EntradaDeDados...
│   └── classes/
│       ├── Radio
│       ├── Televisor
│       └── ArCondicionado
│
├── Tarefas/
│   ├── Tarefa01/
│   │   └── Cálculos matemáticos
│   │
│   ├── Tarefa02/
│   │   └── Sistema de Folha de Pagamento
│   │
│   └── Tarefa03/
│       └── Sistema de Gestão de Ingressos
│
└── Projetos/
    └── ContaBancaria/
        └── ContaBancaria.java
```

A estrutura pode ser expandida conforme novos exercícios e projetos forem desenvolvidos.

---

### 🎓 Conteúdos e Projetos Desenvolvidos

#### 🏫 Atividades da FIAP

Durante as aulas de Engenharia de Software / DDD, foram desenvolvidos exercícios e tarefas para consolidar os fundamentos de Java e introduzir conceitos de programação orientada a objetos.

Entre os principais conteúdos estão:

* Tipos de dados e variáveis
* Entrada e saída de dados
* Operadores matemáticos e lógicos
* `Scanner`
* `JOptionPane`
* Classes e atributos
* Métodos
* Introdução à Orientação a Objetos
* Regras de negócio
* Cálculos financeiros

Alguns projetos desenvolvidos incluem:

**Folha de Pagamento**

Sistema responsável por realizar cálculos relacionados ao salário de um colaborador, considerando salário bruto, número de dependentes, INSS e plano de saúde.

**Gestão de Eventos**

Aplicação voltada ao cálculo do valor de ingressos de um evento com base nas despesas, quantidade de convidados e margem de lucro.

---

#### 📚 Projeto Final – Curso de Java | Alura

Como desafio final do curso de Java da Alura, foi desenvolvido um sistema de **Conta Bancária** para aplicar os principais conceitos estudados durante o curso.

A aplicação simula uma conta bancária e apresenta um menu interativo no console, permitindo ao usuário realizar diferentes operações.

##### 💰 Funcionalidades

**1. Consultar saldo**

Exibe o saldo atual da conta.

**2. Receber valor**

Permite informar um valor que será adicionado ao saldo da conta.

**3. Transferir valor**

Permite informar um valor para transferência e verifica se existe saldo suficiente antes de realizar a operação.

**4. Sair**

Encerra a execução da aplicação.

O sistema também possui validações para impedir transferências superiores ao saldo disponível e informar quando uma opção inválida é selecionada.

---

### 🧠 Principais Conceitos Aplicados

Ao longo das atividades e projetos presentes neste repositório, foram praticados conceitos como:

* Declaração e utilização de variáveis
* Tipos de dados
* Operadores de atribuição
* Operadores aritméticos
* Operadores relacionais
* Operadores lógicos
* Entrada de dados com `Scanner`
* Saída de dados no console
* Estruturas condicionais (`if`, `else if`, `else`)
* Estruturas de repetição (`for` e `while`)
* Classes e atributos
* Métodos
* Regras de negócio
* Manipulação de valores numéricos
* Criação de menus interativos

---

### 💻 Exemplo – Conta Bancária

O projeto utiliza variáveis para armazenar os dados iniciais da conta:

```java
String nome = "Luigi Escudero";
String tipoConta = "Conta Corrente";
double saldo = 2500.00;
int opcao = 0;
```

O menu permanece disponível enquanto o usuário não escolher a opção de saída:

```java
while (opcao != 4) {
    // menu e operações
}
```

As operações são controladas através de estruturas condicionais:

```java
if (opcao == 1) {
    // consultar saldo
} else if (opcao == 2) {
    // receber valor
} else if (opcao == 3) {
    // transferir valor
}
```

Para realizar uma transferência, o sistema verifica se o valor solicitado está dentro do saldo disponível:

```java
if (valor <= saldo) {
    saldo = saldo - valor;
} else {
    System.out.println("Você não tem saldo o suficiente!");
}
```

---

### ▶️ Como Executar

**Pré-requisitos:**

* Java 21 ou superior
* IntelliJ IDEA ou outra IDE compatível com Java

Clone o repositório:

```bash
git clone https://github.com/Lueg2007
```

Abra o projeto no **IntelliJ IDEA** e execute a classe que possui o método `main`.

Para executar o projeto de Conta Bancária, abra:

```text
Projetos/ContaBancaria/ContaBancaria.java
```

A aplicação será executada diretamente pelo console.

---

### 🚀 Tecnologias Utilizadas

| Tecnologia                  | Utilização                                     |
| --------------------------- | ---------------------------------------------- |
| **Java 21+**                | Desenvolvimento das aplicações e exercícios    |
| **java.util.Scanner**       | Entrada de dados pelo console                  |
| **javax.swing.JOptionPane** | Entrada e saída de dados por interface gráfica |
| **IntelliJ IDEA**           | Ambiente de desenvolvimento                    |
| **Git**                     | Controle de versão                             |
| **GitHub**                  | Armazenamento e compartilhamento dos projetos  |

---

### 📚 Cursos e Formação

**FIAP – Engenharia de Software**

Atividades acadêmicas desenvolvidas durante a graduação, envolvendo fundamentos de programação, Java, DDD e Orientação a Objetos.

**Alura – Curso de Java**

Curso voltado aos fundamentos da linguagem Java, incluindo variáveis, operadores, entrada de dados, estruturas condicionais e estruturas de repetição.

**Instrutora:** Jacqueline Oliveira

---

### 🚀 Próximos Passos

Este repositório continuará sendo atualizado conforme novos conteúdos e projetos forem desenvolvidos.

O objetivo é evoluir gradualmente dos fundamentos de Java para aplicações mais completas, aprofundando conhecimentos em:

* Orientação a Objetos
* Java
* SQL
* Banco de dados
* APIs
* Desenvolvimento Backend
* Boas práticas de programação

---

### 👤 Autor

<table>
<tr>
<td align="center">
<a href="https://github.com/Lueg2007">
<img src="https://github.com/Lueg2007.png" width="100px;" alt="Lueg2007"/>
<br />
<sub><b>Luigi Escudero Grigoletto</b></sub>
</a>
<br />
<sub>Estudante de Engenharia de Software</sub>
</td>
</tr>
</table>

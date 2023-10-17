# Projeto com JavaFX e JDBC 📜

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-contribuidores">Contribuidores</a> 
</p>

<p align="center">
  <img src="https://github.com/Lucas-Henschel/workshop-javafx-jdbc/blob/main/src/assets/about-page.PNG" alt="About page">
</p>


## 💻 Sobre o projeto

Este é um projeto de estudo onde foi desenvolvido uma interface gráfica onde você pode criar, editar ou remover um departamento e um vendedor. Tudo isso salvando no banco de dados MySQL localmente.

---

## ⚙️ Funcionalidades

- <h3> Seller </h3>
 
- [x] Se você ir em Registration > Seller, você se depara com uma lista de vendedores cadastrados no banco.
- [x] No botão New vai abrir um modal com um formulario para a criação de um vendedor.
- [x] Se você clicar no botão edit de um determinado vendedor, vai abrir um formulario com as informações já carregadas para você editar.
- [x] Se você clicar no botão remove você deleta o vendedor do sistema.

- <h3> Department </h3>
 
- [x] Se você ir em Registration > Department, você se depara com uma lista de departamentos cadastrados no banco.
- [x] No botão New vai abrir um modal com um formulario para a criação de um departamento.
- [x] Se você clicar no botão edit de um determinado departamento, vai abrir um formulario com as informações já carregadas para você editar.
- [x] Se você clicar no botão remove você deleta o departamento do sistema.

---

## 🎨 Layout

- <h3> Seller </h3>

Página principal referente ao vendedor, onde tem uma listagem de todos os vendedores cadastrados no sistema.

<img src="https://github.com/Lucas-Henschel/workshop-javafx-jdbc/blob/main/src/assets/seller-page.PNG" alt="Seller page">

##

Modal com um formulário para criar um vendedor, com todas as vaidações dos campos implementadas.

<img src="https://github.com/Lucas-Henschel/workshop-javafx-jdbc/blob/main/src/assets/seller-form.PNG" alt="Seller form">

##

Modal de confirmação para remover um vendedor.

<img src="https://github.com/Lucas-Henschel/workshop-javafx-jdbc/blob/main/src/assets/remove.PNG" alt="Seller remove">

---

- <h3> Department </h3>

Página principal referente ao departamento, onde tem uma listagem de todos os departamentos cadastrados no sistema.

<img src="https://github.com/Lucas-Henschel/workshop-javafx-jdbc/blob/main/src/assets/department-page.PNG" alt="Department page">

##

Modal com um formulário para criar um departamento, com todas as vaidações dos campos implementadas.

<img src="https://github.com/Lucas-Henschel/workshop-javafx-jdbc/blob/main/src/assets/department-form.PNG" alt="Department form">

---

## 🚀 Como executar o projeto

### Pré-requisitos
  
Antes de começar, é bom ter um editor para trabalhar com o código como [Eclipse](https://eclipseide.org/)

#### 🧭 Rodando o projeto

```bash

# Clone este repositório
$ git clone git@github.com:Lucas-Henschel/workshop-javafx-jdbc.git

# Abra o projeto no Eclipse
$ File > Import > General > Existing projects into workspace > Open project

# Bibliotecas importadas
$ Certifica-se de que todas as bibliotecas estejam importadas no projeto

# Informações do banco de dados
$ No arquivo db.properties coloque as informações da sua máquina local

# Execute o projeto
$ No caminho src > application > Main.java, clique com o botão direito e execute em Run as > Java Application

```
---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- **[Java](https://www.java.com/pt-BR/)**
- **[JDK](https://www.oracle.com/br/java/technologies/downloads/)**
- **[JavaFX](https://gluonhq.com/products/javafx/)**
- **[SceneBuilder](https://gluonhq.com/products/scene-builder/)**
- **[MySQL](https://www.mysql.com/products/workbench/)**
- **[MySQL Connector](https://dev.mysql.com/downloads/connector/j/)**

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://www.linkedin.com/pulse/como-contribuir-em-um-projeto-open-source-github-f%C3%A1bio-amaral/?originalSubdomain=pt)









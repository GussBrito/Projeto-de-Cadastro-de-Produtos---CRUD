# Sistema de Cadastro de Produtos em Java Swing

Um projeto acadêmico de aplicação desktop para realizar o gerenciamento completo de produtos, construído com Java e a biblioteca Swing.

Este sistema implementa as quatro operações fundamentais de persistência de dados (CRUD) e foi desenvolvido para aplicar conceitos de Programação Orientada a Objetos, manipulação de interfaces gráficas e persistência de dados em arquivos.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-GUI-blue?style=for-the-badge)

## 📸 Screenshot
<img width="726" height="606" alt="Captura de tela 2025-08-04 182325" src="https://github.com/user-attachments/assets/f9082584-95e5-4d17-a5f1-143886b104c8" />

## ✨ Principais Funcionalidades

* **Criar (Create):** Adição de novos produtos com validação para impedir códigos duplicados.
* **Ler (Read):** Listagem de todos os produtos cadastrados em uma tabela de fácil visualização.
* **Atualizar (Update):** Seleção e edição de informações de produtos já existentes.
* **Deletar (Delete):** Remoção de produtos da lista com caixa de diálogo para confirmação.
* **Persistência de Dados:** As informações são salvas em um arquivo local (`produtos.dat`) usando serialização de objetos, garantindo que os dados não sejam perdidos ao fechar o programa.

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Java (JDK 11 ou superior)
* **Interface Gráfica:** Java Swing
* **Padrões de Projeto:**
    * DAO (Data Access Object) para separar a lógica de acesso a dados da lógica de negócio.
    * MVC (Model-View-Controller) de forma simplificada, com a View e o Controller na classe `TelaPrincipal`.

## ⚙️ Como Executar o Projeto

Para compilar e executar o projeto localmente, siga os passos abaixo:

```bash
# 1. Clone o repositório
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

# 2. Navegue até a pasta do projeto
cd seu-repositorio

# 3. Compile todos os arquivos .java
javac *.java

# 4. Execute a classe principal
java Main

# POS

Configuração da Base de Dados

Este projecto liga-se à base de dados MySQL através da classe `LigacaoMySql.java`, com as seguintes definições:

```java
String Url = "jdbc:mysql://127.0.0.1:3306/bdpos?useTimezone=true&serverTimezone=UTC";
String User = "root";
String Password = "*****";
```

Crie uma base de dados chamada `bdpos` no seu MySQL local e ajuste o utilizador e a palavra-passe conforme necessário. Certifique-se de que o driver `mysql-connector-java` está incluído nas dependências do projeto.

## ▶️ Como Executar

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. **Abrir no NetBeans:**  
   Recomenda-se utilizar o NetBeans para manter a compatibilidade com os ficheiros `.form`.

3. **Verificar a ligação à base de dados:**  
   Verifique se o servidor MySQL está activo e se os dados de acesso em `LigacaoMySql.java` estão correctos.

4. **Executar o programa:**  
   Compilar e executar o ficheiro `frm_Pos.java`.

## 📌 Requisitos

- Java JDK 8 ou superior
- NetBeans IDE
- MySQL Server (localhost, porta 3306)
- Biblioteca `mysql-connector-java.jar`

## 👩‍💻 Autora

Desenvolvido por **Fernanda**  
Projeto académico e de aprendizagem em Java com foco em interfaces gráficas e integração com base de dados.

---

# 🧾 Java POS System

This project is a Java-based Point of Sale (POS) system with a graphical user interface using Swing. Ideal for small businesses or as an academic exercise, it allows product management, automatic total calculations, and receipt printing.

## 🎯 Features

- Add and remove products from orders
- Modify quantities and prices
- Automatically calculate total
- Print receipts using `PrinterJob`
- Connect to a MySQL database
- User-friendly graphical interface (GUI built with NetBeans GUI Builder)

## 🛠️ Technologies Used

- Java SE 8+
- Swing (javax.swing)
- JDBC (MySQL Connector/J)
- NetBeans IDE (`.form` GUI files)
- MySQL 5.7 or newer

## 🗃️ Database Setup

The project connects to MySQL using the `LigacaoMySql.java` class with the following settings:

```java
String Url = "jdbc:mysql://127.0.0.1:3306/bdpos?useTimezone=true&serverTimezone=UTC";
String User = "root";
String Password = "*****";
```

Create a database called `bdpos` on your local MySQL server and adjust the credentials as needed. Ensure `mysql-connector-java` is included in your project dependencies.

## ▶️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Open in NetBeans:**  
   NetBeans is recommended to preserve compatibility with `.form` files.

3. **Check database connection:**  
   Make sure MySQL is running and the credentials in `LigacaoMySql.java` are correct.

4. **Run the project:**  
   Compile and run the `frm_Pos.java` file.

## 📌 Requirements

- Java JDK 8 or higher
- NetBeans IDE
- MySQL Server (localhost, port 3306)
- `mysql-connector-java.jar` library

## 👩‍💻 Author

Developed by **Fernanda**  
Academic and learning project focused on Java GUI and database integration.

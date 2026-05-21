# 🏨 Hotel Reservation System

Sistema simples de reserva de quartos desenvolvido em Java com foco em Programação Orientada a Objetos e tratamento de exceções personalizadas.

O projeto simula o cadastro e atualização de reservas de hotel via terminal, aplicando regras de negócio e validações de datas.

---

## 🚀 Objetivos do Projeto

Este projeto foi desenvolvido para praticar conceitos fundamentais de backend com Java, incluindo:

- Programação Orientada a Objetos (POO)
- Encapsulamento
- Construtores
- Sobrecarga de métodos
- Tratamento de exceções
- Exceções personalizadas (`DomainException`)
- Manipulação de datas com `Date`
- Entrada de dados com `Scanner`

---

## 🛠️ Tecnologias Utilizadas

- Java
- VS Code
- Git & GitHub

---

## 📂 Estrutura do Projeto

```bash
src/
├── application/
│   └── Program.java
├── model/
│   ├── entities/
│   │   └── Reservation.java
│   └── exceptions/
│       └── DomainException.java
```

---

## ▶️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
```

### 2. Acesse a pasta do projeto

```bash
cd exceptions-java
```

### 3. Compile o projeto

```bash
cd src

javac application/Program.java model/entities/Reservation.java model/exceptions/DomainException.java
```

### 4. Execute o programa

```bash
java application.Program
```

---

## 💻 Exemplo de Execução

```text
Room Number: 101
Check-in date (dd/MM/yyyy): 25/05/2026
Check-out date (dd/MM/yyyy): 30/05/2026

Reservation: Room 101, check-in: 25/05/2026, check-out: 30/05/2026, 5 nights
```

---

## ⚠️ Regras de Negócio

O sistema realiza validações como:

- A data de check-out deve ser posterior ao check-in
- Não é permitido atualizar reservas para datas passadas
- Tratamento de erros de entrada e regras de domínio

---

## 📚 Conceitos Aplicados

- Clean Code básico
- Organização em camadas
- Separação de responsabilidades
- Tratamento de exceções customizadas
- Boas práticas em Java

---

## 🎯 Finalidade

Projeto desenvolvido com fins educacionais para fortalecimento da base em desenvolvimento backend com Java.

---

## 👨‍💻 Autor

Maurício Dos Santos

🔗 LinkedIn: https://www.linkedin.com/in/mauricio-dos-santos-/

🔗 GitHub: https://github.com/Hyouem
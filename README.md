
# 💳 Projeto Bank Exception | Bank Exception Project

Este projeto é um exercício em **Java** com foco em **tratamento de exceções** aplicado a um cenário de **conta bancária**.  
This project is a **Java** exercise focusing on **exception handling** applied to a **bank account** scenario.

---

## 📌 Objetivo do projeto | Project Goal
**PT:** Simular operações bancárias (como saque) validando regras de negócio e utilizando exceções personalizadas para indicar erros de forma clara.  
**EN:** Simulate banking operations (such as withdrawals) by validating business rules and using custom exceptions to indicate errors clearly.

---

## 🚀 Funcionalidades | Features
✅ **PT:** Criar uma conta com:  
✅ **EN:** Create an account with:
- Número da conta | Account number  
- Nome do titular | Account holder  
- Saldo inicial | Initial balance  
- Limite de saque | Withdraw limit  

✅ **PT:** Realizar saque (`withdraw`) com validações:  
✅ **EN:** Perform withdrawals with validations:
- Valor não pode ultrapassar o limite de saque.  
  Value cannot exceed the withdraw limit.
- Valor não pode ser maior que o saldo disponível.  
  Value cannot exceed the available balance.
- Caso alguma regra seja violada, uma exceção do tipo **BusinessException** é lançada.  
  If any rule is violated, a **BusinessException** is thrown.

---

## 📂 Estrutura do projeto | Project Structure
```

src/
│
├── application/
│   └── Program.java          # PT: Classe principal | EN: Main class
│
├── entities/
│   └── Account.java          # PT: Lógica de conta | EN: Account logic
│
└── exception/
└── BusinessException.java # PT: Exceção personalizada | EN: Custom exception

````

---

## 🛠️ Tecnologias utilizadas | Technologies
- ☕ Java (17+ recomendado | recommended)
- 💻 IDE: Eclipse / IntelliJ
- ✅ Conceitos de POO e tratamento de exceções  
  OOP concepts and exception handling

---

## ▶️ Como executar | How to run
1. **PT:** Clonar o repositório  
   **EN:** Clone the repository
```bash
git clone git@github.com:heliot98/projeto-bank-exception.git
````

2. **PT:** Importar na IDE como projeto Java
   **EN:** Import into your IDE as a Java project

3. **PT:** Executar a classe `Program.java` e seguir as instruções no console
   **EN:** Run `Program.java` and follow the console instructions

---

## 💡 Exemplo de uso | Example usage

**Entrada | Input:**

```
Number: 1234
Holder: João
Initial balance: 500.00
Withdraw limit: 300.00

Enter amount for withdraw:
350.00
```

**Saída | Output:**

```
The amount exceeds withdraw limit
```

Outro exemplo | Another example:

```
Enter amount for withdraw:
200.00
```

```
New balance: 300.00
```

---

## ✨ Aprendizados | Learnings

* **PT:** Criar exceções personalizadas (`BusinessException`).
  **EN:** Create custom exceptions (`BusinessException`).
* **PT:** Aplicar validações de regra de negócio.
  **EN:** Apply business rule validations.
* **PT:** Usar `try/catch` para tratar erros e exibir mensagens amigáveis.
  **EN:** Use `try/catch` to handle errors and show user-friendly messages.

---

## 📌 Autor | Author

👤 **Hélio Tarquínio**
🔗 [LinkedIn](https://www.linkedin.com/in/helio-tarquino-66b894263/)
🔗 [GitHub](https://github.com/heliot98)

---

> **PT:** Projeto desenvolvido para estudo e prática de exceções em Java.
> **EN:** Project developed for learning and practicing exception handling in Java.

```



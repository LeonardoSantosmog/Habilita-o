# Verificador de Idade para Habilitação (CNH)

Este é um script simples em Python que verifica se o usuário tem idade suficiente para tirar a habilitação (CNH), com base na legislação brasileira que exige idade mínima de **18 anos**.

## ✅ Funcionalidades

- Solicita o nome do usuário
- Solicita a idade do usuário
- Verifica se a idade é igual ou superior a 18 anos
- Exibe uma mensagem informando se é possível ou não tirar a habilitação

## 💻 Código Utilizado

```python
nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))

if idade >= 18:
    print(f"Com {idade} anos, você pode se habilitação!!!")
else:
    print(f"Com {idade} anos, você não pode se habilitação")

# 🏭 Fábrica de Brinquedos 🚗👧

Este é um programa em C# que simula a produção otimizada de brinquedos em uma fábrica. O usuário pode escolher entre dois tipos de brinquedos ("Carrinho" ou "Boneca") e realizar operações matemáticas relacionadas à produção de cada um deles.

## ✨ Funcionalidades

- **Escolha do produto:** O usuário pode escolher entre fabricar um 🚗 Carrinho ou uma 👧 Boneca.
- **Carrinho:** O programa solicita um número e calcula o fatorial desse número, representando a quantidade de rodas necessárias para o modelo escolhido.
- **Boneca:** O programa solicita um número e mostra sua fatoração em números primos, representando a quantidade de peças de roupa necessárias para o modelo escolhido.
- **Validação de entradas:** O programa valida as entradas do usuário para evitar valores inválidos.
- **Repetição:** O usuário pode realizar novos cálculos para outros brinquedos até decidir encerrar o programa.

## 🖥️ Como usar

1. **Execute o programa.**
2. **Escolha o tipo de brinquedo:** Digite `Carrinho` ou `Boneca` quando solicitado.
3. **Forneça o número solicitado:** 
   - Para Carrinho: insira um número inteiro positivo para calcular o fatorial.
   - Para Boneca: insira um número inteiro positivo para fatoração em primos.
4. **Veja o resultado exibido na tela.**
5. **Escolha se deseja realizar outro cálculo ou encerrar o programa.**

## 💡 Exemplo de Uso

```
------------- Fábrica de brinquedos -------------
------ Otimização da produção de brinquedos ------
--------------------------------------------------------------------
Digite o tipo de brinquedo: Carrinho / Boneca
obs: Digite a palavra referente ao tipo de brinquedo
Carrinho

Produto válido! Produto escolhido: Carrinho
Digite o número para cálculo do fatorial:
4
O número de rodas necessárias para o modelo desejado é: 24

Deseja realizar o cálculo para mais algum brinquedo? s / n
s

Digite o tipo de brinquedo: Carrinho / Boneca
obs: Digite a palavra referente ao tipo de brinquedo
Boneca

Produto válido! Produto escolhido: Boneca
Digite o número para fatoração:
18
O número de peças de roupa determinado pelos fatores primos do número 18 para este modelo é:
2 3 3 

Deseja realizar o cálculo para mais algum brinquedo? s / n
n

Você escolheu não continuar. Programa encerrado
```

## 🔎 Estrutura do Código

- O código está contido na classe `fabrica_brinquedos`, dentro do namespace `Programa1bimestre`.
- Utiliza laços de repetição e validação de entradas para garantir o funcionamento correto.
- Para o cálculo do fatorial e da fatoração, utiliza apenas lógica básica, sem bibliotecas externas.

## 📦 Requisitos

- .NET Core SDK ou .NET Framework instalado
- Editor de código compatível com C#, como Visual Studio ou Visual Studio Code

## ▶️ Como compilar e executar

1. **Salve o código em um arquivo chamado `Program.cs`.**
2. **Abra o terminal na pasta do arquivo.**
3. **Compile usando:**
   ```
   csc Program.cs
   ```
4. **Execute o programa compilado:**
   ```
   Program.exe
   ```
   ou, caso utilize .NET Core:
   ```
   dotnet run
   ```

## ⚠️ Observações

- Certifique-se de digitar corretamente "Carrinho" ou "Boneca" quando solicitado.
- Apenas números inteiros positivos são aceitos para os cálculos.
- O programa é simples e visa fins educacionais para praticar lógica de programação e manipulação de strings e números em C#.

---

## 👤 Autor

- **Yure Campos Camilo**
- ✉️ ccamposcamilo@gmail.com

---

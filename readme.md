
## 📄 README.md para o Projeto de Códigos Python

Este `README` descreve os dois *scripts* Python contidos neste projeto, que demonstram conceitos básicos de **entrada/saída de dados**, **estrutura condicional (`if/else`)** e **laço de repetição (`for`)**.

-----

## 🚀 Sobre o Projeto

Este projeto contém dois pequenos programas Python para fins de aprendizado e demonstração:

1.  **Verificador de Maioridade:** Um *script* que solicita o nome e a idade do usuário e verifica se ele é maior ou menor de idade.
2.  **Tabuada Simples:** Um *script* que solicita um número inteiro e exibe sua tabuada de multiplicação de 1 a 10.

-----

## 💻 Códigos e Funcionalidades

### 1\. Verificador de Maioridade

Este código utiliza a estrutura **`if/else`** para tomar decisões com base na idade fornecida pelo usuário.

```python
name = input("Qual o seu nome ? ")
idade = int(input("Digite sua idade ? "))

if idade >= 18:
    print(f"Olá {name}, você é maior de idade")
else:
    print(f"Olá {name}, você é menor de idade")
```

-----

### 2\. Tabuada Simples

Este código usa o **laço de repetição `for`** combinado com a função `range()` para iterar sobre os números de 1 a 10 e calcular a tabuada.

```python
num = int(input("Digite um número inteiro: "))

for i in range(1,11):
    resultado = num * i
    print(f"{num} x {i} = {resultado}")
```




## ⚙️ Como Executar

Para rodar o código, você deve ter o **Python instalado** em sua máquina.

1.  Salve o código em um arquivo (ex: `demo.py`).

2.  Abra o terminal ou prompt de comando.

3.  Navegue até o diretório onde você salvou o arquivo.

4.  Execute o *script* usando o comando:

    ```bash
    python demo.py
    ```

5.  O programa solicitará as entradas necessárias para cada seção (nome, idade, e o número para a tabuada).

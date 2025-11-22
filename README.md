# Coffee Machine ☕  
Simulação simples de uma máquina de café em Python.

Este projeto reproduz o funcionamento básico de uma máquina automática de café:  
mostra o menu, verifica ingredientes, processa pagamentos e prepara a bebida.

---

## 🚀 Funcionalidades

- Exibe um menu com opções de bebidas  
- Verifica se há recursos suficientes (água, leite e café)  
- Processa pagamento em moedas  
- Prepara o café e deduz os ingredientes  
- Permite visualizar um relatório dos recursos e do lucro  
- Comando `off` desliga o sistema

---

## 📁 Estrutura do Projeto

coffee-machine/
│
├── main.py
├── menu.py
├── coffee_maker.py
└── money_machine.py


- **main.py** → Arquivo principal que controla o loop da máquina  
- **menu.py** → Lista de bebidas e lógica de busca  
- **coffee_maker.py** → Gerencia os recursos e prepara o café  
- **money_machine.py** → Simula inserção de moedas e pagamentos

---

## ▶️ Como executar

1. Certifique-se de ter o Python instalado (3.8+).
2. No terminal, navegue até a pasta do projeto:
   
   cd coffee-machine e execute python main.py

📋 Comandos disponíveis

latte / espresso / cappuccino → Faz o pedido da bebida

report → Mostra recursos e lucro

off → Desliga a máquina



💰 Pagamento

A simulação pede a quantidade de moedas:

  Quarters = $0.25

  Dimes = $0.10

  Nickles = $0.05

  Pennies = $0.01

Se o valor inserido for suficiente, o programa:

  Aceita o pagamento

  Libera troco

  Prepara a bebida




Exemplo de uso (terminal):

What would you like? (latte/espresso/cappuccino/): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0
Here is $7.5 in change.
Here is your latte ☕️. Enjoy!


📦 To-do (se quiser melhorar)

Adicionar suporte a interface gráfica

Adicionar banco de dados de vendas

Criar log de operações

Simular manutenção preventiva

Tornar o menu configurável via arquivo JSON

# ☕ Coffee Machine Project
### Este projeto é um simulador de uma máquina de café desenvolvido em Python. Ele gerencia recursos (água, leite, café), processa pagamentos em moedas e valida se a transação e a preparação da bebida são possíveis com base no inventário atual.

## Funcionalidades
### O sistema opera em um loop contínuo e oferece as seguintes capacidades:

- Três Opções de Bebidas: Oferece Espresso, Latte e Cappuccino, cada um com receitas e custos distintos definidos em um dicionário de dados.  
- Gestão de Recursos: Monitora a quantidade de água, leite e pó de café disponíveis. Antes de cada pedido, a máquina verifica se há ingredientes suficientes para completar a bebida.  
- Processamento de Moedas: Simula a inserção física de moedas (Quarters, Dimes, Nickles e Pennies) e calcula o valor total inserido.  
- Validação Financeira: Verifica se o dinheiro inserido cobre o custo da bebida e calcula o troco exato, utilizando arredondamento para garantir precisão monetária.  
- Relatórios em Tempo Real: Através do comando report, o usuário pode visualizar o status atual dos ingredientes e o lucro total acumulado pela máquina.  
- Modo de Manutenção: O comando secreto off permite desligar a máquina e encerrar o programa com segurança.

## Tecnologias utilizadas
- Python 3
- Lógica de Programação: Funções modulares, manipulação de dicionários, controle de fluxo (while, if/elif/else) e escopo global/local.

## Como Executar
- Certifique-se de ter o Python instalado em sua máquina.
- Clone este repositório.
- Execute o arquivo principal: main.py
- Siga as instruções no console para escolher seu café e inserir as moedas.

## Aprendizados Relevantes
### Este projeto foi fundamental para praticar o conceito de Programação Modular. Ao invés de repetir códigos para cada tipo de café, foram criadas funções genéricas (como is_resource_sufficient e make_coffee) que recebem argumentos e processam a lógica de forma escalável e limpa.

## 💗 Desenvolvido por
### Heloisa Cadenas no curso 100 days of Python - Udemy

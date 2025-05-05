![Captura de tela 2024-07-15 145508](https://github.com/user-attachments/assets/b12b3aaf-ef68-4f13-8c80-94249f22c617)
💳 Sistema Bancário - Python 💳
📝 Sobre o Projeto
Este projeto é um sistema bancário simples, desenvolvido em Python, que simula as operações bancárias básicas como depósitos, saques, extrato e criação de contas. Ele permite o gerenciamento de clientes, contas correntes e transações.

O código é baseado em um modelo orientado a objetos, utilizando conceitos de herança, polimorfismo e encapsulamento para representar clientes, contas, transações e historico de movimentações.

🎯 Funcionalidades
1. Clientes
Criar novos clientes (Pessoa Física).

Cada cliente pode ter múltiplas contas.

2. Contas
Contas correntes podem ser criadas para os clientes.

Saques e depósitos são realizados nas contas.

Extratos são gerados mostrando todas as transações realizadas.

3. Transações
Saque: Realiza o saque de um valor da conta, com verificação de saldo e limite de saques.

Depósito: Realiza o depósito de um valor na conta.

Extrato: Exibe todas as transações realizadas, bem como o saldo atual.

4. Menu
O sistema exibe um menu interativo onde o usuário pode escolher a operação desejada (Depositar, Sacar, Extrato, Criar Conta, Criar Cliente, Listar Contas ou Sair).

🔧 Tecnologias Usadas
Python: Linguagem de programação principal.

Conceitos de OOP (Programação Orientada a Objetos): Herança, Polimorfismo, Encapsulamento.

⚡ Como Usar
Criação de Cliente: Você pode criar novos clientes, informando dados como nome, CPF, data de nascimento e endereço.

Criação de Conta: Após criar um cliente, você pode criar contas correntes vinculadas a esse cliente.

Realizar Transações: Você pode realizar depósitos, saques e consultar extratos das contas.

Listar Contas: Exibe todas as contas bancárias cadastradas no sistema.

💡 Como Funciona o Código
Classes
Cliente: Representa o cliente do banco, com atributos como endereço e contas associadas.

PessoaFisica: Subclasse de Cliente que adiciona atributos como nome, CPF e data de nascimento.

Conta: Representa a conta bancária de um cliente. Possui operações de saque e depósito, além de um histórico de transações.

ContaCorrente: Subclasse de Conta que implementa limites para saques e o número máximo de saques permitidos.

Transacao: Classe abstrata para definir a estrutura de transações (saques e depósitos).

Saque e Deposito: Classes que implementam transações de saque e depósito, respectivamente.

Historico: Armazena todas as transações realizadas em uma conta.

Fluxo de Execução
O código permite a interação com o usuário por meio de um menu de opções no terminal. O usuário pode realizar operações bancárias como:

Depositar: Realiza o depósito de um valor em uma conta.

Sacar: Realiza o saque de um valor, considerando as limitações de saldo e número de saques.

Extrato: Exibe o histórico de transações realizadas em uma conta.

Criar Cliente: Adiciona um novo cliente ao sistema.

Criar Conta: Cria uma conta bancária vinculada a um cliente existente.

Listar Contas: Exibe todas as contas cadastradas no sistema.

📝 Exemplo de Execução
Menu Principal
plaintext
Copiar
Editar
=============== MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> 
Exemplo de Saque
plaintext
Copiar
Editar
Informe o CPF do cliente: 12345678900
Informe o valor do saque: 100.0

=== Saque realizado com sucesso! ===
💻 Como Rodar o Projeto
Para rodar o projeto, basta executar o arquivo main.py no seu terminal:

bash
Copiar
Editar
python main.py
Este código não requer dependências externas. Certifique-se de ter o Python instalado em sua máquina.

🤝 Contribuindo
Faça um fork deste repositório.

Crie um branch para a nova funcionalidade:

bash
Copiar
Editar
git checkout -b minha-nova-feature
Faça alterações e commit:

bash
Copiar
Editar
git add .
git commit -m "Adiciona nova funcionalidade"
Envie para o seu repositório:

bash
Copiar
Editar
git push origin minha-nova-feature
Abra um Pull Request.

🤖 Contato
Se você tiver sugestões ou dúvidas sobre o projeto, não hesite em abrir uma issue ou entrar em contato diretamente.


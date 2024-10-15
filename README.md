### Projeto criado no curso de Python da DIO.me.


# Sistema Bancário em Python

Este é um sistema bancário simples implementado em Python, que permite realizar operações como depósito, saque, exibição de extrato, criação de contas e usuários, e listar contas. O programa utiliza um menu interativo para que o usuário possa escolher as operações desejadas.

## Funcionalidades

- **Depósito**: Permite ao usuário depositar um valor na conta.
- **Saque**: Permite ao usuário sacar um valor da conta, com limite de saque e número máximo de saques diários.
- **Extrato**: Exibe o extrato bancário com as transações realizadas e o saldo atual.
- **Nova Conta**: Cria uma nova conta associada a um usuário existente.
- **Novo Usuário**: Adiciona um novo usuário ao sistema.
- **Listar Contas**: Lista todas as contas criadas no sistema.

## Limitações do Sistema

- O valor máximo de saque é de R$ 500,00.
- O número máximo de saques permitidos por dia é 3.
- Não é permitido sacar valores negativos ou superiores ao saldo da conta.

## Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Faça o download ou clone este repositório.
3. Navegue até o diretório do projeto no terminal.
4. Execute o programa com o seguinte comando:

   ```bash
   python nome_do_arquivo.py
   ```

5. Utilize o menu interativo para realizar as operações desejadas.

## Exemplo de Uso

```bash
====================== MENU ======================
[d]    Depositar
[s]    Sacar
[e]    Extrato
[nc]   Nova Conta
[lc]   Listar Contas
[nu]   Novo Usuário
[q]    Sair
=> 
```

Escolha uma opção do menu e siga as instruções exibidas.

## Dependências

Este projeto não requer bibliotecas externas, apenas o Python padrão.

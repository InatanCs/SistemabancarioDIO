# Sistema Bancário Simples

Este é um sistema bancário simples desenvolvido em Python. Ele permite que usuários façam depósitos, saques e consultem o extrato de suas contas. O sistema foi criado como parte de um exercício prático para a DIO (Digital Innovation One).

## Funcionalidades

- **Depósito**: Permite ao usuário depositar uma quantia em sua conta.
- **Saque**: Permite ao usuário sacar uma quantia de sua conta, respeitando o saldo disponível, o limite de saque e o número máximo de saques diários.
- **Extrato**: Permite ao usuário consultar o extrato de todas as movimentações da conta, bem como o saldo atual.

## Como Usar

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/SeuUsuario/SistemabancarioDIO.git
    ```

2. **Acesse o diretório do projeto**:
    ```bash
    cd SistemabancarioDIO
    ```

3. **Execute o script Python**:
    ```bash
    python seu_script.py
    ```

4. **Siga as instruções no menu**:

    ```
    ==================== Seja Bem-vindo! ====================

    [1] Depositar
    [2] Sacar
    [3] Extrato
    [4] Sair
    => 
    ```

## Exemplo de Uso

- **Depósito**:
    - O usuário escolhe a opção `1` e informa o valor do depósito.
    - Se o valor for válido, o depósito é realizado e uma mensagem de sucesso é exibida.

- **Saque**:
    - O usuário escolhe a opção `2` e informa o valor do saque.
    - O sistema verifica se o saque é possível (saldo suficiente, limite de saque, número de saques diários).
    - Se o saque for realizado com sucesso, uma mensagem de sucesso é exibida.

- **Extrato**:
    - O usuário escolhe a opção `3` para ver todas as movimentações da conta e o saldo atual.

- **Sair**:
    - O usuário escolhe a opção `4` para sair do sistema.

## Requisitos

- Python 3.6 ou superior

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

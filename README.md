# Jogo de Robôs

Este é um jogo simples de combate entre robôs desenvolvido em Python. O objetivo é simular batalhas entre dois robôs, gerenciando a energia, ataque e defesa de diferentes partes dos robôs.

## Estrutura do Projeto

O projeto é composto por uma única script Python que define a lógica do jogo e a interação entre os robôs.

### Classes Principais

- **`Part`**: Representa uma parte do robô, com atributos de ataque, defesa e consumo de energia. Inclui métodos para atualizar o status e verificar se a parte está disponível para uso.
- **`Robot`**: Representa um robô com várias partes. Gerencia o status do robô, a energia restante e a execução de ataques.
- **Funções**: Inclui funções para criar robôs, gerenciar o jogo e realizar ataques.

## Funcionalidades

- **Criação de Robôs**: Permite ao usuário criar dois robôs, escolhendo um nome e uma cor para cada um.
- **Batalhas**: Os robôs podem atacar um ao outro, reduzindo a energia e a defesa das partes do robô adversário.
- **Status do Robô**: Mostra informações sobre cada parte do robô, incluindo nome, status, ataque, defesa e consumo de energia.

## Como Executar o Jogo

1. **Clone o Repositório**

   ```bash
   git clone <URL_DO_REPOSITÓRIO>
   cd <NOME_DO_REPOSITÓRIO>
   ```

2. **Execute o Jogo**

   Para iniciar o jogo, execute o seguinte comando:

   ```bash
   python <NOME_DO_ARQUIVO>.py
   ```

3. **Siga as Instruções**

   - Escolha um nome e uma cor para cada robô.
   - Durante o jogo, escolha as partes do robô para atacar e quais partes do inimigo atacar.

## Estrutura do Código

- **`Part`**: Define as partes do robô e suas características.
- **`Robot`**: Define o robô e gerencia suas ações e status.
- **Funções auxiliares**: Gerenciam a entrada do usuário e a lógica do jogo.

## Cores

O jogo utiliza códigos de cores ANSI para exibir o texto colorido no terminal. As cores disponíveis são:

- Preto
- Azul
- Ciano
- Verde
- Magenta
- Vermelho
- Branco
- Amarelo
- ![Screenshot (433)](https://github.com/user-attachments/assets/721726f0-2a86-409c-8c2c-99674c931853)


## Observações

- Certifique-se de executar o script em um terminal que suporte códigos de cores ANSI para ver a formatação correta.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

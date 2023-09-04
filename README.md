# Sistema de Gerenciamento de Pedidos de Pizzas 🍕

O Sistema de Gerenciamento de Pedidos foi desenvolvido com o objetivo de otimizar e centralizar os pedidos de pizzas, permitindo uma experiência personalizada de escolha e monitoramento de cada etapa do pedido.

## Funcionalidades:

### 1. Personalização do Pedido:
   * **Borda**: Escolha entre opções deliciosas como cheddar e catupiry.
   * **Massa**: Selecione o tipo, seja ela comum, temperada ou integral.
   * **Sabores de Pizzas**: Os clientes têm a liberdade de escolher até 3 sabores dentre uma variedade, incluindo:
     - Quatro queijos
     - Frango com catupiry
     - Calabresa
     - Lombinho
     - Filé com cheddar
     - Portuguesa
     - Margherita

### 2. Dashboard de Pedidos:
   * **Visão Geral**: Todos os detalhes do pedido ao alcance, desde o ID, tipo de borda, tipo de massa, sabores escolhidos até o status atual.
   * **Gestão de Status**: Atualize em tempo real o status do pedido, marcando-o como "em produção", "em entrega" ou "concluído".
   * **Organização**: Mantenha sua aba limpa deletando os pedidos concluídos. Novos pedidos na aba de seleção são automaticamente refletidos no dashboard.

## Tecnologia e Estrutura de Dados:

* **Interface Gráfica**: Criada com HTML e CSS, proporcionando uma navegação intuitiva.
* **Backend e Integração**: Com PHP, garantimos uma integração fluida e segura ao banco de dados.
* **Banco de Dados**: Desenvolvido a partir de um diagrama ER e modelado em MYSQL, todos os pediddos são armazenados no banco. O banco inclui tabelas como:
  - bordas -> Tipos de borda.
  - massas -> tipos de massa.
  - pedidos -> Pedidos realizados, inclui a pizza escolhida e status do pedido.
  - pizza_sabor -> pivot table para "pizzas" e "sabores".
  - pizzas -> tabela da pizza, incluindo borda e massa.
  - sabores -> sabores existentes.
  - status -> status existentes.

---

#### Segue imagem do diagrama:

![image](https://github.com/GabCarmona/PizzariaSQL/assets/118035572/431631bf-317e-40d9-9a47-704ad850a388)

#### Segue Vídeo de funcionamento:

https://github.com/GabCarmona/PizzariaSQL/assets/118035572/a9a185f0-f396-4898-8b34-c0f7d99c55f0



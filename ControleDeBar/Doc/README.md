# Sistema de Controle de Bar

O Sr. John Wick, propriet�rio do Bar Academia do Programador, precisa controlar melhor o que cada cliente consumiu em seu estabelecimento para aumentar a produtividade e alavancar o sucesso do seu bar. A equipe do Bar Academia do Programador precisa de mais agilidade na realiza��o das atividades e processos e, desta forma, necessita de um sistema que ajude a controlar as quest�es financeiras do estabelecimento.

## Requisitos Funcionais

### Gerenciamento de Clientes
- Adicionar novos clientes.
- Listar todos os clientes cadastrados.
- Editar as informa��es dos clientes.
- Excluir clientes.

### Gerenciamento de Gar�ons
- Adicionar novos gar�ons.
- Listar todos os gar�ons cadastrados.
- Editar as informa��es dos gar�ons.
- Excluir gar�ons.

### Gerenciamento de Mesas
- Adicionar novas mesas.
- Listar todas as mesas cadastradas.
- Editar as informa��es das mesas.
- Excluir mesas.

### Gerenciamento de Produtos
- Adicionar novos produtos ao card�pio.
- Listar todos os produtos dispon�veis.
- Editar as informa��es dos produtos.
- Excluir produtos.

### Registro de Consumo
- Registrar o consumo dos clientes.
- Associar cada consumo a um cliente espec�fico e a uma mesa espec�fica.
- Permitir adicionar e remover pedidos de uma determinada conta.

### Relat�rios e Faturamento
- Gerar um relat�rio detalhado do consumo por cliente.
- Gerar um relat�rio geral do bar, incluindo o total faturado.
- Visualizar as contas abertas e o total faturado no dia.

## Regras de Neg�cio

### Cliente
- Cada cliente deve ter um ID �nico.
- O nome do cliente � obrigat�rio e deve ser �nico.

### Gar�om
- Cada gar�om deve ter um ID �nico.
- O nome do gar�om � obrigat�rio e deve ser �nico.

### Mesa
- Cada mesa deve ter um ID �nico.
- O n�mero da mesa � obrigat�rio e deve ser �nico.

### Produto
- Cada produto deve ter um ID �nico.
- O nome do produto � obrigat�rio.
- O pre�o do produto � obrigat�rio.

### Consumo
- Cada registro de consumo deve incluir a data e hora do consumo, o cliente, o gar�om que atendeu e a mesa.
- Cada consumo deve estar associado a um ou mais produtos.

## Estrutura do Projeto

### In�cio com Clientes
- Implementar a funcionalidade de gerenciamento de clientes (adicionar, listar, editar, excluir).

### Expans�o para Gar�ons, Mesas e Produtos
- Adicionar funcionalidades semelhantes para gar�ons, mesas e produtos.

### Registro de Consumo e Relat�rios
- Implementar o registro de consumo e a gera��o de relat�rios detalhados e gerais.
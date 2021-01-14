- Clientes
- Produtos
- Pedidos => adicionou o `customer_id`
- PedidosProdutos(`ManytoMany`) => armazena: `id, id_product, qtde, value, order_id`

### 1ª Etapa => @shared

**Infra** => tudo que está relacionado a serviços externos
- containers
- migrations

### 2ª Etapa => Customers

- `entities` => incluir as referências ao typeorm
  - Entity,
  - Column,
  - PrimaryGeneratedColumn,
  - CreateDateColumn,
  - UpdateDateColumn,

- `controller` => instanciar as variáveis e vincular ao `CreateCustomerService`

### 3ª Etapa => Products

- `entities`
- `typeorm - repositories`
- `services`

### 4ª Etapa => Orders

- `entities` => Oerder e OrdersProducts
- `typeorm - repositories`
- `controller` => começar com o método `create`
- `services` => começar com FindOrderService





Modelo de Entidade-Relacionamento para E-commerce
Descrição:
Este projeto contém o modelo de Entidade-Relacionamento (ER) para um sistema de e-commerce. O modelo foi projetado para abordar funcionalidades-chave, como gestão de clientes, inventário de produtos, pedidos, pagamentos e entregas. Também incorpora refinamentos para evitar redundâncias e garantir clareza nos relacionamentos entre as entidades.

Funcionalidades:
1. Gestão de Clientes
Suporta tanto clientes individuais (CPF) quanto clientes empresariais (CNPJ).
Diferencia clientes Pessoa Física (PF) e Pessoa Jurídica (PJ) por meio do atributo Tipo.
2. Sistema de Pagamento:
Suporta múltiplos métodos de pagamento por pedido, incluindo cartão, Pix e outros.
Inclui detalhes como tipo de pagamento e número de parcelas.
Utiliza um relacionamento muitos-para-muitos (N:N) entre pedidos e pagamentos.
3. Produtos e Inventário:
Rastreia produtos, suas categorias e descrições.
Relaciona produtos com locais de estoque e quantidades, garantindo a rastreabilidade dos estoques.
4. Pedidos e Entregas:
Suporta múltiplos produtos por pedido com uma estrutura de relacionamento clara.
Rastreia o status da entrega e os detalhes de envio, incluindo códigos de rastreamento.
5. Gestão de Fornecedores e Vendedores:
Diferencia entre fornecedores e vendedores terceiros.
Permite a associação de produtos com seus respectivos provedores.

Refinamentos Realizados:
> Generalização da entidade Cliente em subclasses específicas para PJ e PF.
> Adição da entidade Entrega para gerenciar status de entregas e códigos de rastreamento.
> Estabelecimento de relacionamentos para lidar com múltiplos métodos de pagamento para um único pedido.
> Melhoria na nomenclatura dos atributos para maior clareza e consistência.

Diagrama de Entidade-Relacionamento
O diagrama ER representa visualmente as entidades e seus relacionamentos. As principais entidades incluem:
Cliente
Cadastro
Pedido
Pagamento
Entrega
Produtos
Fornecedor
Terceiro - Vendedor
Estoque

Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, sinta-se à vontade para enviar.

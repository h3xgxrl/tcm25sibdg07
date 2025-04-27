# C2 : Especificação de Requisitos

Para que o sistema de informação seja eficaz, é essencial identificar os principais tipos de utilizadores (actores) e as funcionalidades (casos de uso) que estarão disponíveis para cada um deles.
Tipos de Utilizadores (Actores)
Administrador
O Administrador será responsável pela gestão global do sistema. Este perfil tem permissões totais sobre todos os dados, podendo adicionar, editar ou excluir produtos, categorias, clientes e encomendas. Além disso, o Administrador tem acesso ao histórico de transações e à gestão do stock.
Gestor de Stock
O Gestor de Stock terá acesso limitado à gestão de produtos e ao estado do stock. Este utilizador será responsável por atualizar as quantidades de produtos e monitorizar o nível de stock, gerando alertas para reposição quando necessário.
Cliente
O Cliente terá um perfil restrito, podendo apenas visualizar os produtos disponíveis, realizar compras e consultar o seu histórico de encomendas. Além disso, terá acesso aos dados de entrega e ao estado atual da sua encomenda.
Atendimento ao Cliente
O Atendimento ao Cliente terá permissões para aceder aos detalhes das encomendas e interagir diretamente com os clientes, resolvendo dúvidas ou questões relacionadas com os pedidos. Este perfil poderá também atualizar o estado das encomendas conforme necessário.
Funcionalidades (Casos de Uso)
A seguir, são descritas as principais funcionalidades do sistema, de acordo com os tipos de utilizadores:
Administrador:
Gestão de Produtos: Registo, edição e eliminação de produtos, incluindo nome, preço, categoria e quantidade em stock.
Gestão de Categorias de Produtos: Adicionar, editar ou excluir categorias de produtos.
Gestão de Clientes: Registar novos clientes, editar dados e eliminar registos de clientes.
Gestão de Encomendas: Visualizar, editar e atualizar o status das encomendas.
Gestão de Stock: Monitorizar o stock de produtos, incluindo alertas de reposição e ajustes de inventário.
Consulta de Relatórios: Visualizar relatórios sobre vendas, stock e comportamentos de clientes.
Gestor de Stock:
Gestão de Produtos: Atualização de quantidades de produtos em stock, visualização de produtos em falta e geração de alertas para reposição.
Consulta de Stock: Acesso a relatórios sobre o estado do stock e produtos com baixo inventário.
Cliente:
Visualização de Produtos: Navegar pelo catálogo de produtos, incluindo filtros de categoria e preço.
Realização de Encomendas: Adicionar produtos ao carrinho, realizar o checkout e efetuar o pagamento.
Consulta de Encomendas: Aceder ao histórico de compras e acompanhar o estado das encomendas em tempo real.
Atendimento ao Cliente:
Consulta de Encomendas: Acesso aos detalhes de encomendas dos clientes, permitindo a atualização do status e a resolução de problemas.
Gestão de Reclamações: Registar e acompanhar as reclamações dos clientes, encaminhando-as para o administrador, se necessário.


---
[< Previous](rei01.md) | [^ Main](/../../) | [Next >](rei03.md)
:--- | :---: | ---: 

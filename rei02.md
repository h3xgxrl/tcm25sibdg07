# C2 : Especificação de Requisitos

# Tipos de Utilizadores (Atores) e Funcionalidades (Casos de Uso)

## Tipos de Utilizadores (Atores)

### Administrador

O Administrador será responsável pela gestão global do sistema.  
Este perfil tem permissões totais sobre todos os dados, podendo:
- Adicionar, editar ou excluir produtos, categorias, clientes e encomendas.
- Aceder ao histórico de transações.
- Gerir o stock.

### Gestor de Stock

O Gestor de Stock terá acesso limitado à gestão de produtos e ao estado do stock.  
Responsabilidades:
- Atualizar as quantidades de produtos.
- Monitorizar o nível de stock.
- Gerar alertas para reposição de produtos.

### Cliente

O Cliente terá um perfil restrito, podendo:
- Visualizar os produtos disponíveis.
- Realizar compras.
- Consultar o histórico de encomendas.
- Aceder aos dados de entrega e ao estado atual da sua encomenda.

### Atendimento ao Cliente

O Atendimento ao Cliente terá permissões para:
- Aceder aos detalhes das encomendas.
- Interagir com os clientes para resolver dúvidas ou questões relacionadas com os pedidos.
- Atualizar o estado das encomendas conforme necessário.

---

## Funcionalidades (Casos de Uso)

### Administrador

- **Gestão de Produtos:**  
  Registo, edição e eliminação de produtos (nome, preço, categoria e stock).

- **Gestão de Categorias de Produtos:**  
  Adicionar, editar ou excluir categorias.

- **Gestão de Clientes:**  
  Registar novos clientes, editar dados e eliminar registos.

- **Gestão de Encomendas:**  
  Visualizar, editar e atualizar o status das encomendas.

- **Gestão de Stock:**  
  Monitorizar o stock, gerar alertas de reposição e ajustar inventário.

- **Consulta de Relatórios:**  
  Visualizar relatórios sobre vendas, stock e comportamento dos clientes.

### Gestor de Stock

- **Gestão de Produtos:**  
  Atualizar quantidades de produtos em stock, visualizar produtos em falta e gerar alertas.

- **Consulta de Stock:**  
  Acesso a relatórios sobre o estado do stock e produtos com baixo inventário.

### Cliente

- **Visualização de Produtos:**  
  Navegar pelo catálogo de produtos, com filtros de categoria e preço.

- **Realização de Encomendas:**  
  Adicionar produtos ao carrinho, realizar o checkout e efetuar o pagamento.

- **Consulta de Encomendas:**  
  Aceder ao histórico de compras e acompanhar o estado das encomendas em tempo real.

### Atendimento ao Cliente

- **Consulta de Encomendas:**  
  Acesso aos detalhes das encomendas dos clientes, atualização do status e resolução de problemas.

- **Gestão de Reclamações:**  
  Registar e acompanhar reclamações dos clientes, encaminhando-as para o administrador quando necessário.



---
[< Previous](rei01.md) | [^ Main](/../../) | [Next >](rei03.md)
:--- | :---: | ---: 

# Desafio Backend Web: API NestJs + Jest com MongoDb pa

## História
Somos uma distribuidora de produtos diversos e precisamos de uma API onde possamos gestar os pedidos de nossos clientes, sendo assim precisamos de uma API nos padrões RESTFul que permita a um GERENTE gestar os Pedidos e seus Produtos e que permita ao nosso CLIENTE, fazer pedidos, mas não alterá-los

### Requisitos funcionais
1. Como GERENTE gostaria de INCLUIR um novo produto ao catálogo
2. Como GERENTE gostaria de ALTERAR um produto existente no catálogo
3. Como GERENTE gostaria de REMOVER o produto do meu catálogo da loja
4. Como GERENTE gostaria de LISTAR os produtos cadastrados
5. Como GERENTE gostaria de BUSCAR produtos pela sua DESCRIÇÃO
6. Como GERENTE preciso que os resultados da LISTA sejam PAGINADOS
7. Como GERENTE quero que apenas um GERENTE possa incluir, alterar ou remover remover produtos
8. Como GERENTE quero que apenas um GERENTE possa alterar um pedido
8. Como CLIENTE quero CADASTRAR um PEDIDO com um ou mais produtos vinculados a ele
9. Como CLIENTE quero visualizar todos os meus pedidos e ver o status em que estão
10. Como GERENTE quero LISTAR os pedidos de compra em ABERTO
11. Como GERENTE quero ALTERAR o status de um pedido de ABERTO para CONCLUÍDO

### Requisitos não funcionais
1. A API deve usar [NestJs](https://nestjs.com/) com Typescript
2. A API deve seguir um padrão [REST](https://cloud.google.com/apis/design)
3. A API deve ter pelo menos 3 testes unitários com [JEST](https://jestjs.io/pt-BR/)
4. A API deve usar o [Prisma ORM](https://www.prisma.io/)
5. A API deve persitir em um banco de dados (Preferencialmente o MongoDB. Não sendo possível, utilizar PostgreSQL)

### Entrega
	- Um repositório GitHub
  - README.md com todas as informações necessárias para rodar a API e testar cada um dos requisitos funcionais
	- Um ambiente rodando a aplicação

### Critérios de avaliação
	- Ambiente rodando a aplicação corretamente
  - Entendimento dos requisitos
	- Afinidade com a ferramenta utilizada
	- Testes unitários
	- Estrutura de arquivos
	- Padrão de escrita do código
	- Utilização de boas práticas

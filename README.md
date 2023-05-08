# Sistema de Gerenciamento de Pedidos de Restaurante <h1>
Esta atividade foi feita na disciplina de Tecnologia em Desenvolvimento de Sistemas
<br>
Grupo: Bruna Eloisa Schvingel, Isabella Gon e Lissa Takahashi.
## Classes básicas: <h2>
* Mesa: representa as mesas do restaurante. Contém atributos como número da mesa e status da mesa (ocupada, livre), hora de abertura em caso de estar ocupada.
* Garçon: representa os garçons do restaurante. Contém atributos como nome, sobrenome, número de identificação e número de telefone.
* Categoria: representa as categorias de produtos disponíveis no restaurante. Contém atributos como nome e descrição.
* Produto: representa os produtos disponíveis no restaurante. Contém atributos como nome, descrição, preço e categoria.
* Atendimento: representa o atendimento de uma mesa por um garçon em um determinado momento. Contém atributos como a mesa atendida, o garçon responsável o horário do pedido e os produtos solicitados.

Associações: Um garçon pode atender várias mesas, registrando os produtos pedidos em cada atendimento. Uma mesa pode ser atendida por vários garçons.  Um produto pertence a uma categoria.

## Instruções de como executar a aplicação <h2>
Para executar o programa, faça o download do arquivo .zip e abra ele no Visual Studio Code, vá em ProjetoGerenciamentoRestaurante.API e em seguida Program.cs clique com o botão direito, abra o terminal e digite "dotnet watch run", assim será executada a API. Para executar as Pages, realiza-se o mesmo procedimento, porém em ProjetoGerenciamentoRestaurante.RazorPages.

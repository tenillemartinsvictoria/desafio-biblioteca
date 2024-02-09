# desafio-biblioteca
Aplicação que faz a gestão de uma biblioteca de livros

Você deverá criar uma aplicação que faça a gestão de uma biblioteca de livros, onde deverá ser implementado as seguintes operações.

Cadastro de Livros. (Título do livro, tipo de literatura (infantil, suspense, terror, educacional, filosofia, etc), status, nome do autor, qtde de páginas, foto da capa)
Edição de livros cadastrados.
Busca de livros cadastrados por nome, tipo de literatura e por status (emprestado, reservado ou disponível). A busca deve ser paginada, 10 livros por página.
Deletar livro cadastrado. Somente pode deletar livros que não estejam emprestados. Se o livro estiver reservado, cancelar a reservar e enviar um e-mail avisando a pessoa que tinha reservado.
Reservar livro para empréstimos
Somente pode-se agenda o empréstimo 2 antes da data da retirada;
É Permitido reservar um livro que já esteja emprestado, desde que a data da reservar seja posterior a data da entrega do livro emprestado;
Quando existir uma reserva, o backend deve enviar um e-mail no dia da retirada para lembrar o cliente sobre a reserva.
Caso o cliente não retire o livro no dia da reserva, no dia seguinte a reserva deve ser cancelada e o status do livro atualizado para disponível.
Processo para cancelar a reserva
Processo de empréstimo. Somente pode alugar os livros que estejam disponíveis e não estejam reservados e nem emprestado;
Faltando um dia para terminar o prazo do empréstimo, deve ser enviado um e-mail lembrando o cliente da devolução.
Caso o cliente não devolva o livro na data agendada, deve ser cobrado uma multa do cliente no valor de R$5,00 por dia de atraso
Processo para devolução do livro
Criar um endpoint para listar os cliente inadimplentes, ou seja, que não devolveram o livros, nessa lista deve retornar o nome do cliente, o valor devido da multa baseado na quantidade de dias em atraso, data que ele deveria ter devolvido, titulo do livro emprestado.
A lista deve ser retornada paginada.
10 livros por página
Retorna a quantidade de páginas total
Retornar a página que o cliente esta visualizando
Criar um endpoint para avançar e retornar as páginas. 
Criar um endpoint para formalizar a devolução e pagamento da multa![Uploading image.png…]()


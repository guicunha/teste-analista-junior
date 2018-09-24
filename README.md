# teste-analista-junior

## PHP + Laravel

A idéia do teste é descobrir como a candidata/candidato lida com um projeto zero to deploy.

1 – Criar uma conta no Github caso não possua.

2 – Criar um Projeto em Laravel e implementar login, poderá ser tanto via session quanto via oAuth2.

3 – Criar entidades e suas respectivas tabelas de um cadastro padrão:

    • Cadastro: nome, sobrenome, titulacao, CPF, RG, e-mail e etc.
    • Endereço: Endereço completo
    • Filme que já assistiu: titulo do filme, ano de lancamento, diretor, nota do filme, sinopse do filme.

4 – Cada cadastro poderá ter um número indeterminado de endereços e um número indeterminado de filmes, porém deverá ter um endereço marcado como principal.

5 – Criar as telas para inserção e atualização dos referidos dados.

6 – Criar as listas referentes aos filmes de cada usuário, lista de todos os usuários e endereços destes usuários.

7 – Ao clicar em um cadastro, na lista de cadastros você deverá ver os detalhes deste cadastro, seja em nova página ou na mesma página através de modal ou outro elemento gráfico.
	 
Poderá ser utilizado bibliotecas de terceiro, qualquer modelo ou paradigma de estruturação de código desde que respeite o style coding do laravel.

Caso não tenha concluído o teste indique no README.md o que faltou e qual foi o maior desafio no iten(s) faltantes. Colocar no README.md também as observações de como foi realizado, porque foi realizado de determinada maneira e porque usou alguma biblioteca de terceiros (o que é totalmente recomendável se necessário).

Caso julgue alterar os requisitos do CRUD o faça, seja para inserção de capa do filme ou qualquer outro campo, toda melhoria será considerada bem-vinda na implementação.

Caso não utilize alguma migration, enviar também o dump do banco de dados.

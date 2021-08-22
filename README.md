# Exercicio_semana6-Reprograma
Entrega do exercício da semana 6 da reprograma.

On12-TodasEmTech-s6-Introducao-Node
Turma Online 12 | Back-end | 2021 | Introdução à API: HTTP e NodeJS

Para casa


# 1- Qual a relação entre os métodos HTTP e o CRUD?

CRUD é a composição da primeira letra de 4 funções básicas de um sistema que trabalha com banco de dados:

✅ C: Create (criar) - criar um novo registro

👁 R: Read (ler) - ler (exibir) as informações de um registro

♻️ U: Update (atualizar) - atualizar os dados do registro

❌ D: Delete (apagar) - apagar um registro

HTTP é um protocolo (protocol) que permite a obtenção de recursos, como documentos HTML. É a base de qualquer troca de dados na Web e um protocolo cliente-servidor, o que significa que as requisições são iniciadas pelo destinatário, geralmente um navegador da Web.

# 2 - Comente, com exemplos, a diferença entre o PUT e o PATCH.

Os métodos HTTP PUT e PATCH são usados para indicar um requisição de alteração de dados.

Geralmente, ao usar-se o PUT, fica legível que a alteração do dado será com referência a entidade completa.

Exemplo: (/usuario/1234) :

Resultado: {'id': 1234, 'name': 'Joao', 'idade': 25, 'documento': '123.321.12-X'}

O PATCH é usado para atualização parcial, quando você não quer mandar o payload completo.

Exemplo: (/usuario/1234) :

Resultado: {'name': 'João'}

# 3 - Assim como na aula, apresente os dados dos JSONs no console

No colors-rgb.js apresente o nome da cor e o codigo RGB como no exemplo: "gainsboro - rgb(220, 220, 220, 1)"
No estados-cidade.js apresente o nome do Estado, a sigla e todas as cidadades, sem arrays aparentes no console
No filmes.js apresente titulo, plot, generos e lingua. Genero e lingua devem ser apresentados em arrays no console.
Defina o conceito de idempotência e como uma API pode ser idempotente

Cite alguns diferentes padrões de projetos de software

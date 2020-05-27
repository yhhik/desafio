# Desafio

O projeto deve conter três funcionalidades, dois CRUD's(curso e aluno) e uma tela onde o usuário possa matricular o aluno ao curso. O banco deve ter a seguinte estrutura:
	
| ALUNO   	|     SEXO     |     CURSO      | ALUNO_CURSO
|--|--|--|--|
 |id_aluno      |  id_sexo     |   id_curso|  id_curso|
| nome   |  descricao    |  nome| id_aluno
 |cpf| | professor | |
| rg| | turno
| id_sexo| | qtd_vagas |

# Regras

* Antes de excluir um curso, caso existam alunos matriculados no curso, deve ser apresentada a seguinte mensagem: "Não é possível concluir a operação, pois, há alunos matriculados no curso."
* Antes de cada matrícula, deve ser verificado se há vagas disponíves. Caso não, deve ser apresentado a seguinte mensagem: " Não foi possível realizar a matrícula, não há vagas." 


# Tecnologias

As seguintes tecnologias ou frameworks devem ser utilizadas:

* Maven
* Hibernate
* SpringBoot
* Angular 2 ou superior
* Lombok (Opcional)
* Teste Unitário (Opcional)
